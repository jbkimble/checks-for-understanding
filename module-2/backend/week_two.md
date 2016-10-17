## Week Two - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON - YOU are a web developer!!!). 

Note: When you're done, submit a PR. 

1. At a high level, what is ActiveRecord? What does it do/allow you to do?
  `ActiveRecord is a object relationship manager which allows you to create relational databases with built in functions you' can call on them.`
  
2. What is a migration?
  `A migration is the structure of the database which allows you to add and edit tables and ultimately allows that entire database to be recreated`
  
3. How does a table relate to a model?
  `A model communicates with the table in a database, the model contains methods which can be called on the database and allows us to draw relationships between tables`
  
4. What kind of methods are `belongs_to`, and `has_many`? (i.e. class or instance) Give an example.
  `They are class methods, they are called on the class and not on instances of the class`
  
5. What do they allow you to do?
  'They allow you to draw relationships between different tables.  For example populating a house table with id's which point to a table which contains each individual room'
  
6. What's the difference between agile workflow and waterfall method?
  `Agile is an itterative process which combines the planning and execution phases and emphasizes completeing small steps, testing, and revision.  While waterfall seperates planning and executing into two distinct phases.`
  
7. What is the difference between `#new` and `#create`?
 `new creates a new active record object representing a row in a table but does now actually save it to the table.  Create combines the .new and .save methods`
 
8. At a basic level, what does cURL allow you to do?
  `send data to the internet`
9. In a database that's holding students and teachers, what will be the relationship between students and teachers? Draw the schema diagram.
 `many to many`
10. Define foreign key, primary key, and schema.
`foriegn key = a key in a table which points to a row on another table.  Primary key = a key which points to a row in a table.  schema = a file that creates your database`

11. Describe the relationship between a foreign key on one table and a primary key on another table.
  `the foriegn key in one table points to the primary key of a another table (identifying the row it points to`
12. What are the parts of an HTTP response?
  `the status of the http resonse, a time/date stamp, information about the server'
  
13. `Rack::Test` allows us to test our controllers in isolation. What are some of the methods it gives us to simulate the request/response cycle?
  ``

14. Describe some techniques to make our Sinatra views more DRY. Give an example of when you would use these techniques.
  'You can use a layout template to apply styling and insert elemnts into all of your pages'
### Optional Questions

1. Name your five favorite ActiveRecord methods (i.e. methods your models inherit from ActiveRecord) and describe what they do.
2. Name your three favorite ActiveRecord rake tasks and describe what they do.
3. What's the difference between agile workflow and waterfall method?
4. What can you expect from a group as you begin working together? As you continue working together?
5. What two columns does `t.timestamps null: false` create in our database?
6. What cURL flag can you use to send a `POST` request?
7. What case does JSON (and JavaScript) use for multi-word variables?
8. What case does Ruby use for multi-word variables?
9. In a database that's holding schools and teachers, what will be the relationship between schools and teachers?
10. In the same database, what will you need to do to create this relationship (draw a schema diagram)?
11. Give an example of when you might want to store information besides ids on a join table.
12. Describe and diagram the relationship between patients and doctors.
13. Describe and diagram the relationship between museums and original_paintings.
14. What are some examples of acceptable values for the parts of an HTTP response?
15. What types of output do we want to test when we test our controllers?
16. What could you see in your code that would make you think you might want to create a partial?
17. Why might you use a helper method?
