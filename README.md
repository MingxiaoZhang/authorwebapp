## Author info API implemented with Node.js and Express.

### How to Run:

``` 
npm install

npm start
 ```

### API endpoints:

GET: Returns the JSON data for all stored authors in the database

POST: Stores author info into MongoDB and returns response in JSON data

GET/{id}: Returns the JSON data for the author with the given unique id

POST/{id}: Add works to the author of given id

PUT: Updates author information based on new data

DELETE: Removes author information from database



## Web Application: The web applciation is implemented with React.

### How To Run:

```
npm install

npm start
```

### Usage: 
There are three pages in the application: Home, PublicAPI, and FormAPI. 

PublicAPI: provides the interface for querying the public Authors API at https://openlibrary.org/search/authors.json 

FormAPI: provides the interface for querying the API developed in this project. To use it, run the API project first before running the web application.
