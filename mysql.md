# Banco Mysql Docker

> Para a execução de um banco de dados Mysql em um ambiente de desenvolvimento onde os dados não precisam persistir, tendo como parâmetro as variáveis de ambiente de nome de usuário, nome do banco e senha do mesmo, execute o seguinte comando:

```bash
docker run --name Mysql-dev -e MYSQL_ROOT_PASSWORD=docker_pwd -e MYSQL_USER=docker_usr -e MYSQL_DATABASE=curso_docker -p 3306:3306 -d mysql
