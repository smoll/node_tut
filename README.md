node_tut
========

Following http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/

### Start db
```
$ mongod --dbpath ./data
```

### View db entries with mongo console
```
$ mongo
$ db.usercollection.find().pretty()
```

### Start node server
```
$ npm start
```

### View site
In a browser, go to: http://localhost:3000

View users: http://localhost:3000/userlist

Add new user: http://localhost:3000/newuser
