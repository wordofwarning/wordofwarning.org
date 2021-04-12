# Word of Warning's website

Word of Warning's [website](https://wordofwarning.org) is built in Jekyll.

To run the site locally:

```
git clone https://github.com/wordofwarning/wordofwarning.github.com.git
bundle install
bundle exec jekyll serve --livereload
```

There is a small test suite to test outgoing links, well formed HTML etc. To run it:

```
bundle exec rake test
```
