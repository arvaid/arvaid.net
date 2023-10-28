---
title: Hugo-Nyum
date: 2023-09-02T11:19:01+02:00
draft: false
---

I needed a way to have a recipe collection ready at hand (i.e. on my phone) that I can share with my partner.

[Nyum](https://github.com/doersino/nyum) is a shell script that generates HTML from Markdown files using [Pandoc](https://pandoc.org/). While that is really cool, I couldn't manage to get it working on GitHub Actions, so I made a version of the site it generates as a template for [Hugo](https://gohugo.io/) – a popular static site generator that runs this site as well.

Since Hugo is much more well documented and has an existing community, I prefer using it. Porting a theme for it was a fun project to do and a great experience to deepen my knowledge about Hugo.
