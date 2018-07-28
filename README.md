### Intro

- "Refresh" is a Hugo theme for blogging.

- Author's name (AuthorName), Github username, and Twitter username can be modified in the `config.toml` file.

- To enable Disqus, add `disqusShortname = "yourdiscussshortname"` with your shortname in the `config.toml` file.

- For Google Analytics, add `googleAnalytics = "UA-XX-XX"` with your tracking ID in the `config.toml` file.

### Creating New Content

- To create a new post, type `hugo new posts/new-post.md`.

- To create a new "about" page, type `hugo new about/_index.md`. "About" content will go inside `content/about/_index.md`

- To create a new "projects" page, type `hugo new projects/_index.md`. The data in the "projects" page is populated by a `projects.json` file, which is stored in the `data` folder. The file __must__ be named `projects.json` to work.

- Here is the template for the `projects.json` file:

```
{
   "projects": 
   [
        {
        "name": "Project1",
        "link": "http://www.example.com",
        "desc": "A wonderful project",
        "technologies": ["java", "spring-boot"]
        },

        {
        "name": "Project2",
        "link": "http://www.example.com",
        "desc": "A really cool project",
        "technologies": ["python", "opencv"]
        }
    ]
}
```

