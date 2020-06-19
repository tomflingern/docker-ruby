# docker-ruby

Base Repo for Ruby on Rails Application running on Docker

## Installation

Clone this project

Run `docker-compose run web rake db:create`

Run `docker-compose up`

Check in your browser if the application is running:
`http://localhost:3000/`

Note: Stop your application by running `docker-compose down`

## Technical notes

This application comes with
* Ruby 2.7.1
* Rails 5.2.4.3
* Postgres Database in an own Docker container
