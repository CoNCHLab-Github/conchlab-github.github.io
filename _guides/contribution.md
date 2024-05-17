---
layout: wiki
title: Contributing to CoNCH Lab Wiki
---

## Get started

The lab wiki is powered by [GitHub Pages](https://pages.github.com/) using [Jekyll](https://jekyllrb.com/). The website is deployed from the `gh-pages` branch, so for changing the content, you'll need to commit your changes to this branch. However, you should create a new branch for the changes you want make and when you want to publish them, create a pull request to the `gh-pages` branch.

1. To get your hands on editing, start by cloning the repository:
   
    ```
    git clone https://github.com/CoNCHLab-Github/conchlab-github.github.io.git
    ```
2. Then, checkout the `gh-pages` branch:

    ```
    git checkout gh-pages
    ```
3. Now, you'll need to install and run Jekyll locally to be able to preview the website. Follow this guide for the instructions:
[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

4. From the `gh-pages` branch, create and switch to a new branch for the changes you intend to make:

    ```
    git switch -c <branch-name>
    ```
5. Refer to the other sections on this page to learn how the website works and how you can edit it or add your own content.
   
6. Create a pull request to the remote `gh-pages` branch.


## Structure of the website 
The repository looks like the following:

```
.
├── 404.html
├── assets
│   ├── css
│   └── img
├── _config.yml
├── Gemfile
├── Gemfile.lock
├── _guides
│   ├── backup
│   ├── backup.md
│   └── ...
├── _includes
│   └── toc.html
├── index.md
├── journal_club.csv
├── journal_club.html
├── _layouts
│   ├── default.html
│   ├── home.html
│   ├── post.html
│   └── wiki.html
├── _posts
├── _site
└── _tutorials
    ├── computecanada.md
    ├── git.md
    └── mTRF.md
```

**Files:**
- `404.html`: the "not found" page for when the url cannot be resolved.
- `_config.yml`: contains the website configurations like the description, logo, and etc.
- `Gemfile` and `Gemfile.lock`: files related to managing Ruby gems, which are packages of Ruby applications or libraries **(don't edit these files)**.

**Directories:**
- `assest`: a directory for the assests like `.css` style files in the `css` subfolder and images (e.g. lab logo) in the `img` subfolder.
- `_guides`:
- `_includes`:
- `_layouts`:


## Index/Home page

## Journal Club page

## Edit an existing page

## Adding a new page