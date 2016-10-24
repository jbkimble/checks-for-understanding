## Week Three Recap

### Instructions
Fork this repository. Be sure to pull the latest changes to your local repo. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

1. What is the entry at the command line to create a new rails app?
`rails new SomeName`
2. What do Models generally inherit from in rails?
  `ActiveRecord::Base`
3. What do Controllers generally inherit from in a rails project?
  `ApplicationController`
4. How would I create a route if I wanted to see a specific horse in my routes file assuming I'm sticking to standard conventions and that I didn't want other CRUD functionality?
  `resources :horses, only: [:show]`

5. What rake task is useful when looking at routes, and what information does it give you?
  `'rake routes', it shows you all of the routes in your application and which pages they route to and the name of the route helper` 
6. What is an example of a route helper? When would you use them?
`company_path(@company) you use them in your controllers and views to create links and direct users to specific show pages`
7. What's the difference between what `_url` and `_path` return when combined with a routes prefix?
`_url returns the absolute path.  _path returns the relative path`
8. What are strong params and why are the necessary?
`strong params increase the security of your application by ensuring that only the parameters you expect are able to be sent to your program.`
9. What role does `form_for` play in helping us create our forms?
  `form_for is method we call which creates our forms for us`
10. How does `form_for` know where to submit the user's input?
  `we pass it the objects we wish it to edit`
11. Create a form using a `form_for` helper to create a new `Horse`. 
``` 
  <%= form_for @horse do |f| %>
  <%= f.label "name" %>
  <%= f.text_field "name"%>
  <%= f.submit %>
```
12. Why do we want to validate our models?
`to ensure that we are not getting lots of objects with empty attributes inserted into out database?`
