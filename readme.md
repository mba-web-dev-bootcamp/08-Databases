# Databases

## Intro to Databases
* What is a database?
    * A collection of information / database
    * Has an interface that you can write code against
* SQL(relational) vs. NoSQL(non-relational)


# Intro to MongoDB
* What is MongoDB
* Why are we using it?
* Let's Install It!
 

# Our First Mongo Commands
* mongod - starts mongo process (usually in a different term window)
* mongo - opens up the mongo shell (always in a different term win)
* help - basic help
* show dbs - shows database names
* use - use (or create) database "use demo"
* insert - db.dogs.insert({name: "Rusty", breed: "Mutt"})
* find - db.dogs.find() - db.dogs.find({breed: "Mutt"})
* update - db.dogs.update({name: "Rusty"}, {$set: {name: "Tater", isCute: true}})
* remove - db.dogs.remove({breed: "Labradoodle"})

dogs
name age breed


# Mongoose
* What is Mongoose?
* Why are we using it?
* Interact with a Mongo Database using Mongoose



