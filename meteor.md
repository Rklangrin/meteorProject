# Meteor

### Collections
- Data Layer is stored in MongoDB
- MongoDB can be accessed through collections

Create new collection: 

**Server**
```
Todos = new Mongo.Collection('todos');
```

**Client**
```$xslt
Todos = new Mongo.Collection('todos');
```
