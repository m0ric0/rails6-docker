# rails6-docker

- Ruby 3
- Rails 6
- Postgres

## Build the project

~~~
$ docker-compose run web rails new . --force --no-deps --database=postgresql --skip-bundle
~~~

### For API mode

~~~
$ docker-compose run web rails new . --force --no-deps --database=postgresql --skip-bundle --api
~~~
