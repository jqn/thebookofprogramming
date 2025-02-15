# thebookofprogramming

The book of programming site - GitHub pages with Jekyll

## Building site locally

### Install Hombrew

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Install chruby and the latest Ruby with ruby-install

```
$ brew install chruby ruby-install
$ ruby-install ruby 3.4.1
```

Configure your shell to use chruby automatically

```
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
$ echo "chruby ruby-3.4.1" >> ~/.zshrc # run 'chruby' to see actual version
```

### Install rails

```
$ sudo gem install rails
```

### Install Jekyll

```
$ gem install jekyll
```

### Install bundler

```
$ gem install jekyll bundler
```

### Run the site

```
$ bundle install
$ bundle exec jekyll serve
// or
$ jekyll serve --livereload
```

### References

- [Creating a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)
