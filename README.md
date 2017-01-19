# Izitoast

Simple wrapper around [IZITOAST](http://izitoast.marcelodolce.com) js notification plugin [visit Authors website.](https://www.google.com "Marcelo Dolce")


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'izitoast'
```
And then execute:

    $ bundle


Add this line to your application.js file:

```javascript
//= require iziToast
```

Add this line to your application.scss (css):

```scss
@import "iziToast";
```

That's it. It works now
## Usage

To test how it works, open your browser console and execute next command:

```javascript
iziToast.success({
    title: 'Hey',
    message: "It's alive! Congratulations!"
});
```

You will see notification in the bottom-right corner of your browser.

To find more about usage options, please [visit Authors website.](https://www.google.com "Marcelo Dolce")

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/BadAllOff/izitoast. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

