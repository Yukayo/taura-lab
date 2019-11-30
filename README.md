# Taura-Lab Website

The Taura-lab website is built with [MkDocs](https://www.mkdocs.org/).
MkDocs generates static HTML files from the Markdown files in `docs/` directory.

## Building the site

You need to install [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) (a MkDocs theme that this website uses):

```
pip install mkdocs-material
```

Run the following command to generate the site under `site/`:

```
mkdocs build
```

Or you can preview the site as you are editing by running the following command and accessing <http://127.0.0.1:8000/>:

```
mkdocs preview
```
