# Imagem oficial do MySQL
FROM mysql:8.0
# Variáveis de ambiente para configuração inicial
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=meubanco
ENV MYSQL_USER=usuario
ENV MYSQL_PASSWORD=senhausuario
# Porta padrão do MySQL
EXPOSE 3306
# Copiar scripts de inicialização (opcional)
COPY ./initdb /docker-entrypoint-initdb.d