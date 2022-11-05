# masaaldosey.github.io

My personal webspace.
You can view the website at: https://masaaldosey.github.io

A simple, clean, and responsive [Jekyll](https://jekyllrb.com/) theme for academics.
This template is based on the awesome [al-folio](https://alshedivat.github.io/al-folio/) theme.
It has the following extra features:

- A new theme for dark mode
- Option to show unlimited news posts
- Hyperlinks to articles in publications


## Getting started

For more about how to use Jekyll, check out [this tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/).
Why Jekyll? Read this [blog post](https://karpathy.github.io/2014/07/01/switching-to-jekyll/)!


### Installation

Assuming you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system (*hint: for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*), first [fork](https://guides.github.com/activities/forking/) the theme from `github.com:masaaldosey/masaaldosey.github.io` to `github.com:<your-username>/<your-repo-name>` and do the following:

```bash
$ git clone git@github.com:<your-username>/<your-repo-name>.git
$ cd <your-repo-name>
$ bundle install
$ bundle exec jekyll serve
```

Now, feel free to customize the theme however you like (don't forget to change the name!).
After you are done, **commit** your final changes.
Now, you can deploy your website to [GitHub Pages](https://pages.github.com/) by running the deploy script:

```bash
$ ./bin/deploy [--user]
```
By default, the script uses the `master` branch for the source code and deploys the webpage to `gh-pages`.
The optional flag `--user` tells it to deploy to `master` and use `source` for the source code instead.
Using `master` for deployment is a convention for [user and organization pages](https://help.github.com/articles/user-organization-and-project-pages/).

**Note:** when deploying your user or organization page, make sure the `_config.yml` has `url` and `baseurl` fields as follows.

```
url:  # should be empty
baseurl:  # should be empty
```

## Features

Read about full set of features [here](https://github.com/alshedivat/al-folio#features).

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

This theme is based on the [al-folio theme](https://github.com/alshedivat/al-folio#features) (published by [Maruan Al-Shedivat](https://www.cs.cmu.edu/~mshediva/) and under the MIT license).