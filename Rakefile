# -*- ruby -*-

require 'rubygems'
require 'hoe'
require './lib/thrift.rb'

Hoe.new('thrift', Thrift::VERSION) do |p|
  # p.rubyforge_name = 'thriftx' # if different than lowercase project name
  p.developer('Christopher Brown', 'cb@opscode.com')
end

task :cultivate do
  #system "touch Manifest.txt; rake check_manifest | grep -v \"(in \" | patch"
  system "rake debug_gem | grep -v \"(in \" > `basename \\`pwd\\``.gemspec"
end

# vim: syntax=Ruby
