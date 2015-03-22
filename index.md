---
layout: page
title: Home
sitemap:
priority: 1.0
changefreq: weekly
lastmod: 2015-03-22T13:57:30+05:30
---
# Home Page
This is the home page. Change `index.html` to update the contents.

To create a blog in a sub-directory with your own contents on the home page, do these:

* First add `permalink` in `_config.yml` with the value: `/blog/:categories/:year-:month-:day-:title.html`, where `blog` is the sublink to be used for your posts and other values like `categories`, `year`, `month`, `day` and `title` can be used as desired.
* Then change the value of `paginate_path` from `"/page:num"` to `"/blog/page:num"` so that `index.html` file in `blog` directory has access to pagination variable.
* Create a `blog` directory in the root folder of the theme.
* Move the main `index.html` file to the `blog` directory.
* Now create an `index.html` or `index.md` file in your root directory and add content to it as desired.
* Provide a link to your `blog` directory in your page navigation.
* Test your jekyll site.
