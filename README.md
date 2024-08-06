# JP For Palestine Website repo

This repository holds the raw files that build the JP4P website: https://jpforpalestine.github.io/jpforpalestine/

The site is built using [`mkdocs-material`](https://squidfunk.github.io/mkdocs-material). 

It builds from the raw markdown files in the `docs/` folder, following the instructions define in `mkdocs.yml`

The build process is automated using GitHub Actions using the workflow defined in `.github/workflows/deploy_mkdocs_site.yml`


## Instructions to run the docs server locally
1. Create a virtual envirnment
2. Run `pip install -e .`
3. Run `mkdocs serve`

