ARG root_pwd

FROM mysql:5.7

COPY my.cnf /etc/mysql/my.cnf

CMD echo "Build number: ${root_pwd}"

RUN mysql -uroot -p${root_pwd} -e"GRANT REPLICATION SLAVE ON *.* TO 'rpl_user'@'%' IDENTIFIED BY '123456';"