### What is this?

Todo list - following the meteor + react tutorial

### To run the application:

`$ meteor npm install`

// you might have to add packages for the db, cmd to do this is:

// `$ meteor add react-meteor-data`

`$ meteor`

### Seeding

The database is empty by default

You can add tasks from the browser window or from the cmd line.

To add a new element into the database from the cmd line:

`$ meteor mongo`

`> db.tasks.insert({ text: "Hello world!", createdAt: new Date() });`
