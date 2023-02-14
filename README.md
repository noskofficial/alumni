## Quick Start

Before starting, please follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of `Ruby`, `RubyGems`, `Jekyll`, and `Bundler`. In addition, [Git](https://git-scm.com/) is also required to be installed.

### Step 1. Creating a New Site

Create a new repository from the [**Chirpy Starter**](https://github.com/cotes2020/chirpy-starter/generate) and name it `<GH_USERNAME>.github.io`, where `GH_USERNAME` represents your GitHub username.

### Step 2. Installing Dependencies

Before running for the first time, go to the root directory of your site, and install dependencies as follows:

```console
$ bundle
```

### Step 3. Running Local Server

Run the following command in the root directory of the site:

```console
$ bundle exec jekyll s
```

Or run with Docker:

```console
$ docker run -it --rm \
    --volume="$PWD:/srv/jekyll" \
    -p 4000:4000 jekyll/jekyll \
    jekyll serve
```

After a while, navigate to the site at <http://localhost:4000>.

# How to contribute:

- Fork the repo
- Clone the forked repo
- Add your picture in assets/images/ directory with dimension: 512x480
  - Please use the username for the image and format can be jpg, png, webp 
  - **webp is recommended**
- Add your detail in data/authors.yml
```
mukezhz:   <- this is username of yours please keep this unique
  name: Mukesh Kumar Chaudhary
  twitter: mukezhz
  url: https://github.com/mukezhz/
```
- add your information in _posts dir: **naming convension: yyy-mm-dd-firstname-middlename-lastname**
- add the frontmatter properly 
  - section between --- and --- is frontmatter
- you can use normal markdown to add the content below markdown
  - Please don't forget to add: Introduction, Experience and Education Section
```
---
title: Mukesh Kumar Chaudhary
author: mukezhz
date: 2023-02-12 09:02:00 GMT+0545
categories: [Alumni, Student]
tags: [nosk, alumni, alumnus, student, ncit]
math: true
mermaid: true
image:
  path: /assets/images/mukezhz.webp  <- my image
  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
  alt: Mukesh Kumar Chaudhary
---

## Introduction
...

## Experience
...

## Education
- ...
- ...
```
**Note**: image.lqip can be neglected
- git add, commit, push and send the pr to the original repo
- add reviewer to me or any other member we will verify you and violla!!!


**Thank you!!!**
