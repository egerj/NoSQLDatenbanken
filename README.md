# NoSQLDatenbanken
Präsentation Software Engineering I

MongoDB mit Docker einrichten (über Konsole):
  1. docker pull mongo
  2. docker run --name mongo -d mongo mongod
  3. docker exec -it mongo bash
  4. mongo

MongoDB Collection Methods (https://docs.mongodb.com/manual/reference/method/js-collection/)
- use dbName
- db.Collection.insert()
- db.Collection.remove()
- db.Collection.update()
- db.Collection.find().pretty()
- db.Collection.find().sort().pretty()
- db.Collection.find().Count()
