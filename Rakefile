require 'rspec/core/rake_task'

Dir.mkdir("spec", 0755) if Dir["spec"].empty?

RSpec::Core::RakeTask.new(:spec)

task :default => :spec
