# DA4M6



---
## Installation

### Create the repo in GitHub
- Needs to be a Public repository
- Add a README.md
- Include a Python `.gitignore` file

### Setup locally
- git clone
- Install Python virtual enviroment: `python3 -m venv venv`

### Install mkdocs
- $ `pip install mkdocs-material`

### Create your site
- $ `mkdocs new .`

### Setup your site
edit `mkdocs.yaml`:

```
site_name: My Site
theme:
  name: material
```

### Test your site
- Run $ `mkdocs serve`
- point your browser to: `localhost:8000`

### Build and push your site
- Run $ `mkdocs build`
- **Commit your changes and push to GitHub** (on the main branch)

### Publish your site
- Run $ `mkdocs gh-deploy --force`
- `--force` will force the push to GitHub

### Setup GitHub Pages
- go to the repo in GitHub
- click **Settings**
- click **Pages**
- In **Build and Deployment** click: Branck --> Select branch: gh-pages and Save

### Success!
Go to the URL: `https://barbourian/github.io/<REPO>/` to verify that the site has been created.

---
## Ongoing changes

### locally
- make the changes locally in main branch or a dev branch
- test by runing `mkdocs serve`
- when finished run `mkdocs build`
- push changes to GitHub
- create pull request if required
- when changes are in the main branch run: `mkdocs gh-deploy --force`
