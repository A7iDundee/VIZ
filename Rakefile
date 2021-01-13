#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

lib = File.expand_path("../../config/application", __FILE__)
$LOAD_PATH.unshift(lib) unless $LOAD_PATH.include?(lib)

begin
  require "Application/gem_tasks"
rescue LoadError
end
