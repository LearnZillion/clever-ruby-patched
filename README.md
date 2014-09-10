# Clever::Ruby

[![Build Status](https://drone.ops.clever.com/github.com/Clever/clever-ruby/status.svg?branch=master)](https://drone.ops.clever.com/github.com/Clever/clever-ruby)

Ruby bindings to the Clever API.

## Installation

Add this line to your application's Gemfile:

```bash
gem 'clever-ruby'
```

And then execute:

```bash
$ bundle
```

Or install it yourself as:

```bash
$ gem install clever-ruby
```

## Run tests

To run all tests:

```bash
$ rake test
```

To run all tests and the linter ([rubocop](https://github.com/bbatsov/rubocop)):

```bash
$ rake
```

The linter follows the [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide) with a few exceptions. To just run the linter:

```bash
$ rake lint
```

Running specific tests is not currently supported.

## Usage

Configure clever-ruby to use your Clever API key:

```ruby
Clever.configure do |config|
  config.api_key = 'YOUR-API-KEY'
end
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git add -p ./path/to/files; git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
