# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require_relative 'config/application'

require 'ci/reporter/rake/rspec'

# ...
# Rake code that creates a task called `:rspec`
# ...

task :rspec => 'ci:setup:rspec'

Rails.application.load_tasks
