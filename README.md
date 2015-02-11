[![Gem Version](https://badge.fury.io/rb/schema_plus_views.svg)](http://badge.fury.io/rb/schema_plus_views)
[![Build Status](https://secure.travis-ci.org/SchemaPlus/schema_plus_views.svg)](http://travis-ci.org/SchemaPlus/schema_plus_views)
[![Coverage Status](https://img.shields.io/coveralls/SchemaPlus/schema_plus_views.svg)](https://coveralls.io/r/SchemaPlus/schema_plus_views)
[![Dependency Status](https://gemnasium.com/lomba/schema_plus_views.svg)](https://gemnasium.com/SchemaPlus/schema_plus_views)

# SchemaPlus::Views

TODO: Write a gem description

SchemaPlus::Views is part of the [SchemaPlus](https://github.com/SchemaPlus/) family of Ruby on Rails extension gems.

## Installation

<!-- SCHEMA_DEV: TEMPLATE INSTALLATION - begin -->
<!-- These lines are auto-inserted from a schema_dev template -->
As usual:

```ruby
gem "schema_plus_views"                # in a Gemfile
gem.add_dependency "schema_plus_views" # in a .gemspec
```

To use with a rails app, also include

```ruby
gem "schema_monkey_rails"
```

which creates a Railtie to that will insert SchemaPlus::Views appropriately into the rails stack. To use with Padrino, see [schema_monkey_padrino](https://github.com/SchemaPlus/schema_monkey_padrino).

<!-- SCHEMA_DEV: TEMPLATE INSTALLATION - end -->

## Compatibility

SchemaPlus::Views is tested on:

<!-- SCHEMA_DEV: MATRIX - begin -->
<!-- These lines are auto-generated by schema_dev based on schema_dev.yml -->
* ruby **2.1.5** with activerecord **4.2**, using **mysql2**, **sqlite3** or **postgresql**

<!-- SCHEMA_DEV: MATRIX - end -->

## Usage

TODO: Write usage instructions here

## History

* 0.1.0 - Initial release

## Development & Testing

Are you interested in contributing to SchemaPlus::Views?  Thanks!  Please follow
the standard protocol: fork, feature branch, develop, push, and issue pull
request.

Some things to know about to help you develop and test:

<!-- SCHEMA_DEV: TEMPLATE USES SCHEMA_DEV - begin -->
<!-- These lines are auto-inserted from a schema_dev template -->
* **schema_dev**:  SchemaPlus::Views uses [schema_dev](https://github.com/SchemaPlus/schema_dev) to
  facilitate running rspec tests on the matrix of ruby, activerecord, and database
  versions that the gem supports, both locally and on
  [travis-ci](http://travis-ci.org/SchemaPlus/schema_plus_views)

  To to run rspec locally on the full matrix, do:

        $ schema_dev bundle install
        $ schema_dev rspec

  You can also run on just one configuration at a time;  For info, see `schema_dev --help` or the [schema_dev](https://github.com/SchemaPlus/schema_dev) README.

  The matrix of configurations is specified in `schema_dev.yml` in
  the project root.


<!-- SCHEMA_DEV: TEMPLATE USES SCHEMA_DEV - end -->

<!-- SCHEMA_DEV: TEMPLATE USES SHEMA_PLUS_CORE -->

<!-- SCHEMA_DEV: TEMPLATE USES SHEMA_MONKEY -->
