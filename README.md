## RustBridge Berlin

This repository contains the website data for [RustBridge Berlin's chapter
website](https://berlin.rustbridge.com).

### Local Setup

You will need to have [Jekyll](https://www.jekyllrb.com) installed. 

With that, clone the repository:

``` shell
git clone https://github.com/rustbridge/berlin.git
```

Install the local dependencies:

``` shell
gem install bundler
bundle install
```

After which you can work on the site by running Jekyll's local server:

``` shell
bundle exec jekyll serve --livereload
```
