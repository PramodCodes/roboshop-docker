FROM mysql:5.7
ENV MYSQL_ROOT_PASSWORD=RoboShop@1 \
    MYSQL_DATABASE=cities \
    MYSQL_USER=shipping \
    MYSQL_PASSWORD=secret
# scripts will be pickeup from entrypoint automatically
COPY scripts/* /docker-entrypoint-initdb.d/
