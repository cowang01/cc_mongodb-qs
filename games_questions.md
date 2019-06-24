### Questions

1. What is responsible for defining the routes of the `games` resource?
A.    server/helper/create_router.js   This contains functions that can direct items from and to the database.

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
A.   The client is responsible for storing all raw data in the database and sending or updating the raw data.  The client is responsible for display and what is to be seen or amended.

3. What are the the responsibilities of server.js?
A.   Notifing any errors, creating the url structure, initiating any functions to get or post data, connecting any database handling frameworks.

4. What are the responsibilities of the `gamesRouter`?
A.  Provides access to the various functions that operate on the database depending on what the client is looking to perform.

5. What process does the the client (front-end) use to communicate with the server?
A.  Fetch requests to hosted URL from the games service folder.

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
A.   Init object.  Used to tell the server side paramaters of the request.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
A.   get, post and delete.

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
A.  To communicate with the inbuilt database from server side javascript.
