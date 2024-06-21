### Comandos docker:

```bash
# Rodar containers:
$ docker compose up
# Encerrar containers:
$ docker compose up
# Acessar bash do container db:
$ sudo docker compose exec db bash
# Acessar bash do container app:
$ sudo docker compose exec app bash
```

### Comandos mysql:

São executados no bash do container **db**

```bash
# Acessar bash do mysql:
$ mysql -uroot -proot
# Mostrar tabelas:
$ show databases;
# Selecionar tabela:
$ use nest;
```

### Comandos prisma:

```bash
# Rodar migration:
$ npx prisma migrate dev
# Formatar arquivo schema.prisma:
$ npx prisma format
```
