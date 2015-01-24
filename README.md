# Consuming APIs

## Topics
* What is an API?
* ``curl``
* Code Along with ``HTTParty``
* Testing API calls

## ``curl``
```
curl -v https://api.github.com/emojis
```

## Code Along

* [``app.rb``](app.rb)
* Spec - Use Case
  *  User can visit ``/`` to see a list of github emojis
* [Read the API docs](https://developer.github.com/v3/emojis/)

## Optional: Testing code which uses APIs

## Summary
* API is an interface for Applications to use
  * JSON
  * HTTP GET,POST,etc.
  * RESTful routing
* Tools to poke at APIs
  * ``curl`` - command line
  * [Postman REST Client](http://bit.ly/stujo_postman) - chrome
* Using APIs in your Applications
  * HTTParty in ``ruby`` apps
* Testing API calls
  * Stubbing API calls
  * [thoughtbot - how-to-stub-external-services-in-tests](http://robots.thoughtbot.com/how-to-stub-external-services-in-tests)
  * ``gem 'webmock'``
  * ``require 'webmock/rspec'``

