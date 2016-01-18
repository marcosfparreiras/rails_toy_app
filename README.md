# Ruby on Rails Tutorial: A toy app

This is the second application for the
[*Ruby on Rails Tutorial*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

This is a simple Ruby on Rails application that manages users and microposts.

In order to make it run, clone this repo by typing
```
$ git clone https://github.com/marcosfparreiras/rails_toy_app.git
```
Then, in the terminal type
```
$ cd /path/to/repo
$ rails server
```
Thus just open your favorite browser and access http://localhost:3000 and you'll see the Users page. From it, you can add new users, list them, update and delete. The users page can also be accessed through the path http://localhost:3000/users.

Accessing the path http://localhost:3000/microposts on your browser, you can manage microposts, that have a simple validation, so they can't be bigger then 140 characters.
