# Five9 Web Service API

### This module has been depreciated, please do not use it. 

This is an API wrapper for [five9 - Cloud Contact Center Software](http://www.five9.com/). In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/five9_webapi`. To experiment with that code, run `bin/console` for an interactive prompt.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'five9_webapi'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install five9_webapi

## Usage

In order to use this you will have to have an active account with five9.

    five9 = Five9Gem::Connection.new("YOUR_USERNAME","YOUR_PASSWORD")

TODO: it will be completed once it's ready to publish.

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/mhadaily/five9_webapi. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

