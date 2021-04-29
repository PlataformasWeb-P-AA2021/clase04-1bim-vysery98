# Clase 04 - CouchDB

* Para subir datos en formato JSON mediante línea de comandos a una base de datos CouchDB, se puede usar el siguiente comando.

```
curl -d @[nombre-archivo].json -H "Content-type: application/json" -X POST http://127.0.0.1:5984/[nombre de la base de datos]/_bulk_docs
```

Donde:
* [nombre-archivo], reemplazar por el nombre del archivo en formato JSON
* [nombre de la base de datos], reemplazar por el nombre de la base de datos creada previament en CouchDB


#### Repositorio creado con fines académicos.
