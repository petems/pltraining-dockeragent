#This file is generated by ModuleSync, do not edit.

source ENV['GEM_SOURCE'] || "https://rubygems.org"

def location_for(place, version = nil)
  if place =~ /^(git[:@][^#]*)#(.*)/
    [version, { :git => $1, :branch => $2, :require => false}].compact
  elsif place =~ /^file:\/\/(.*)/
    ['>= 0', { :path => File.expand_path($1), :require => false}]
  else
    [place, version, { :require => false}].compact
  end
end

gem 'facter', *location_for(ENV['FACTER_GEM_VERSION'])
gem 'puppet', *location_for(ENV['PUPPET_GEM_VERSION'])
gem 'puppetlabs_spec_helper',    :require => false

gem 'rake'