# README

Credit goes to codewithjason.
https://www.codewithjason.com/dockerize-rails-application/

# Steps:
1.  docker-compose build
2.  docker-compose up
3.  docker-compose run web yarn install –check-files
4.  docker-compose run web rails db:create
5.  docker-compose run web rails db:migrate
