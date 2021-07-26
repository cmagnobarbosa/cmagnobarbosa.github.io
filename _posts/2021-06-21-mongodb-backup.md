# Realizando Backup de dados do MongoDB


Neste primeiro post, irei apresentar uma dica rápida sobre realizar
backup e restauração no MongoDB.


Os passos abaixo devem ser realizados no terminal.
### Backup de um banco completo

``` console
mongodump --db <banco> --out <pasta>
```

### Como fazer backup de uma coleção especifica
``` console
mongodump --collection=<colecao> --db <banco> --out <pasta>
```
### Restaurar

``` console
mongorestore --db <db_nome> pasta
```
