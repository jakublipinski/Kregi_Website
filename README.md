# Kregi_Website

# brew install ruby
# sudo gem install bundler -v 3.2.3
# bundle install

export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
bundle config set --local path 'vendor/bundle' 
bundle exec jekyll serve --livereload