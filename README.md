### Intro

- This is the "Refresh" theme for Hugo. It is an elegant, minimalist theme built for bloggers. Built with Bootstrap 4.

- Author's name (AuthorName), Github username, and Twitter username can be modified in the `config.toml` file.

### CLI Commands

- To create a new post, type `hugo new posts/new-post.md`.

- To create a new "about" page, type `hugo new about/your-name.md`, where `your-name` is the field specified in the "AuthorName" parameter of your `config.toml` file.

- To create a new "projects" page, type `hugo new projects/projects.md`.

### 'Projects' Page

- The data in the "projects" page is populated by a JSON file, which is stored in the `data` folder. Here is a sample data structure for the JSON file:

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


