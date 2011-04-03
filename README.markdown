# Ruby on Rails Tutorial: sample application

This is the sample application for [*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/) by [Michael Hartl](http://michaelhartl.com/).

## Testing

### Run spork

Spork is configured in `spec/spec_helper.rb`. To run, just type:

    $ spork

### Run autotest

Autotest is configured in the `autotest/discover.rb` file. To run:

    $ autotest

### Run tests

    $ rspec spec

## Heroku

Deploy to Heroku without test or development gems:

    $ heroku config:add BUNDLE_WITHOUT="development test"

## Parking Lot

### .autotest

Figure out how to add request specs to .autotest (there doesn't appear to be an .autotest file in my project directory). See chapter 5:

http://ruby.railstutorial.org/chapters/filling-in-the-layout