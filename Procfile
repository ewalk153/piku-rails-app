web: bin/rails s
release: gem install --user-install bundler && bundle config path vendor; bundle; bin/rails db:setup; bin/rails db:migrate; bin/rails assets:precompile
