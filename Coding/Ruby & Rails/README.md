# Ruby & Rails

Version management - especially since macOS installs its own (old) version.

Options:
* [rbenv]() - what I'm using
* [rvm]()

## Ruby

### Installing

An oldish version of Ruby is installed by default. To run Rails you need at least 2.5. Homebrew will install this "keg only" so Ruby will need to be added to your path.

Use rbenv.

Check active version of Ruby with ```rbenv version```, set with ```rbenv [global|local|shell] version-number```.

#### Upgrading

```sh
brew update         # make sure formulas are up to date
brew upgrade ruby
```

### Gems

[Ruby Gems](https://rubygems.org)

### IDEs

### Testing

#### Tools

##### Test Gems

**"Standard Kit:"**

* MiniTest (built-in)

**Commonly Used:**

* [Rspec](http://rspec.info)
* [Capybara]()
* [Factory Bot](https://github.com/thoughtbot/factory_bot) - test fixture generator
* Database Cleaner
* Simplecov
* VCR
* [Mutant (mbj/mutant)](https://github.com/mbj/mutant) - "mutates" your code and reruns your tests so that you can verify your test design and coverage. Works with Rspec and MiniTest.

"Odor detectors:"

* [Reek](https://github.com/troessner/reek)
* [SandiMeter](https://github.com/makaroni4/sandi_meter)

## [Bundler](https://bundler.io)

## [Rails](https://rubyonrails.org)

### Installing

### Starting A Project

### Databases

### Using Typescript

[typescript-ruby/typescript-rails](https://github.com/typescript-ruby/typescript-rails)

### Using Coffeescript

### Testing

* [15 TDD steps to create a Rails application](http://andrzejonsoftware.blogspot.com/2007/05/15-tdd-steps-to-create-rails.html)
* [How to waste time on TDD](http://andrzejonsoftware.blogspot.com/2012/06/how-to-waste-time-on-tdd.html)
* [Rails 5 Test Prescriptions](https://pragprog.com/book/nrtest3/rails-5-test-prescriptions)
* [mutant and minitest within a Rails application](http://andrzejonsoftware.blogspot.com/2015/12/mutant-and-minitest-within-rails.html)

#### MiniTest



#### Rspec

* [rspec-rails](https://github.com/rspec/rspec-rails)
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails)

### Hosting

* [Heroku](https://heroku.com) - free for one site with moderate traffic volumes.
  - [Dashboard](https://dashboard.heroku.com/apps)
  - [Getting Started Guide for Ruby](https://devcenter.heroku.com/articles/getting-started-with-ruby)
  - [CDN setup](https://devcenter.heroku.com/articles/using-amazon-cloudfront-cdn) - e.g., Amazon CloudFront
