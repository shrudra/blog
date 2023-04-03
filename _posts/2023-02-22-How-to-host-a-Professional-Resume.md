---
layout: post
title: How to host a Professional Resume with Jekyll and GitHub Pages
---

<!-- ![Jekyll Vitae Theme Screenshot](https://raw.githubusercontent.com/sakhsain/jekyll-vitae/main/assets/images/jekyll-vitae-theme-screenshot.png "Jekyll Vitae Theme Screenshot") -->

Want to make a professional resume and share it with your boss? 😁 So, you’ve come to the right place! today I'll tell you how you can create your Resume / CV with Jekyll and GitHub Pages.

Jekyll is a static site generator that's can deploy your repository as a website. So, let's build your Resume.

First of all, you must have a GitHub account . Then you need to find a Jekyll theme you like. I will recommend you to use the <a href="https://github.com/sakhsain/jekyll-vitae">**Jekyll Vitae**</a>. Because, It looks like a professional CV, as there are no additional colors or images used that are characteristic of an ideal CV. And It's super easy and easy to use.

Now, you have to fork the repository. After forked,  you can rename your repository.


![Fork](https://raw.githubusercontent.com/sakhsain/jekyll-vitae/main/assets/images/fork.png "Fork")

Edit  `_config.yml` . In this file, you can change your site name, your social links, you can add favicon and whatever you want. 

An example of these edited code is below.

<script src="https://gist.github.com/shrudra/1a6c159665633a9634da761d879406c1.js"></script>

Now edit the `index.md` file as you wish. You can write here about yourself, your current employment, your experience and whatever you want. After edited the file, then Go to settings and set master branch as Github Pages source. Now, Your Resume / CV should be ready at `https://<username>.github.io/repo-name/`

Congratulations 🎉, you've finally hosted your Resume. 
