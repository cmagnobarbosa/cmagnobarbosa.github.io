# Realizando Backup MongoDB


Neste primeiro post, irei apresentar uma dica rápida sobre realizar backup e restauração no MongoDB.



### Backup de um banco completo

``` console
mongodump --db <banco> --out <pasta>

```

### Como fazer backup de uma colecao especifica
``` console
mongodump --collection=<colecao> --db <banco> --out <pasta>
```
### Restaurar

``` console
mongorestore --db <db_nome> pasta
```
