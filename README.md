- "Refresh" is a Hugo theme for blogging.

### Configuration

- Add the following to your `config.toml` file:

```
baseURL = "http://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"
theme = "refresh"
pygmentsCodefences = true
pygmentsStyle = "manni"

[params]
    AuthorName = "Your Name"
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

- Create a new "projects" page with `hugo new projects/_index.md`. The data in the "projects" page is populated by a `projects.json` file, which is stored in the `data` folder. The file __must__ be named `projects.json` and adhere to the structure below to work.

- Here is the structure for the `projects.json` file:

```
{
    "projects": [
        {
            "name": "Project1",
            "link": "https://www.example.com",
            "desc": "Project1 description",
            "technologies": [
                "java",
                "spring-boot"
            ]
        },
        {
            "name": "Project2",
            "link": "https://www.example.com",
            "desc": "Project2 description",
            "technologies": [
                "python",
                "opencv"
            ]
        }
    ]
}
```

