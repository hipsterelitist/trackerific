require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "trackerific"
  gem.homepage = "http://github.com/travishaynes/trackerific"
  gem.license = "MIT"
  gem.summary = %Q{Trackerific provides package tracking to Rails.}
  gem.description = %Q{Trackerific provides USPS, FedEx and UPS package tracking to Rails.}
  gem.email = "travis.j.haynes@gmail.com"
  gem.authors = ["Travis Haynes"]
end
Jeweler::RubygemsDotOrgTasks.new
