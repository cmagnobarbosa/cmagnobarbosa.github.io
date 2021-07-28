# Realizando Backup de dados do MongoDB


Neste primeiro post, irei apresentar uma dica rápida dos passos para realizar
o backup e restauração do banco de dados não relacional MongoDB.

Versão utilizada: MongoDB 4.4


Os passos abaixo devem ser realizados no terminal.
### Backup de um banco completo

``` console
mongodump --db <banco> --out <pasta>
```

### Como realizer o backup de uma coleção especifica
``` console
mongodump --collection=<colecao> --db <banco> --out <pasta>
```
### Restaurar

``` console
mongorestore --db <db_nome> pasta
```
