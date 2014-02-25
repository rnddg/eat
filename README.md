# Simple Recipe Collection

This is a simple recipe collection of favorites that is meant to be easily accessible from any device, quick-loading, and easy to contribute to.

Created for both practice and training with git/GitHub and a desire for a simpler way to file our recipes.

## Hosted with GitHub Pages

This repository is hosted using [GitHub Pages](http://pages.github.com/) and can be accessed from your browser at http://ljvasey.github.io/recipes

### Submitting Recipes

We highly encourage you to submit a recipe! Please try to make sure you're including your own 'perfectly tweaked' version of a recipe, not one cut and pasted verbatim from somewhere on the internet. If you do, please link to the original recipe using the `original_url` variable in each recipe's *YAML front-matter.*

#### What the Heck is YAML Front Matter?

Each recipe is stored in a [Markdown](https://help.github.com/articles/markdown-basics) file, free of HTML code or other clutter.

At the very top of each recipe file, you'll see a block of code that looks like this, as in [sauce/teriyaki.md](https://github.com/ljvasey/recipes/blob/gh-pages/sauce/teriyaki.md):

```
---
layout: recipe
title: Teriyaki Sauce Two Ways
original_url:
---
```

This is a section of the YAML front matter needed by the system to format the recipe properly for display on the web. It consists of 3 different _variables_, `layout`, `title`, and `original_url`. To change a variable, simply add a space after a variable's colon, and enter whatever you'd like. Most variables will be easy to indentify by their names.

The full list of variables and their uses can be found below.

##### Recipe-Related Variables

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell



