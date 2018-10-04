# require "bundler/gem_tasks"

# task :default => [:convert]

desc 'Convert semantic-ui less to sass'
task :convert, :branch do |t, args|
  require './tasks/converter'
  branch = args[:branch]
  Converter.new(branch).process
  puts "Converting Sematic UI #{branch} Less file to Sass..."
end
