# Flixter Web Application

[Flixter](http://flixter-abdullah-alam.herokuapp.com): A two sided video streaming marketplace, featuring credit card payment capabilities, user role management, advanced UI & UX, and advanced database relationships.

This app powers Flixter located [here](http://flixter-abdullah-alam.herokuapp.com)


## Getting Started

## Software requirements

- Rails 5.0.0 or higher

- Ruby 2.3.1 or higher

- PostgreSQL 9.5.x or higher

## Navigate to the Rails application

```
$ cd /path/to/rails/application
```

## Set configuration files

```
$ cp config/database.yml.template config/database.yml
$ cp config/application.yml.template config/application.yml
$ cp config/initializers/carrierwave.rb.template config/initializers/carrierwave.rb
$ cp config/initializers/stripe.rb.template config/initializers/stripe.rb
```

Note:  You may need to edit the above files as necessary for your system.

## Create the database

 ```
 $ pgstart
 $ rake db:create
 ```

## Migrating and seeding the database

```
$ rake db:migrate
$ rake db:seed
```

## Starting the local server

```
$ rails server

   or

$ rails s
```

## Production Deployment

  ```
  $ git push heroku master
  $ heroku run rake db:migrate
  ```

## Support

Bug reports and feature requests can be filed with the rest for the Ruby on Rails project here:

* [File Bug Reports and Features](https://github.com/abdullahalam/flixter/issues)

## License

Flixter is released under the [MIT license](https://mit-license.org).

## Copyright

&copy; Copyright 2017 Abdullah Alam. All Rights Reserved.