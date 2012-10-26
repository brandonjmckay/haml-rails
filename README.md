# A modification of Haml-rails
This modification provides support for Twitter Bootstrap and HAML.

The difference between this mod and the layouts provided by the `twitter-bootstrap-rails` gem:
- This mod uses `section`, `header` and `aside` tags for layout and action buttons
- This doesn't have table tags
- It uses the `.row` and `.span*` tags to setup default labels for attributes

To use this fork, add this line to your Gemfile:

	gem 'haml-rails', :git => "git://github.com/brandonjmckay/haml-rails.git"

Then type bundle into your command prompt. Cheers!

--------------
Haml-rails provides Haml generators for Rails 3. It also enables Haml as the templating engine for you, so you don't have to screw around in your own application.rb when your Gemfile already clearly indicated what templating engine you have installed. Hurrah.

To use it, add this line to your Gemfile:

    gem "haml-rails"

Pretty fancy, eh?

Once you've done that, any time you generate a controller or scaffold, you'll get Haml instead of ERB templates. On top of that, when your Rails application loads, Haml will be loaded and initialized completely automatically! The modern world is just so amazing.

### Contributors

Haml generators originally from [rails3-generators](http://github.com/indirect/rails3-generators), and written by José Valim, André Arko, Paul Barry, Anuj Dutta, Louis T, and Chris Rhoden. Tests originally written by Louis T.

### License

Ruby license or MIT license, take your pick.