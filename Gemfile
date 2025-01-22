Encoding.default_external = Encoding::UTF_8
Encoding.default_internal = Encoding::UTF_8

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}" }

gem 'paneron-register', '~> 0.1.3'

# Allow local development overrides of gems:
begin
  eval_gemfile('Gemfile.devel')
rescue StandardError
  nil
end
