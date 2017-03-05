What is this?
Todo list - following the meteor + react tutorial

To run the application:
`$ meteor npm install`
// you might have to add packages for the db:
// $ meteor add react-meteor-data
`$ meteor`

The database is empty by default
To add a new element into the database:
`$ meteor mongo`
`> db.tasks.insert({ text: "Hello world!", createdAt: new Date() });`
