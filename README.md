# Hn

A tiny gem to fetch Hacker News entries

[![Build Status](https://secure.travis-ci.org/forresty/hn.png?branch=master)](http://travis-ci.org/forresty/hn)

![hn gem](http://forresty.com/images/hn.png)

## Installation

Add this line to your application's Gemfile:

    gem 'hn'

And then execute:

    $ bundle

## Issues

Recently, Hacker News has started enforcing HTTPS connections. If you're having
problems accessing Hacker News via this gem, read [these
instructions](http://railsapps.github.com/openssl-certificate-verify-failed.html)
for specific fixes.

## Usage

    require 'hn'

    # return up to 30 homepage entries
    HackerNews::Engine.homepage

    # return up to 30 best entries
    HackerNews::Engine.best

    # return up to 30 newest entries
    HackerNews::Engine.newest

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Contributors

Thanks following wonderful people for contributing to this project:

[@bencevans](https://github.com/bencevans)
[@imkmf](https://github.com/imkmf)
