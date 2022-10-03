web: bin/rails s
release: [ ! -f 'db/production.sqlite3' ] && bin/rails db:setup; bin/rails db:migrate; bin/rails assets:precompile
