namespace :greeting do
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

desc 'outputs hola to the terminal'
  task :hola do 
    puts "hola de Rake!"
  end
end

task :console do
  puts "hello"
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
end