---
layout: post
title: Hosting a blog using Github Pages and Jekyll
---

This site is hosted using Github Pages and Jekyll. 

<!-- more -->

For an introduction to Github Pages see [https://pages.github.com](https://pages.github.com).

For an introduction to Jekyll see [https://jekyllrb.com](https://jekyllrb.com).

I used [Poole](http://getpoole.com) to get going very quickly.

Something to note is that Github Pages has the following plugins enabled: [https://pages.github.com/versions/](https://pages.github.com/versions/). This page show what each plugin does: [https://jekyllrb.com/docs/plugins/#available-plugins](https://jekyllrb.com/docs/plugins/#available-plugins).

So far, I'm using [Vim](http://www.vim.org) to edit templates and posts.

## Advantages
* Free
* Can use custom domain names, for example [http://rixon.org](http://rixon.org)
* Very handy if one uses Github already or familiar with git.

## Disadvantages
* Static site only. For example, it's not a CMS like Wordpress; to create and edit posts one needs to edit files and push them to Github. [^fn-github-editing]
* No SSL for custom domains. For a static site, I don't think this is much of an issue. [^fn-internet-disagrees]
* A bit of a learning curve if one isn't familiar with git.

[^fn-github-editing]: Of course Github supports editing and creating files directly in the browser.

[^fn-internet-disagrees]: I'm sure at least one person on the internet would disagree.
