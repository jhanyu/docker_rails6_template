# README

## Setup
1. Git clone
   ```sh
   $ git clone git@github.com:jhanyu/docker_rails6_template.git
   ```

1. Build docker image
   ```sh
   $ cd docker_rails6_template
   $ docker-compose build
   ```

## Boot the app
1. Boot docker
   ```sh
   $ docker-compose up
   ```

1. Create database  
   :warning: It takes time to start the database, so please wait for a while before executing.
   ```sh
   $ docker-compose exec web rake db:create
   ```

## Stop the app
1. Cleanup docker
   ```sh
   $ docker-compose down
   ```
