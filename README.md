# Taura-Lab Website

[The Taura-lab website](https://www.eidos.ic.i.u-tokyo.ac.jp) is built with [MkDocs](https://www.mkdocs.org/).
MkDocs generates static HTML files from the Markdown files in `docs/` directory.

GitLab CI is configured so that a push to the master branch of this repository will automatically trigger an update of the website.
If you want to edit/add/delete pages, you only have to edit/add/delete the Markdown files and push your changes to the master branch.

## Building the site

You need to install [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) (a MkDocs theme that this website uses):

```
pip install mkdocs-material
```

Run the following command to generate the site under `website/`:

```
mkdocs build
```

Or you can preview the site as you are editing by running the following command and accessing <http://127.0.0.1:8000/>:

```
mkdocs serve
```
