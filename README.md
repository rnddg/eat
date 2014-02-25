# Simple Recipe Collection

This is a simple recipe collection of favorites that is meant to be easily accessible from any device, quick-loading, and easy to contribute to.

Created for both practice and training with git/GitHub and a desire for a simpler way to file our recipes.

## Hosted with GitHub Pages

This repository is hosted using [GitHub Pages](http://pages.github.com/) and can be accessed from your browser at http://ljvasey.github.io/recipes

### Submitting Recipes

We highly encourage you to submit a recipe! Please try to make sure you're including your own 'perfectly tweaked' version of a recipe, not one cut and pasted verbatim from somewhere on the internet. If you do, please link to the original recipe using the `original_url` variable in each recipe's *YAML front-matter.*

#### What the Heck is YAML Front Matter?

Each recipe is stored in a [Markdown][] file, free of HTML code or other clutter.

At the very top of each recipe file, you'll see a block of code that looks like this, as in the [template recipe][]:

```
---
layout: recipe
title: Teriyaki Sauce Two Ways
original_url:
---
```

This is a section of the YAML front matter needed by the system to format the recipe properly for display on the web. It consists of 3 different _variables_, `layout`, `title`, and `original_url`. To change a variable, simply add a space after a variable's colon, and enter whatever you'd like.

It should be fairly easy to identify what most variables do by their names, but the full list of variables and their uses can be found below.

### Submitting Images

Images can be submitted along with a recipe, or at another time, even from a different user. Only one image per recipe will be displayed, so please choose the best one in your library.

Please do not import images saved from somewhere on the internet. We only want images you or your friends have taken.

Simply place an image with the *same name* as the recipe you want it to associate with in the [recipe images folder][]

##### Recipe-Related Variables

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell


[markdown]: http://guides.github.com/overviews/mastering-markdown/  "Github's 'Mastering Markdown' Page"
[template recipe]: https://raw.github.com/ljvasey/recipes/gh-pages/sauce/teriyaki.md  "Template Recipe"
[recipe images folder]: https://github.com/ljvasey/recipes/tree/gh-pages/img/recipes  "Our Recipe Images Folder"





