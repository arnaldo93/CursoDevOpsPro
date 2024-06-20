# Banco Postgres Docker

> Para a execução de um banco de dados Postgres em um ambiente de desenvolvimento onde os dados não precisam persistir, tendo como parâmetro as variáveis de ambiente de nome de usuário, nome do banco e senha do mesmo, execute o seguinte comando:

```bash
docker run --name postgres-dev -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker -p 5432:5432 -d postgres
