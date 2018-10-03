#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com";

mod 'alisio-confsbase'
mod 'alisio-memcached'
mod 'alisio-mysqlserver'

mod 'puppet-webserver',
  :git => 'https://github.com/alisio/puppet-webserver.git',
  :branch => 'production'

mod 'puppet-balancer',
  :git => 'https://github.com/alisio/puppet-balancer.git',
  :branch => 'production'
