web: jemalloc.sh bundle exec rails s -b 0.0.0.0 -p $PORT
postdeploy: bundle exec rails db:migrate
worker: jemalloc.sh bundle exec sidekiq
