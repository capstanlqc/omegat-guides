# OmegaT user guides [cApStAn]

Welcome to the **OmegaT user guides** repository, maintained by the [cApStAn](http://www.capstan.be) Tech Team.

This repository contains different OmegaT user guides authored as Markdown files with, meant to be built as a static website with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material) theme.

[MkDocs](https://www.mkdocs.org/) is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

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

To deploy the static website to [GitHub Pages](https://capstanlqc.github.io/omegat-guides/):

```
mkdocs gh-deploy
```


## Block inclusion for modularity

Some sections are common for all or several, whereas some other sections are guide-specific. Only one copy of common sections exist, and that is included as needed when composing the different guides using Django template syntax (e.g. `{% include 'foo.md' %}`).

Alternative appraoch using Jekyll: https://jekyllrb.com/docs/includes/

## Goals

Create documentation that is:

+ Straightforward to write with simple syntax
+ Easy to maintain with version control
+ Flexible and minimalistic to edit
+ Compatible with many output formats
+ Reusable and platform-independent
+ Leading to a clean and responsive display
+ Compatible with embedding

The means to achieve all those points is Markdown.

Also, issues that we try to solve or avoid:

- copy-pasting
- anyone can edit our guide in PISA Connect's documentation dashboard
- there's no backup in PISA Connect
- PISA Connect only offers editing in a WYSIWYG mode or in plain HTML code

## Steps

1. Exported all Dokuwiki pages as Markdown with the [DokuWiki to Markdown Plugin](https://www.dokuwiki.org/plugin:dw2markdown)
2. Tweaked formatting and paths to included files and images
3. Organized content as guides for different roles, based on the previous guides

## Todo / ways to help

+ Update images
+ Look for @todo in the files and find things to do
+ Test other building tools such as Pandoc, Sphinx, Jekyll, etc. and other hosting sites such as [BookStack](https://www.bookstackapp.com/), [GitBook](Gitbook) or [RTfD](http://www.readthedocs.org)
+ Test other themes
+ Test other authoring formats like reStructuredText, AsciiDoc, Wiki etc.
+ Consider a custom URL in a cApStAn domain, info [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
+ Test export to PDF and ePub

## Embedding

```html
<embed src="https://github.com/capstanlqc/omegat-guides/translation/"
    scrolling="no" frameborder="0" width="100%" height="600">
```

## Tips for writing guides

+ Use the Markdown [Tables Generator](https://www.tablesgenerator.com/markdown_tables) to create or edit markdown tables easily.
+ Keep it short (instructions don't need to be long or verbose to be clear)
+ Keep consistency in headers, e.g. avoid different construtions like:
    + "Check glossary adherence" (imperative + object)
    + "Completion check" (noun phrase)
    + "Creating target files"
+ Use **bold** for window, button and pane labels
+ Use `code` formatting for folder names, file names, paths, etc.
+ Do's and dont's

| 👎 Do not | 👍 Do | Comment |
|-------|-----|---------|
| **Project>Open Recent Project**    | **Project** > **Open Recent Project** | Separate both items in the path with " > ". Bold each separately     |




## Images

+ Width: 745 px (or same as videos?)
+ Font: Dialog 14
+ Labels: orange, padding? 
+ Arrow: thickness, color, etc.
+ Red square with border 3px


<!-- 

00 index.md
00 installation-and-customization.md
10 accessing-the-project.md
20 navigation.md
30 tags.md
40 matches.md
50 glossary.md
60 repetitions.md
70 other-useful-features.md
80 qa-checks.md
90 creating-target-files.md
91 creating-your-deliverable.md
99 shortcuts.md     

 -->

## Review

- check that all pages have prev/next links in the footer, except the first page and the last (which shuold have only next and prev respectively)

<!-- @todo:

    todo: 

see what files in _includes are not in this list 


              - _includes/abbreviations.md
              - _includes/cheatsheet.md
              - _includes/omt-alt-trans.md
              - _includes/omt-autoprop.md
              - _includes/omt-chara.md
              - _includes/omt-conc.md
              - _includes/omt-empty.md
              - _includes/omt-glos-add.md
              - _includes/omt-glos-ins.md
              - _includes/omt-glos.md
              - _includes/omt-html-tag.md
              - _includes/omt-id-repeateds.md
              - _includes/omt-ins-src.md
              - _includes/omt-inst.md
              - _includes/omt-intro.md
              - _includes/omt-mk-tgt.md
              - _includes/omt-nav.md
              - _includes/omt-nav1-panes.md
              - _includes/omt-nav2-files.md
              - _includes/omt-nav3-seg.md
              - _includes/omt-nbsp.md
              - _includes/omt-other.md
              - _includes/omt-pack.md
              - _includes/omt-qa-comp.md
              - _includes/omt-qa-glos.md
              - _includes/omt-qa-tags.md
              - _includes/omt-qa.md
              - _includes/omt-rec-match.md
              - _includes/omt-rec-other.md
              - _includes/omt-rec-tags.md
              - _includes/omt-reps.md
              - _includes/omt-shortcuts.md
              - _includes/omt-tag-insert.md
              - _includes/omt-tag-iss.md
              - _includes/omt-tag-recog.md
              - _includes/omt-tags-com.md
              - _includes/omt-targets.md
              - _includes/omt-match.md
              - _includes/omt-tra-tags.md
              - _includes/omt-unpack-and-recent.md
              - _includes/omt-ver-tags.md
              - _includes/preview-in-microsoft-word.md
              - _includes/preview.md

check what images are not used anymore

-->

## Contributing without cloning

It's not necessary to clone this repo to contribute changes. 

It's possible to open the repository directly from VS Code (as explained [here](https://www.freecodecamp.org/news/you-can-now-edit-anything-on-github-in-vs-code-without-cloning/)).

<!-- @todo: 
    - hide button with capstan logo
    - create one site for each guide to restrict indexing scope
-->