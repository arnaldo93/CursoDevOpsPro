# Banco Mysql Docker

> Para a execução de um banco de dados Mongodb em um ambiente de desenvolvimento onde os dados não precisam persistir, tendo como parâmetro as variáveis de ambiente de nome de usuário e senha do banco, execute o seguinte comando:

```bash
docker run --name Mongodb-dev -e MONGO_INITDB_ROOT_PASSWORD=docker_pwd -e MONGO_INITDB_ROOT_USERNAME=docker_usr -p 27017:27017 -d mongo
