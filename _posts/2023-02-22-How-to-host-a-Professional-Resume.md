---
layout: post
title: How to host a Professional Resume with Jekyll and GitHub Pages
---

![Jekyll Vitae Theme Screenshot](https://raw.githubusercontent.com/sakhsain/jekyll-vitae/main/assets/images/jekyll-vitae-theme-screenshot.png "Jekyll Vitae Theme Screenshot")

Want to make a professional resume and share it with your boss? 😁 So, you’ve come to the right place! today I'll tell you how you can create your Resume / CV with Jekyll and GitHub Pages.

Jekyll is a static site generator that's can deploy your repository as a website. So, let's build your Resume.

First of all, you must have a GitHub account . Then you need to find a Jekyll theme you like. I will recommend you to use the Jekyll Vitae. Because, It looks like a professional CV, as there are no additional colors or images used that are characteristic of an ideal CV. It's super easy and easy to use.

Now, you have to fork the repository. After forked,  you can rename your repository.


![Fork](https://raw.githubusercontent.com/sakhsain/jekyll-vitae/main/assets/images/fork.png "Fork")

Edit  `_config.yml` . In this file, you can change your site name, your social links, you can add favicon and whatever you want. 

 An example of these edited code is below.

```
markdown:   kramdown

# Name of your site (displayed in the header)
name: Sakhawat Hossain 

# Short bio (displayed in the header)
description: Web Developer from Bangladesh 

# URL of your favicon image (Use .ico file format for better quality)
favicon: 

error:
  img: https://raw.githubusercontent.com/sakhsain/jekyll-vitae/main/assets/images/error-image.png # URL of an image that you want to use for the '404 - Page not found' page

mail:
  url: sakhwt.hssain@gmail.com  # URL of your email address (e.g. person@example.com)
  address:  #Write whatever you want :-)

github:
  url: https://github.com/sakhsain   # URL of your GitHub account (e.g. https://github.com/username)
  username: sakhsain 

linkedin:  # URL of your linkedin address 
  url:  
  username: 

  
# If you're deploying your site at a repository on GitHub pages
# (http://username.github.io/repo-name)
# and not your user repository (http://username.github.io)
# then add in the baseurl here, like this: "/repo-name"
baseurl: "/myCV" #My Repo name is myCV
```

Now edit the `index.md` file as you wish. You can write here about yourself, your current employment, your experience and whatever you want. After edited the file, then Go to settings and set master branch as Github Pages source. Now, Your Resume / CV should be ready at https://<username>.github.io/repo-name/

Congratulations 🎉, you've finally hosted your Resume which you can later edit using only Markdown and change the style of the Resume.
