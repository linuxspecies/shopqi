redis:  /opt/redis/redis-server
web:    bundle exec unicorn_rails -p 4000 -c config/development.unicorn.conf.rb
resque: QUEUE=* INTERVAL=1 bundle exec rake resque:work