source 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
    puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
    puppetversion = ['~> 2.7']
end

gem 'rspec-puppet'
gem 'rspec', '< 3.2.0'
gem 'puppet-lint'
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper'
