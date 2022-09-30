---
layout: post
title: How to create new posts
date: 2022-09-07 23:00:00 +0200
description: An explanation on how to create a new post
img: jekyll.webp
tags: [blog]
author: Wim
---
# Intro

Welcome to the *Knowledge Base*, an attempt to share knowledge and ideas between colleagues and friends.

The site is:
* a simple *blog* without an imposed structure, but with some freely assigned tags
* without implied ownership: an open-source (GPL) GitHub project that anyone can use / fork / extend / ..., and hopefully contribute
* hosted in a *timeless* way, via Git on GitHub pages
* programmer-friendly, using *Markdown* (Kramdown)
* accepting contributions using GitHub *pull requests*, see below how to create a new post.
* using a default markdown *linter* to ensure correct syntax (see it as inforcing a *clean build* of the markdown syntax)
* using *peer review* one of the other base contributors should approve the pull request of the contributor before it can be merged

# Submit a pull request with a new or updated post

Any method submitting a pull request will work, but if you are new to Git / GitHub / Pull Requests:
* Make sure you have a GitHub account
* Install a Git client (a suggest using [GitKraken](https://www.gitkraken.com/)), log in (you can use your GitHub account)
* Fetch the *source code* of the blog locally by doing a *Clone* of this GitHub repository
* Create a new branch (e.g. `blazor-wasm-hotreload`)
* Do your necessary changes (create a new post or updating an existing one).  This is explained in detail in the next topic.
* Commit your changes
* Submit your branch as a pull request

Other info:
* A good howto using the Git command line can be found [here](https://opensource.com/article/19/7/create-pull-request-github).
* If you prefer open source, another good graphical Git client is [Git Extensions](http://gitextensions.github.io/)
 
# Creating a new post
 
In Jekyll / GitHub pages,
* All articles of the blog are located in the `_posts`
* Copy `.template-post.md` and give it a name like `YYYY-MM-DD-blazor-wasm-hotreload.md`, or start from a copy of any existing post.
* Open the new file in an editor.  I strongly suggest to use a modern one like [Visual Studio Code](https://code.visualstudio.com/).  This will prevent issues with text encoding.  Visual Studio Code also has a decent [Markdown preview/editor](https://code.visualstudio.com/docs/languages/markdown).
* Update the *frontmatter* of the post, which is located between the lines `---`.  The frontmatter contains the meta data about the post, such as the title, author, tags, ...
* Continue with your blog post after the second  `---` , with your article in markdown syntax.
* A good *extensive* list of Markdown syntax topics is explained [here](https://www.markdownguide.org/basic-syntax).
 
# For the experienced: local hosting
 
Only tested on Ubuntu Linux:
First [install Ruby & Jekyll](https://jekyllrb.com/docs/installation/)
 
``` bash
bundle exec jekyll serve
```
