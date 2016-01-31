#!/usr/bin/env ruby
# coment 
require 'rake/testtask'
require 'rubygems'
require 'rake'
#require 'haml'

task default: :ring

task :ring do
  puts "Bell is ringing."
end
 
task :enter do
  puts "Entering home!"
end

task :test do 
  Rake::TestTask.new do |t|
    t.test_files = FileList['test/jenkins_sample_test.rb']
  end
end
