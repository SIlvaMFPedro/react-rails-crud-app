# Creating a Simple CRUD App with Rails and React

This is the code repository to accompany a tutorial on how to create a Rails API then, using the Webpacker gem, build a React front-end to consume it.

Code based on this tutorial URL: [https://hibbard.eu/rails-react-crud-app/](https://hibbard.eu/rails-react-crud-app/)

## Requirements

- [Ruby](https://www.ruby-lang.org/en/downloads/)
- [Node.js](http://nodejs.org/)

There are instructions for installing both Ruby and Node at the beginning of the tutorial.

## Installation

- Clone repo
- Run `bundle install`
- Run `yarn install`
- Run `rake db:create`, `rake db:migrate`, then `rake db:seed`

## Running

- Start the Rails server with `rails s`
- In a second terminal start the bepback-dev-server with `./bin/server`
- Hit http://localhost:3000/events/


