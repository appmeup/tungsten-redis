# Tungsten::Redis

Redis for Tungsten

## Installation

Add this line to your `application's Gemfile:`

```ruby
gem 'tungsten-redis'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install tungsten-redis

## Usage

Add this line to your `config/tungsten.rb`:

```ruby
require 'tungsten/redis'
```

Now you can include it in your roles:

```ruby
role :app do
  uses :redis
end
```

## Development

Fork and install all dependencies:

    $ bundle

Test the lib locally with *Vagrant* using the provided `Vagrantfile`:

    $ vagrant up

Start sending commands:

    $ tungsten start -C lib/tungsten/redis/test_config.rb

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/appmeup/tungsten-redis. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
