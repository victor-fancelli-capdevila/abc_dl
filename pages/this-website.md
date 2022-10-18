---
title: Documentation²
permalink: /this-website/
lang: en
date: 2022-10-18
---

# Documentation²
(documentation of the documentation a.k.a. docuemtnation about this website)

# How it works
This website is a fork of [Docsy Jekyll]([https://vsoch.github.io/docsy-jekyll/) by [VanessaSaurus](https://github.com/vsoch), which works with Jekyll and is hosted at GitHub.

We made some modification to simplify it and to have a workaround for having (at least) two languages.

# Making a modification
Having a GitHub account, you can just click on "Edit this page" on the right, and you will be redirected to GitHub, were you can work in Markdown. After the modifications, commit the changes (write something meaningful and short in the title, e.g. "Correction of typografic errors"). Then you will neet to make a merge request. I will chekc it and if everything works, I will accept the changes.

# Frontmatter
At the beginning of the site, you will find the Frontmatter, the setcion between ```---```, written in YAML. It looks something like this:
```
---
title: "your title"
# lang: en or de
lang: en
date: YYYY-MM-DD
version: 00.1
nav-order: 20
tags:
  - tag1
  - tag2
---
```
Change only this two variables
- ```date```:(empty space) and today's date
- ```version```:(empty space) and version

## Versions

As we have two languages, we want to be able to track changes in both languages. To do this we will use two numbers, the first indicating a major change, then a point and then the second indicating the minor change. What's the difference?

Suppose we have a page in english and in german in version 1.0, and someone modifies the german page. Suppose the modification are:
- just linguistic corrections that are irrelevant for the english version. Then it will be 1.1
- Modification of content, that should also be updated in english (introducing screenshots). Then will be 2.0

Looking at the versions, we will be able to understand if we have to update the other language.

## Date
As the things we're documentating are changing constantly, we use date to have a reference on how updated our information is. This is the reason that we change it with every change and sometimes, if the information is still correct and need no further modification, we will just change the date, to say: "yes, it still works!"

### Images
Screenshot are really usefull and help people to understand what they have to do.

### Creating and naming Images

### Uploading images

### Inserting images

# Creating a new page
What if you want to document something that is not there? You will need another page. For the moment, create a documetn issue (on the right). I will create a link to have new pages.



```
---
title: "your title"
# lang: en or de
lang: en
date: YYYY-MM-DD
version: 00.1
nav-order: 20
tags:
  - tag1
  - tag2
---

# Header 1
```
