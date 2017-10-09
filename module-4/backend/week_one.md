## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
  
  -Most important thing is learning how to test javascript with mocha and chai.
  
2. What are some tools to help debug JavaScript code?

  PryJS, Chrome Console, debugger, console.log
  
3. What are some tools you need in order to unit test your JavaScript?

  Mocha and Chai
  
4. What is the syntax for invoking a function?

  functionName(parameter);
  
5. What's `this` in JavaScript?

  this refers to the function in which is was invoked. 
  
6. What is Webpack and why is it useful?

   A webpack collects all of your assets and dependencies, compiles it and creates a bundled js file from it.
   
7. When/why do you want to use event delegation?

  Event Delagation lets you handle a node event that does not exist yet by setting an event listener onto the parent.
  You want to use it when you have an element that does not appear on page when loaded but has an event that can be   triggered. You set the listener to the parent and bubbling will find the child when it appears.
  
8. What's `npm` and what do we use it for?

  It's used to install packages and dependencies to your project. It creates the package.json.

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.
  
  1. Based on the request, the controller asks the model for information.
  2. The model connects with the database, parses the information, and gives it to the controller
  3. The controller gives that information to the view and the view handles how to display it.
  
10. What are a few ways to optimize a Rails application?
  
  Using serializers to filter only the information you want to display, Presenters to make sure you only have one instance in the view, and loading a webpage section by section instead of trying to load everything at once.

11. What's a background worker? When would we want to use a background worker?
  
  A background worker gets sent off to do tasks while the system keeps running. For example, when a customer buys an item off amazon, when they click 'Buy', the background worker sends the information to the queue, but the page loads to say order is complete even if the order has not yet been paid for. In doing this, the customer does not have to wait for the long process of transaction.

