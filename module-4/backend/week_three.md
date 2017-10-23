## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
  
  Node is a runtime environment that lets you write javascript server-side applications

2. What is Express? What is Express similar to in the Ruby world?

  Express is a unopinionated framework hosted within a Node environment. It makes it less painful to write server side code by providing methods like .get and .post.
  
3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

  app.get('/api/v1/foods', Foods.getFoods())
  
4. What do we use Knex for?

  Knex lets you build queries using simple syntax instead of writing raw sql.
  
5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?

  You can separate your code into specific files so it follows MVC. For example, store all routes in the server.js, make a controller folder and store functions that deal with request and response in a file in that folder, and create a models folder and store functions that deal with sql queries in a file in that folder, and views will be in a separate front-end app.
  
6. How do you execute raw SQL in node?

  database.raw("sql query")
  
7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

  Advantages of having a front end and backend application is that the code is more organized adn follows MVC conventions. A disadvantage would be that the front end is dependent upon the backend so if the backend server goes down then the front end wont be able to access the information.

#### Review  

8. Describe DNS.

  Domain Name Server is used to convert IP addresses into a user friendly, easy to read, string.
  
9. What does writing clean code mean to you?

  Writing clean code is to have well factored, organized code. Extracting low level logic and keeping the high level logic up top. It also means to keep functions short and having descriptive variable names and functions.
  
10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?

  I would need a reservations class which would be responsible for keeping track of room reservations, a check-in/ check-out class that would be used to check-in/ check-out guests, a payments class that would hold deposits and charge guests for the room.
