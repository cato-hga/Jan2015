# Half Way Challenge

1. What is a class?

A class would be the DNA or the blueprint of an object. An example would be that a bicycle would be an object of the class bicycles.



2. What is an attribute?

An attribute makes an object descriptive. If we had an object named bicycle I believe an attribute of that object could be wheels or color.





3. What is an object?

An instance of a class. If there a class of bicycles then a bicycle would be the object.



4. What type of object is a PORO?

Plan Ole Ruby Object.



5. What is a Rails model?

 A Rails model stores and validates data. It does all of the validation before it hits the database.



6. What is your absolute favorite meal?

Either Pad Thai or Lasagna.



7. What is the difference between a locally scoped variable and an instance variable?

A locally scoped variable can only be used with that specific block of code where as an instance variable can be used throughout the whole application



8. Why do we use version control like git?

To keep tabs on our latest versions of applications we create



9. What is the difference between git and GitHub?

Git deals with our code history. Github is somewhat of a hosting service for our Git folders



10. What is your ideal vacation?

Relaxing somewhere in Jamaica by the beaches or hiking somewhere in the Smokey Mountains



11. What does the pattern of Separation of Concerns mean and why do we use it?
It's a computer science term that deals with organizing and separating a program into different sections. It allows the overall flow of an application to run smoother and more efficient.



12. What does the pattern MVC mean?

Model View and Controller.



13. What is the difference between a Rails model and a database table? What is their relationship?

A Rails model is similiar to a blueprint and database table is similiar to the actual product. You can't have a database table without the Rails model.



14. How do we modify the database for our Rails app?

Using migrations. and example of that would be "Rails generate model Product name:string"



15. What do you do to relax?
Listen to music.



16. What is a gem and how do we use them in our Rails apps?
A gem is like a plug-in for a Rails application that gives you different functionality. To install a gem you would add the gem to the Gemfile file and bundle install it in the terminal.



17. In what part of a Rails application do we tell it how to handle an HTTP request to a specific path, like: `http://localhost:3000/movies`?

Routes.rb



18. In what part of a Rails application do we hold data provided by the user, in order to use it, save it to the database, or retrieve it from the database?

Model



19. In what part of a Rails application do we render data, in HTML, to present to the user?

View



20. What TV show do you never want to miss?

Bizarre Foods and Criminal Minds.



21. What part of a Rails application processes actions, uses models, and directs flow to the proper view?

Controller



22. If your app gave you the following error message, on this line of code, what would it indicate?


        undefined method `downcase' for nil:NilClass


        <%= user.name.downcase %>


Maybe the user's name isn't defined.



23. What gem did we use to paginate our Collections?
 kaminari gem



24. What gem did we use to provide upload functionality?

The Carrierwave gem.



25. What is your favorite musical artist or group?
John Mayer, Eshon Burgundy, and KB.


26. What technology do we use to style HTML in the browser?
CSS(Cascade Style Sheets)



27. What type of view templates have we been using in our class to create dynamic HTML?
.ERB



28. What type of helpers do we use to check data against certain rules and requirements before it is saved to our database?

Validators



29. What are model associations?
Allows to link and show the connections between different models.



30. Based on the name, if The Iron Yard wasn't a code school, what else might it be?

Perhaps a mechanical engineering school.



31. What code would you use to find the a User record in the database with an id of 17?
User.find17


32. If you want to use an image inside your app, in what directory do you put it?

The images folder in assets



33. What helper do you use to create a form to edit or create a specific resource?

form helper



34. What does this mean? `||=`

Memoization. Only set it if it's not already set.



35. What is your nickname? If you don't have one, what do you wish it was?
My name last name(Cato).


36. What is a scope? Please provide one example.

A scope allows you to gather information based on certain conditions you require.

class User < ActiveRecord::Base
  scope :newsletter, where(subscribed_to_newsletter: true)
end

User.newsletter would give you users who have subscribed to your newsletter.


37. What is _rake_? Give some examples of how and when we use it?

Allows you to run your ruby code in rails.

Rake db:seed will allow you to run your seed data. Rake db:migrate will allow you to migrate the latest change to your database.



38. How do you deploy your app to Heroku?
 git push heroku master



39. What gem can we use to provide a fast, yet custom and robust, administrative section for our apps?
 active admin gem



40. What is does _anopisthographic_ mean?

 Having writing or printing on one side only?



41. If a User has many ParkingTickets, and the `user` variable points to a User object, what code would you use to get all the ParkingTickets?

user.ParkingTickets.all


42. If an Address model has a postal code attribute, what code would you use to get all Addresses from the database with a postal code of _33771_?

address.where(postalcode: 33771)



43. How do you create a new Book object in the database, if a Book class has the following required attributes: title, author, publish_year, pages?

b = Book.new
b.title.author.publish_year.pages


44. If we get this message in our log after attempting to save an object, what does it mean?

              Unpermitted parameters: first_name

 Never trust parameters from the scary internet, only allow the white list through. White list does not include first_name


45. What one question do you wish I would have asked?

    What is it about this class that intimidates you the most?
