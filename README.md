"Refresh" is an extremely minimalistic blogging theme for Hugo. It puts 100% of the focus on your content. No distractions, no fluff, no BS.

### Configuration

- Add the following to your `config.toml` file:

```
baseURL = "your website"
languageCode = "en-us"
title = "Site Title"
theme = "refresh"
pygmentsCodefences = true
pygmentsStyle = "default"
paginate = 12

[params]
    author = "Your Name"
    description = "Quick Description"
    footer = "your footer text"

[taxonomies]
    tag = "tags"
```

- To enable Disqus, add `disqusShortname = "yourdiscussshortname"` in the `config.toml` file.

- For Google Analytics, add `googleAnalytics = "UA-XX-XX"` in the `config.toml` file.

### Creating New Content

- Create a new post with `hugo new posts/new-post.md`. Posts will be contained in a "posts" directory in your content folder.

```
---
title: "your site title"
---
```
