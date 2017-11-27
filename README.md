# Init

```
$ git clone https://github.com/tiwuofficial/ruby-on-rails-and-docker.git
$ cd ruby-on-rails-and-docker
$ docker-compose build
$ docker-compose run web rake db:create
$ docker-compose up -d
```

# DB

```
$ docker-compose run web rake db:create

```

# Error

```
# server.pidにより起動できない場合
$ docker-compose run web rm /myapp/tmp/pids/server.pid
```