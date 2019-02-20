Freelancer Jekyll theme  [![Build Status](https://api.travis-ci.org/jeromelachaud/freelancer-theme.svg?branch=master)](https://travis-ci.org/jeromelachaud/freelancer-theme/) 
=========================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/)

## How to use
 - Place a image in `/img/portfolio/`
 - ~~Replace `your-email@domain.com` in `_config.yml` with your email address. Refer to [formspree](http://formspree.io/) for more information.~~ ( See Edits made in `Updates Section`)
 - Create posts to display your projects. Use the follow as an example:
```txt
---
layout: default
modal-id: 1
date: 2014-07-18
img: cabin.png
alt: image-alt
project-date: July 2014
client: The Client
category: Web Development
description: The description of the project

---
```

## Demo
View this jekyll theme in action [here](https://jeromelachaud.github.io/freelancer-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/jeromelachaud/freelancer-theme/master/screenshot.png)

---------
For more details, read the [documentation](http://jekyllrb.com/)


## Updates
I made a few minor updates to this theme to make it easier to use today with Netlify as the hosting/backend.

**What was updated**
- Gem Files 
    - Updated Gem files to newest versions.
- Form Submission
    - Updated the Form submition to use Netlify's form collector. 

See the theme used in [this tutorial](https://github.com/kocheck/talks/tree/master/2019.Web.Porfolio.Setup) I wrote.