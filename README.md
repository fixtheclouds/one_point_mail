# OnePointMail

Unofficial 1Point Interactive API wrapper 

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'one_point_mail'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install one_point_mail

## Usage

Obtain your API key from 1Point Interactive account. Then instantiate a client providing
that API key e..g.
```ruby
require 'one_point_mail'
client = OnePointMail::Client.new(api_key)
``` 

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
