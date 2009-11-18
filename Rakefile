require 'rubygems'
require 'rake'

begin

  require 'jeweler'

  Jeweler::Tasks.new do |gemspec|

    gemspec.name        = "merb-pre"
    gemspec.description = "install this before you gem install merb --prerelease"
    gemspec.summary     = "Metagem that contains all the prerelease files for merb"

    gemspec.authors     = [ "The Merb Team" ]
    gemspec.email       = "team@merbivore.com"
    gemspec.homepage    = "http://merbivore.com/"
    
    # # Runtime dependencies
    gemspec.add_dependency "extlib", ">=  0.9.13"
    gemspec.add_dependency "erubis", ">=  2.6.2"
    gemspec.add_dependency "rake", ">= 0"
    gemspec.add_dependency "rack", ">= 0"
    gemspec.add_dependency "mime-types", ">= 1.16"
    gemspec.add_dependency "ruby2ruby", ">= 1.1.9"
    gemspec.add_dependency "ParseTree", ">= 2.1.1"
    gemspec.add_dependency "mailfactory", ">= 1.2.3"
    gemspec.add_dependency "templater", ">= 1.0.0"
    gemspec.add_dependency "haml", ">= 2.0.3"
    gemspec.add_dependency "dm-core", "~> 0.10"
    gemspec.add_dependency "dm-migrations", "~> 0.10"
    gemspec.add_dependency "do_sqlite3", "~> 0.10"
    gemspec.add_dependency "dm-timestamps", "~> 0.10"
    gemspec.add_dependency "dm-types", "~> 0.10"
    gemspec.add_dependency "dm-aggregates", "~> 0.10"
    gemspec.add_dependency "dm-validations", "~> 0.10"
    gemspec.add_dependency "dm-sweatshop", "~> 0.10"
    gemspec.add_dependency "dm-serializer", "~> 0.10"
    gemspec.add_dependency "dm-constraints", "~> 0.10"
    
    # Requirements
    gemspec.required_ruby_version = ">= 1.8.6"
  end

  Jeweler::GemcutterTasks.new

rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end
