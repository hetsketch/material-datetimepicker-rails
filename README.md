# Material::Datetimepicker::Rails

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/material/datetimepicker/rails`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'material-datetimepicker-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install material-datetimepicker-rails

## Usage

Add this line to your application.js file
```js
//= moment
//= rome
//= material-datetime-picker
````

Add following to your application.scss file
```scss
@import "material-datetime-picker";
```

**If you are using gem with Materializecss, you should to add this custom SCSS classes cause JS lib hasn't support Materializecss yet.**

```scss
.c-datepicker {
  box-sizing: content-box !important;
  button {
    background-color: #fff !important;
  }
}

.c-datepicker__calendar {
  box-sizing: border-box;
}

.c-datepicker__days {
  box-sizing: border-box;
  border-collapse: separate;
  border-spacing: 2px;
  border-color: grey;
  width: 0;
  td, th {
    padding: 0;
    margin-bottom: 2px;
    text-align: center;
  }
}

.c-datepicker__days-head {
  border: none !important;
}

.c-btn {
  @extend .btn
}

.c-btn--flat {
  @extend .btn-flat
}
```
## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/hetsketch/material-datetimepicker-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

