# Aw::HighstockRails
[Highstock](https://www.highcharts.com/blog/products/highstock/) lets you create stock or general timeline charts in pure JavaScript with sophisticated navigation options like 
a small navigator series, preset date ranges, date picker, scrolling, and panning. 
This gem includes Highstock as an asset in the Rails 5.1+ asset pipeline. Note: Highstock is not free for commercial use, so you'll need a [valid license](https://shop.highsoft.com/) to use Highstock.

Highstock includes highcharts as well so there is no need to include it in your app.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'aw-highstock_rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install aw-highstock_rails

## Usage
Just add the following lines to application.js 

    //= require highstock/highstock
    //= require highstock/highcharts-more
    
Add modules if needed 
    
    //= require highstock/modules/solid-gauge
    //= require highstock/modules/exporting
    //= require highstock/modules/offline-exporting
    //= require highstock/modules/export-data
    //= require highstock/modules/xrange

   
## Thanks
This gem was built after watching a video at [go rails](https://gorails.com/episodes/creating-gems-for-frontend-javascript-libraries).
   

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/alexwebgr/aw-highstock_rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Aw::HighstockRails project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/alexwebgr/aw-highstock_rails/CODE_OF_CONDUCT.md).
