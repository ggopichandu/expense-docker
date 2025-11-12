# FROM mysql:8.0
# ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1 \
#     MYSQL_USER=expense \
#     MYSQL_PASSWORD=ExpenseApp@1 \
#     MYSQL_DATABASE=transactions
# COPY scripts/*.sql /docker-entrypoint-initdb.d/

FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
RUN echo "Hello World"
COPY scripts/*.sql /docker-entrypoint-initdb.d