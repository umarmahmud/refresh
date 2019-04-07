"Refresh" is an elegant Hugo theme designed with bloggers in mind.

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

- Create a new post with `hugo new posts/new-post.md`. Posts will be contained in a "posts" directory in your content folder.

- Add a "blurb" for your site by creating a `_index.md` directly in your content folder:

```
---
title: "your site title"
---

Your blurb here...

```
