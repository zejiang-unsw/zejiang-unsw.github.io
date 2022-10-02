---
title: 'GitHub Pages: A site to host your personal homepage'
date: 2021-05-06
permalink: /posts/2021/05/blog-post-3/
tags:
  - GitHub
  - Homepage
---

GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website. 

## Setup a GitHub pages

### Template 

There are generally two types of homepage template for researchers, hugo and jekyll theme academic pages. The example shown here uses a customized version based on "minimal-mistakes-jekyll" theme. 

#### GitHub page 
Open a GitHub account and your personal website will be hosted there.

***Note: choose your account name carefully since it will become your website link address in the end, if you do not want to pay for any domain address.***

Download all files of the associated academicpage page from scratch under [Code](https://github.com/academicpages/academicpages.github.io), or download from a researcher's existing GitHub pages, for example, 

1. [Ze Jiang](https://github.com/zejiang-unsw/zejiang-unsw.github.io)
2. [Olivier Gimenez](https://github.com/oliviergimenez/oliviergimenez.github.io)
3. [Sam Zipper](https://github.com/samzipper/website-HEAL)

#### Version control

Download [GitHub Desktop](https://desktop.github.com/) as your version control tool. 

Link **GitHub Desktop** with your GitHub account. 

Add local repository from the downloaded and unzipped folder. Commit and push changes to GitHub when changes have been made. Refresh you homepage at **"Your account name".github.io**. 

#### Personal details

Change details to yours, and there are mainly in the files as follows:
* _config.yml
* _pages: include each individual pages
* _publications: include your publications
* _talks: include your talks
* _projects: include your projects
* _teaching: include your teaching experience
* _posts: include your blogs
* images: include associated images of the website
* files: include associated files of the website

### Customize

1. Organise the order of pages in _data/navigation.yml

2. Author profile on left side of page: 
  * author_profile: false or true

3. Sort the order of sites,for example _pages/talks.html: 

```text
### add curly brackets ({}) and percent sign (%) to each line of codes in the talk.html

#normal order
 for post in site.talks 
   include archive-single-talk.html 
 endfor 

#reversed order
 for post in site.talks reversed 
   include archive-single-talk.html 
 endfor 
```

4. Update _pages/talkmap.html:

```text
###A Git blob (binary large object) is the object type used to store the contents of each file in a repository. 

<p>This map is generated from a Jupyter Notebook file in <a href="https://github.com/zejiang-unsw/zejiang-unsw.github.io/blob/master/talkmap.ipynb">/_talks/talkmap.ipynb</a>, which mines the location fields in the .md files in _talks/.</p>
<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>
```

## How to add a new page

### _config.yml: 

```html
collections:
  people:
    output: true
    permalink: /:collection/:path/
      
defaults:
  # _people
  - scope:
      path: ""
      type: people
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
```

### _pages/people.html

```text
---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---
### add curly brackets ({}) and percent sign (%) to each line of codes in the people.html
 include base_path 

### link the documents under _people folder
 for post in site.people reversed 
   include archive-single.html 
 endfor 
```

### _data/navigation.yml

* Change the title to change the tab name shown online!
* Comment out to not show the People tab online!

```html
# main links links
main:
  - title: "People"
    url: /people/
```


## How to add a Avatar profile

### Add script to HTML or md

```html
<img src="avatar.png" alt="Avatar" class="avatar">
```

### Add class to CSS in assets/css/academicons.css

```html
.avatar {
  vertical-align: middle;
  width: 100px;
  height: auto;
  position: relative;
	overflow: hidden;
  border-radius: 50%;
}
```


