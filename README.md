"Refresh" is a Hugo theme for blogging.

### Configuration

- Add the following to your `config.toml` file:

```
baseURL = "your website"
languageCode = "en-us"
title = "Site Title"
theme = "refresh"
pygmentsCodefences = true
pygmentsStyle = "friendly"
paginate = 12

[params]
    AuthorName = "Your Name"
    description = "Quick Description"

[taxonomies]
    tag = "tags"
```

- To enable Disqus, add `disqusShortname = "yourdiscussshortname"` in the `config.toml` file.

- For Google Analytics, add `googleAnalytics = "UA-XX-XX"` in the `config.toml` file.

### Creating New Content

- Create a new post with `hugo new posts/new-post.md`.

- Add an "About" section with content in `content/_index.md`. The front matter must include `title: "(your site's title)"`

