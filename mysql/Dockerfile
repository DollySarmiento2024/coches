FROM mysql:latest

# contraseña root base de datos
ENV MYSQL_ROOT_PASSWORD=fernanda 

#nombre base de datos
ENV MYSQL_DATABASE=concesionario

# usuario y contraseña base de datos
ENV MYSQL_USER=fernanda
ENV MYSQL_PASSWORD=fernanda

COPY concesionario.sql /docker-entrypoint-initdb.d/
