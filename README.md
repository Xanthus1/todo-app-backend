# TodoApp NodeJS Backend

This project is the backend API using NodeJS/Express for a todo list application. It requires a MongoDB database to connect to, as well as a frontend for user interaction: https://github.com/Xanthus1/todo-app-react

This project was initially created following this tutorial, with some changes and new features: https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/.

## Demo

https://xanthus-todo-react.herokuapp.com/

## Installation / Configuration

Clone this repository:

`$ git clone https://github.com/Xanthus/todo-app-backend`

Create a file with the name ".env" in the root directory, and use the example below to define the MongoDB URI. 

`DB_STRING=MONGO_DB_URI_HERE`

You can also define the Port #. The application defaults to using 4000 if this isn't defined: 

`PORT=4000`

## Deployment

To run server:

`$ npm run start`
