# About

Simple blog engine for [Refinery CMS](http://refinerycms.com). It supports posts, categories and comments.

Options:

* Comment moderation
* [ShareThis.com](http://sharethis.com) support on posts. Set your key in Refinery's settings area to enable this.

# Install

Open up your ``Gemfile`` and add at the bottom this line

    gem 'refinerycms-blog', '= 1.0.rc16'

Now run ``bundle install``

Next to install the blog plugin run (for Rails 2):

    ruby script/generate refinerycms_blog

Or, for Rails 3:

    rails generate refinerycms_blog

Finally migrate your database and you're done.

    rake db:migrate