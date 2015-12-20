# encoding: utf-8

source 'https://rubygems.org'

gemspec

gem 'parser', '2.3.0.pre.6' # WORK-AROUND for Ruby 2.2.4

group :test do
  gem 'coveralls', require: false
end

local_gemfile = 'Gemfile.local'

if File.exist?(local_gemfile)
  eval(File.read(local_gemfile)) # rubocop:disable Lint/Eval
end
