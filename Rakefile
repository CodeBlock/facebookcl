require 'rubygems'
require 'rake'

task :default do; end

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "facebookcl"
    gem.summary = %Q{Facebook Command Line}
    gem.description = %Q{Facebook Command Line Long Description}
    gem.email = "jubishop@facebook.com"
    gem.homepage = "http://github.com/jubishop/facebookcl"
    gem.authors = ["Justin Bishop"]
    gem.executables = ['facebook']
    gem.post_install_message = <<MESSAGE

===========================================================

           Thanks for installing FacebookCL!
           Just run 'facebook' to start.

===========================================================

MESSAGE
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available."
  puts "Install it with: gem install jeweler"
end