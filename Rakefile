require 'rake'
require 'hanami/rake_tasks'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.pattern = 'spec/**/*_spec.rb'
  t.libs    << 'spec'
  t.warning = true
  t.verbose = true
end

task default: :test
task spec: :test
