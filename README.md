# OmegaT user guides [cApStAn]

Welcome to the **OmegaT user guides** repository, maintained by the [cApStAn](http://www.capstan.be) Tech Team.

This repository contains different OmegaT user guides authored as Markdown files with a modular approach, meant to be built as a static website with MkDocs.

## Block inclusion for modularity

Some sections are common for all or several, whereas some other sections are guide-specific. Only one copy of common sections exist, and that is included as needed when composing the different guides using Django template syntax (e.g. `{% include foo.md %}`).

## Commands

To start the live-reloading docs server:

```
mkdocs serve
``` 

To build the static documentation site:

```
mkdocs build
``` 

To print help message and exit:

```
mkdocs -h
``` 

To commit changes to this Github repository:

```
git add .
git commit -m "A description of the changes"
git push
``` 

To deploy the latest version at [https://capstanlqc.github.io/omegat-guides/](https://capstanlqc.github.io/omegat-guides/):

```
mkdocs gh-deploy
``` 

