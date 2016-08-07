# Hosting Ruby on Rails application in Heroku

a. What components OTHER than your client and server framework did you install?

    I had to install heroku:heroku toolbelt, package dependencies for ruby and rails ,
    rvm for setting ruby version,gem,bundler etc.
  
b. What Linux(Ubuntu) commands are required to deploy and run your server? 
# Uploading code to github:

     $ git init
     $ echo "# Basic-Ruby-on-Rails-app" >> README.md
     $ git add README.md
     $ git commit -m "first commit"
     $ git remote add origin https://github.com/yogavignesh/Basic-Ruby-on-Rails-app.git
     $ git push -u origin master 
     
    to update
     $ git remote add origin https://github.com/yogavignesh/Basic-Ruby-on-Rails-app.git
     $ git push
    
    

# Getting code from github:

       $ heroku Login
       $ git clone https://github.com/yogavignesh/Basic-Ruby-on-Rails-app.git
       $ cd Basic-Ruby-on-Rails-app
       $ heroku create basic-app-ruby-on-rails
       $ git push heroku master
       $ heroku open
       
### The link to the running heroku app

      https://basic-app-ruby-on-rails.herokuapp.com/
        
### References

        http://www.sitepoint.com/use-google-maps-rails/
        http://heroku.com
        http://guides.rubyonrails.org/getting_started.html
        http://www.w3schools.com/
        http://jquery.com/
        http://stackoverflow.com/
        
