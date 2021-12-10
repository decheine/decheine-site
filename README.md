# decheine-site

Personal website to display research and projects

Live website: https://decheine.github.io/decheine-site

## Building locally

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
1. [Install][] MkDocs
1. Preview your project: `mkdocs serve`,
   your site can be accessed under `localhost:8000`
1. Add content
1. Generate the website: `mkdocs build` (optional)

```
git clone https://gitlab.com/decheine/mkdocs.git
cd ricochet-docs
pip install -r requirements.txt
mkdocs serve
```

## Deploying to GitHub Pages

The deploy command

```
mkdocs gh-deploy
```

Must be done after changes have been made to the site. Preview the site and edits locally before deploying. Changes to the repository will not be reflected until the deploy command is run.

## TODO

Figure out a way to automatically update the CV file as it changes.
