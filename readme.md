Setup

    bundle install

Bundler is configured to install dependencies inside the ignored `vendor` folder rather than installing them on the system.
See `/.bundle/config` to change this configuration.

To launch and watch on localhost:4000

    jekyll serve --baseurl '' -w --future

(requires jekyll: gem install jekyll)

To deploy on Github Pages

    git checkout gh-pages
    git rebase master
    (SYNC)
    git checkout master
