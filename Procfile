web: bin/rails s
release: bundle config set --local path $VIRTUAL_ENV; [ ! -f 'db/production.sqlite3' ] && bin/rails db:setup; bin/rails db:migrate; bin/rails assets:precompile
