web: env bin/rails server -p ${PORT:-3000}
worker: bin/rake solid_queue:start
release: bin/rails db:prepare
