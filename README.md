### Intro

- This is the "Refresh" theme for Hugo. It is an elegant, minimalist theme built for bloggers. Built with Bootstrap 4.

- Author's name (AuthorName), Github username, and Twitter username can be modified in the `config.toml` file.

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


