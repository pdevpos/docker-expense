FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD="ExpenseApp@1" \
    MYSQL_PASSWORD="ExpenseApp@1" \
    MYSQL_USER="expense" \
    MYSQL_DATABASE="transactions"
COPY sql/*.sql /docker-entrypoint-initdb.d/