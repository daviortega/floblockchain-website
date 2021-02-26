---
layout: page
title: "Contributing to these web pages"
---

# How to contribute to the FLO webpage

Ensure you have a [Github](https://github.com/) account. Then:

1. Fork the website
- On [https://github.com/daviortega/floblockchain-website](https://github.com/daviortega/floblockchain-website), click `Fork`.
- Once forking completes, click `Settings` and [enable Github pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/).
- Verify that it works by visiting https://YOUR_GITHUB_USERNAME.github.io/site/
  i.e. if your github name is `grinner` then replace `YOUR_GITHUB_USERNAME` with `grinner`.

2. Edit your fork
- The lazy/easy option: just open files in your fork and click `Edit`, then reload the page from your github.io page as above.
- Or clone your fork locally using `git`, edit, then push your changes back to your fork in Github:
```
git clone https://github.com/YOUR_GITHUB_USERNAME/site
git remote add upstream https://github.com/daviortega/floblockchain-website
git fetch --all
git checkout -b my-task-branch upstream/master
(add some files, maybe with git add learn.md images/illustrative.png)
git commit -m "added illustration to learn.md"
git push --set-upstream origin my-task-branch
(then find the link that is displayed, and browse there to easily create a PR)
```
In case you push your work in a branch other than `master` you will not be able to see your changes live
in https://YOUR_GITHUB_USERNAME.github.io/site/. You can either merge your changes in your master branch
or [deploy the website locally on your host](README.md#local-run) and visit http://127.0.0.1:4000.

3. Upstream your changes

- Open a [pull request](https://help.github.com/articles/about-pull-requests/) with your changes.

## Organizing files
Adding a new file? Follow the guidelines [here](https://github.com/mmistakes/so-simple-theme#structure).

## Design changes
Please come discuss design here in the [Telegram chat](t.me/floblockchain).
If your suggestion needs to be shown in context, create a separate page (like example-redesignX-YOUR_USERNAME.md and push to your github.io page, then share the link on the design chat etc.

## Helpful links
This is a good link for basic markdown syntax to help you get familiar if you are a nondev https://sourceforge.net/p/hidereveal/wiki/markdown_syntax/
