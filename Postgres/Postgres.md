# Iniciando banco e administrando via interface grática com Docker

### Iniciando o banco de dados:
```
$ docker run --name some-postgres -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres
```

--name = escolha o nome

POSTGRES_USER e POSTGRES_PASSWORD, você pode deixar o padrão, apenas para fins de teste.

### Iniciando o pgAdmin
```
docker run --name pgadmin -e PGADMIN_DEFAULT_EMAIL=email_do_usuario -e PGADMIN_DEFAULT_PASSWORD=senha_do_usuario dpage/pgadmin4
```

#### Rode o inspect para pegar os ips dos containers, após isso acesse o pgadmin via browser e depois conecte o banco que subiu no primeiro comando


# Dockercompose

Podemos utilizar o docker compose para criação e integração dos dois containers.

### Referências
https://hub.docker.com/_/postgres/

https://hub.docker.com/r/dpage/pgadmin4/

https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html


