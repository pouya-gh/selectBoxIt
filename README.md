# SelectBoxIt

This gem adds [selectBoxIt(v3.8.1)](https://github.com/gfranko/jquery.selectBoxIt.js) JS to your rails project.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'selectBoxIt'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install selectBoxIt

Then add selectBoxIt files like this:

Add this line to your **application.css** file:

```scss
/*
*= require selectBoxIt/jquery.selectBoxIt
*/
```

And this line your **application.js** file (includes all modules):

```javascript
//= require selectBoxIt/jquery.selectBoxIt
```

You could choose its modules like this:

```javascript
//= require selectBoxIt/modules/jquery.selectBoxIt.core
//= require selectBoxIt/modules/jquery.selectBoxIt.add
//= ...
```


## Contributing

1. Fork it ( https://github.com/psparabara/selectBoxIt/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
