# Jersey-Jetty-MongoDB

to start mongodb
mongod --port 27017 --dbpath /data/db

in an separate tab type
mongo --port 27017 -u "someadmin" -p "secret" --authenticationDatabase "admin"
db.createUser({user:"someadmin",pwd:"secret", roles:[{role:"root",db:"admin"}]})
(In some order check)

use {dbName} - to create a new database
show dbs -  to show all dbs

after you hit use {dbName}, feel free to use the below commands

- db.{collectionName}.insert({documents},{[array of documents]}) etc
- db.{collectionName}.find()
- go inside any database and hit db.dropDatabase() to delete that particular db.
