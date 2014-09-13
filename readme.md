WGG 8/17/2014

tutorial from: http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/

this uri is showing json output of the db http://localhost:3000/users/userlist
stopped at: Got it? Cool. Save that file and let's hit our browser and take a look. 

Mongo DB WG 9/12/2014

was getting error: "Failed to connect to 127.0.0.1:27017, reason: errno:61 Connection refused"

to fix i ran: brew services start mongodb

then: mongod --dbpath /Users/wes/node_projects/nodetest2/data

then: mongo

then: use nodetest2