# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

git_source(:github) do |repo_name| "https://github.com/#{repo_name}" end

unless ENV['CI']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 1.3', require: false,
                              git: 'https://github.com/hanami/utils.git',
                              branch: 'master'

gem 'ossy', github: 'solnic/ossy', branch: 'master', platform: :mri
