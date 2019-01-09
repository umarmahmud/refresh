"Refresh" is a Hugo theme for blogging.

### Configuration

- Add the following to your `config.toml` file:

```
baseURL = "http://www.umarmahmud.com"
languageCode = "en-us"
title = "umar writes..."
theme = "refresh"
pygmentsCodefences = true
pygmentsStyle = "friendly"
paginate = 12

[params]
    AuthorName = "Umar Mahmud"
    description = "notes on c#/python/web"
    github = "https://github.com/umarmahmud"
    twitter = "https://twitter.com/umarcomputes"
    email = "umar.mahmud@outlook.com"

[taxonomies]
    tag = "tags"
```

- To enable Disqus, add `disqusShortname = "yourdiscussshortname"` in the `config.toml` file.

- For Google Analytics, add `googleAnalytics = "UA-XX-XX"` in the `config.toml` file.

### Creating New Content

- Create a new post with `hugo new posts/new-post.md`.

