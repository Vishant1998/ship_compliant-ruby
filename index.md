---
layout: default
title: ShipCompliant - Ruby API Client
---

# ShipCompliant - Ruby API Client

The ShipCompliant gem is an API Client for the [SOAP][soap_wiki] API provided by
ShipCompliant. This gem has been created for fast implementation and supports
the 9 main API calls.

[Documentation][documentation_path] | [RDoc][rdoc_path] | [CoreService V1.2][core_service_path]

[![Coverage Status](https://coveralls.io/repos/BaylorRae/ship_compliant-ruby/badge.png?branch=master)](https://coveralls.io/r/BaylorRae/ship\_compliant-ruby?branch=master) [![Build Status](https://api.travis-ci.org/BaylorRae/ship_compliant-ruby.png?branch=master)](https://travis-ci.org/BaylorRae/ship\_compliant-ruby) [![Code Climate](https://codeclimate.com/github/BaylorRae/ship_compliant-ruby.png)](https://codeclimate.com/github/BaylorRae/ship_compliant-ruby)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ship_compliant'
```

And then execute:

```bash
$ bundle install
```

Finally, add this to `config/initializers/ship_compliant.rb`

```ruby
ShipCompliant.configure do |c|
  c.partner_key = ENV.fetch('SHIP_COMPLIANT_KEY')
  c.username = ENV.fetch('SHIP_COMPLIANT_USER')
  c.password = ENV.fetch('SHIP_COMPLIANT_PASS')
end
```

## Usage

TODO: Coming soon...

## Contributing

1. Fork it ( http://github.com/BaylorRae/ship_compliant-ruby/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

[soap_wiki]: http://en.wikipedia.org/wiki/SOAP
[documentation_path]: http://baylorrae.github.io/ship_compliant-ruby/documentation/
[rdoc_path]: http://baylorrae.github.io/ship_compliant-ruby/rdoc/
[core_service_path]: https://shipcompliant.desk.com/customer/portal/articles/1451976-api-coreservice-v1-2?b_id=2759