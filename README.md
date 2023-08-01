# Taura-Lab Website

[The Taura-lab website](https://www.eidos.ic.i.u-tokyo.ac.jp) is built with [Jekyll](https://jekyllrb.com/).
Jekyll generates static HTML files from the Markdown files.

GitHub Pages supports Jekyll so that a push to a specific branch of this repository will automatically trigger an update of the website.
If you want to edit/add/delete pages, you only have to edit/add/delete the Markdown files and push your changes to the main branch.

## Building the site
You need to install bundler:

```bash
gem install bundler
```

Run the following command to install the dependencies under `website/`:

```bash
bundle install
```

Run the following command to build the site:

```bash
bundle exec jekyll build
```

Or you can preview the site as you are editing by running the following command and accessing <http://127.0.0.1:4000/>:

```bash
bundle exec jekyll build
```
