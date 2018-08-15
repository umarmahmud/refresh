"Refresh" is a Hugo theme for blogging.

### Configuration

- Add the following to your `config.toml` file:

```
baseURL = "http://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"
theme = "refresh"
pygmentsCodefences = true
pygmentsStyle = "manni"
paginate = 8

[params]
    AuthorName = "Your Name"
    description = "My Site Description"
    github = "https://www.github.com/"
    twitter = "https://www.twitter.com/"

[taxonomies]
    category = "categories"
```

- To enable Disqus, add `disqusShortname = "yourdiscussshortname"` in the `config.toml` file.

- For Google Analytics, add `googleAnalytics = "UA-XX-XX"` in the `config.toml` file.

### Creating New Content

- Create a new post with `hugo new posts/new-post.md`.

- Create a new "about" page with `hugo new about/_index.md`. "About" content will go inside `content/about/_index.md`

