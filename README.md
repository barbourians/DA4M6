# DA4M6



---
## Installation

### Create the repo in GitHub

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
