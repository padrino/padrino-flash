> **This gem is no longer needed.** Flash messages have been built into Padrino itself (padrino-core) since Padrino 0.11: every Padrino application has `flash` (with `flash.now` and `flash.keep`) once sessions are enabled, without adding this gem. This repository is kept for reference and is no longer maintained.

### Overview

Padrino Flash is a plugin for the [Padrino](https://github.com/padrino/padrino-framework) web framework which adds support for [Rails](https://github.com/rails/rails) like flash messages.

### Setup & Installation

Include it in your project's `Gemfile` with Bundler:

``` ruby
gem 'padrino-flash'
```

Modify your `app/app.rb` file to register the plugin:

``` ruby
class ExampleApplication < Padrino::Application
  register Padrino::Flash
end
```

### Dependencies

* [Padrino-Core](https://github.com/padrino/padrino-framework) and [Padrino-Helpers](https://github.com/padrino/padrino-framework)
* [Ruby](http://www.ruby-lang.org/en) >= 1.9.2

### Copyright

Copyright © 2012 Benjamin Bloch (Cirex). See LICENSE for details.