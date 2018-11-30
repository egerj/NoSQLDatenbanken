# NoSQLDatenbanken
Präsentation Software Engineering I

### MongoDB mit Docker einrichten (über Konsole):
  1. docker pull mongo
  2. docker run --name mongo -d mongo mongod
  3. docker exec -it mongo bash
  4. mongo

Hinweis: Bei Git Bash muss "winpty" vor den "docker exec" Befehl gesetzt werden.

### MongoDB Collection Methods (https://docs.mongodb.com/manual/reference/method/js-collection/)
- use `<dbName>`
- db.`<collectionName>`.insert()
- db.`<collectionName>`.remove()
- db.`<collectionName>`.update()
- db.`<collectionName>`.find().pretty()
- db.`<collectionName>`.find().sort().pretty()
- db.`<collectionName>`.find().Count()
- show dbs (zeigt die angelegten Datenbanken an)
- show collections (zeigt die angelegten Collections in einer Datenbank an)
