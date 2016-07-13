source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? ENV['PUPPET_VERSION'] : ['>= 3.5.1', '<=4.5.2']

group :rspec, :kitchen do
  gem 'librarian-puppet', '2.1.0'
  gem 'puppet', puppetversion
  gem 'rspec_junit_formatter'
  gem 'puppet-blacksmith'
end

group :rspec do
  gem 'puppetlabs_spec_helper', '>= 0.1.0'
  gem 'puppet-lint'
  gem 'facter', '>= 1.7.0'
  gem 'rspec-puppet'
  gem 'puppet-syntax'
end

group :kitchen do
  gem 'puppet_forge'
  gem 'test-kitchen'
  gem 'kitchen-puppet'
  gem 'kitchen-docker'
  gem 'kitchen-vagrant'
  gem 'vagrant-wrapper'
end

