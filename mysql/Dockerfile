FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD="root" \
    MYSQL_PASSWORD="ExpenseApp@1" \
    MYSQL_USER="expense" \
    MYSQL_DATABASE="transactions"
COPY mysql/*.sql /docker-entrypoint-initdb.d/