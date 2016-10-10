## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
  `GET = reads data, Post = creates, PUT = update/replace, PATCH = update/modify, DELETE = delete`
  
2. What is Sinatra?
  `Sinatra is a web development framework`
4. What is MVC?
  `model, view, controller.  A file artchitecture that seperates responsabilities the model deals with the database, the controller interacts with the client and the database, and the view is what is delivered to the client`
5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
`because Sinatra requires us to follow these conventions in order to create relationships and direct the flow of data`

6. What types of variables are accessible in our view templates without explicitly passing them?
`instance variables`

7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    @count = 1
    erb :index, :locals => {:name => "Mr. Ed"}
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed`?
`see above`
9. What's the purpose of ERB?
  `to embed ruby code within HTML`
10. Why do I need a development AND test database?
`Otherwise when we run our tests they would modify our production database`
11. What's responsive design?
`?`
12. What is CRUD and why is it important?
`Create, Read, Update, Destroy.  They are the four basic commands when dealing with a database`
13. What does HTTP stand for? 
`hyper text transfer protocol`

14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
`<%= THIS IS VISIBLE TO THE USER %>  <% THIS IS NOT %>`
15. What's an ORM?
`Object relationship manager`
16. What's the most commonly used ORM?
`ActiveRecord`
17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.

18. What's a migration? 
`the structure of the database which allows us others to recreat the database`
19. When you create a migration, does it automatically modify your database?
`no you have to run additional commands from the command line`
20. How does a model relate to a database?
`the model is related to an individual table within the database`

