Cakebox Builder
===============

The sources used to build the [Cakebox]("http://github.com/alt3/cakebox") Vagrant base box.

# Requires:

- Vagrant
- Chef-DK
- Berksfile
- Test-kitchen

# Provisions:

- Ubuntu 14.04 TLS
- PHP 5.6 (PPA)
- Git 2.x (PPA)
- Memcached
- Redis (PPA)
- Nginx (PPA)
- Percona MySQL
- PostgreSQL
- Curl
- Composer
- PHPUnit
- PHP CodeSniffer
- Heroku Toolbelt
- Ruby 1.9.3
- Cakebox customizations

# PHP Modules

See node.json for a full list of all installed PHP modules.

# Chef cookbooks

See Berksfile for a full list of all used cookbooks.

# Test-kitchen

	cd cakebox-builder
	kitchen create
	kitchen verify

# Contributing

1. Fork it ( https://github.com/alt3/cakebox-builder/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make sure test-kitchen and foodcritic tests pass
4. Commit your changes (`git commit -am 'Adds some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
