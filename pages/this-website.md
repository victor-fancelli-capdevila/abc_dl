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

# Creating a new page
What if you want to document something that is not there? You will need another page. For the moment, create a documetn issue (on the right). I will create a link to have new pages. For working in the page, you can copy-paste this template:

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

# Modifying a page
Having a GitHub account, you can just click on "Edit this page" on the right, and you will be redirected to GitHub, were you can work in Markdown. After the modifications, commit the changes (write something meaningful and short in the title, e.g. "Correction of typografic errors"). Then you will neet to make a merge request. I will chekc it and if everything works, I will accept the changes.

## Frontmatter
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
- ```date```:(empty space) and set today's date
- ```version```:(empty space) and version

## Versions

As we have two languages, we want to be able to track changes in both languages. To do this we will use two numbers, the first indicating a major change, then a point and then the second indicating the minor change. What's the difference?

Suppose we have a page in english and in german in version 1.0, and someone modifies the german page. Suppose the modification are:
- just linguistic corrections that are irrelevant for the english version. Then it will be 1.1
- Modification of content, that should also be updated in english (introducing screenshots). Then will be 2.0

Looking at the versions, we will be able to understand if we have to update the other language.

## Date
As the things we're documentating are changing constantly, we use date to have a reference on how updated our information is. This is the reason that we change it with every change and sometimes, if the information is still correct and need no further modification, we will just change the date, to say: "yes, it still works!"

# Adding Images
Screenshot are really usefull and help people to understand what they have to do.

## Creating Images
Taking screenshots depends on the operating system you're using. Normally a key combination with the keyboard taste ``Print`` should do the work, or you can always search for a screenshot program. If you're in web, some browser as Firefox allow to create screenshots after right-clicking

Some  things you should consider:
- Be concrete: try to make a screenshot only of the relevant information in context.
- Control which information you're sharing and avoid sharing personal information.
- If possible, try to signal where the user will click next: selecting the next text or using the mouse pointer.

## Naming images
Try to give meaningful names to the images. A good idea is to use a combination of 2 or 3 words, with - or _ between them. Screenshot01 is not saying a lot about the images, but eduroam_windows_ As anything else could create problems I would suggest **use English alfabet characters and - or _**. Let's focus on the three words:

1.  you can copy this from the title (e.g. eduroam). That will allow us to group all the images of a post, just ordering the images alphabetically.

2. Something more concrete inside this post. A good idea is to consider the headers (for example, windows).

3. Something event more concrete, or directly a number (at best with 0 before it, you may have more than 9 images!).

## Uploading images

You need to upload the images to `/assets/img/docs`.

## Inserting images in a page

You can use markdown to insert an image. Remember, images are in `/assets/img/docs` so from docs you will need to append `../assets/img/docs/` (or `../../assets/img/docs` if you're in the German version).

So your code should look like something as:
```
![](/assets/img/docs/nameofimage)
```

## Alternative text for images

Some people navigate using a different interfaces adapted to their needs. Taking care that this people can also access the information we want to share is our responsibility.

A good way is to add the label "alternative text" with a description of what you can see in the image, so that a person not seeing the images can also follow our instructions. You can write this description between the square brackets. Try to stay in the description of what you see. For example:

> The window for creating a connection or a network, offering the possibility to choose between four options: an arrow signaling the world globe to establish a connection with internet; An arrow pointing a network computer in a pipe, for creating a new Network. The computer in a pipe, but without arrow for creating a manual Wi-Fi connection; finally an icon of a rack to establish a connection with the workspace. At the bottom on the right, two buttons to continue or cancel the process.

would be a reasonable description for:
![The window for creating a connection or a network, offering the possibiliy to choose between four options: an arrow signaling the world globe to establish a connection with internet; An arrow pointing a network computer in a pipe, for creating a new Network. The computer in a pipe, but without arrow for creating a manual wi-fi connection; finally an icon of a rack to establish a connection with the workspace. At the bottom on the right, two buttons to continue or cancel the process.](../assets/img/docs/eduroam-windows-03.png)
