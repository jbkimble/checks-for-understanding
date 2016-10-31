## Week Four Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

* What is a cookie?
`a cookie is data stored in browser`

* What’s the difference between a session and a cookie?
`a session stores data more temporarily and is cleared when the browser is closed`
* What’s a flash and when do you want to use flashes?
`a flash is a message to the user that pops up the screen when they perform some action.  They are helpful to confirm to the user that their desired action has actually taken place`
* Why do people say “HTTP is stateless”?
`because HTTP requests do not persist, they are sent and recieved and each one is independent of the others and is not saved`
* What’s authentication? Explain.
`authentication is proving the user of the website is a certain person.  Such as when a user or admin logs into a website`
* What’s the difference between authentication and authorization?
 `Authorization is the process of determining which users are allowed to see which parts of the website and restricting other users from seeing those parts`
* What’s a before filter?
`a before filter is a method that is run before all the other methods into a controller, it must evaluate to true in order for the action to continue`
* How do we keep track of a user once they’ve logged in?
 `We set the session key 'user' to equal a user ID which confirms that the user is logged in` 
* When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
`You namespace a resource when you want a set of routes that are only accessible to a specific user.  We nest routes when we want routes that are related to one another (i.e. cats/1/toys/2)`
* At a high level, what tools can you use to implement authorization? How would you use them?
`You use forms and a database to store a username and passoword, you then use the user_id created by the database to render paths and pages which relate to that users information`
* What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
`An enum gives us methods to easily establish a specific users role, there needs to be a 'role' column in the users table.  You declare an enum in the users model?` 
* What are some strategies you can use to keep your views DRY?
`Extract methods and functions to the model and use partials`
