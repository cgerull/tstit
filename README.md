# uniblog

A new minimalistic and responsive Jekyll theme. Suitable for blogs and static sites.
Build with Bootstrap and Font-awesome inspired by many technical blogs.

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "uniblog"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: uniblog
```

And then execute:

    `$ bundle`

Or install it yourself as:

    `$ gem install uniblog`

## Usage

Install the gem and use Jekyllon your own server. If you want to use the theme with GitHub pages, unpack the gem and install the layout to your page directory.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cgerull/uniblog. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `uniblog.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
