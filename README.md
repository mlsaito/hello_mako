# hola mako

My very first ruby gem.

## Description

An exercise on how to create a ruby gem and publish to [RubyGems](https://rubygems.org/).  
This gem will also help me learn about `rails generate`.

This gem was creating using the command:

```
$ bundle gem hello_mako
```

### Installing

Install gem

```
$ gem install hola_mako
```

### Updating the Gem

Clone repository
```
$ git clone https://github.com/mlsaito/hola_mako.git
```

Build and Test on Local
```
$ cd hola_mako
$ gem build hola_mako.gemspec
$ gem install ./hola_mako-0.0.0.gem
```

Test on IRB
```
$ irb
>> require 'hola_mako'
=> true
>> Hola.hi
Hello world!
```

Reference: [http://guides.rubygems.org/make-your-own-gem/](http://guides.rubygems.org/make-your-own-gem/)

### Deployment

Build the gem

```
$ gem build hola_mako.gemspec
```

Deploy to RubyGems

```
$ gem push hola_mako-0.0.0.gem
```

## Running the tests


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details