require 'bundler/gem_tasks'

task defalt: [:spec, :lint]

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new

task lint: [:rubocop]

require 'rubocop/rake_task'
RuboCop::RakeTask.new
