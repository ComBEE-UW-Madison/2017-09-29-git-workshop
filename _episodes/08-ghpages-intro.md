---
title: Introduction to GitHub Pages
teaching: 10
exercises: 0
questions:
- "What are GitHub Pages?"
- "How can I make a personal website with 
objectives:
- "Walk through the basics of GitHub Pages."
- "Show the interplay between Jekyll and GH-pages to create your own website."
keypoints:
- "The same basics are applied to any template used with Jekyll/GH-pages."
---

GitHub Pages is a static site hosting service that hosts your website directly from a GitHub repository in which you edit and push your changes from. You can create and publish GitHub pages online using Jekyll's themes, or work locally through the command line. GitHub pages can be used to host user, organization, or project website. You are allowed one page per user, and unlimited project pages per user/organization. There are several templates which you can fork/clone from directly on Github, and therefore don't have to know a lick of HTML/CSS. This lesson is to show you how you can easily get up and running with virtually any template to launch your personal website with Jekyll/GitHub Pages. 

[Jekyll](https://jekyllrb.com/) is used to generate your site from plain text to a static website, and [GitHub Pages](https://pages.github.com/) hosts the generated website. There are several [Jekyll Themes](http://jekyllthemes.org/) that you can choose from. For today, we will be working with the [Jekyll Now](http://www.jekyllnow.com/) theme designed by Barry Clark. It's a really quick and easy way to get up and running with a personal website and blog. 

The first element of creating your website from a template is forking the template repository to your own GitHub repository, and giving it a specific name so that GitHub pages knows where to build the repository to. Go to the [Jekyll Now GitHub repository](https://github.com/barryclark/jekyll-now). Fork to your own repository by following these steps: 

[!]../fig/fork.png