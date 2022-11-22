## To-Do list

This application is built using Embedded JavaScript (EJS) and Mongoose, a framework of MongoDB.
You can use this applicaiton to create short to-do lists for different occacions such as, _Grocery Shopping_, _Work_, _Gym_.

# Features

Utilises all the CRUD operations
You can create a new list, by adding `/{yourChosenTitle}` at the end of the url.
This will redirect the user to a new to-do list page.

- Can view lists that are saved in the database such as, `/work`.
- Update the current list by adding new items to the specific list
- Delete an item from the list by clicking on the checkmark provided next to it.

To run this application online in localhost:

In the macOS terminal, run:

- `mongod` then
- `brew services start mongodb-community@6.0` to start running the `mongod` service, then
- `mongosh` to connect and use MongoDB
  or
- `brew services stop mongodb-community@6.0` to stop running `mongod` service
