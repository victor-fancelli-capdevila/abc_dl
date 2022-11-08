---
layout: sidebar-as-toc
title: About
permalink: /about/
lang: en
version: 0.1
date: 2022-11-05
---

# About

This website was created as part of the materials of the course "The abc of Digital Literacy" which took place in the Karlsruhe University of Arts and Design during the Winter semester 22/23 and is available to everyone: even if the infrastructure of a small university near the black forest may not be not so interesting, we wanted to share our approach in teaching digital tools, digital competence and digital literacy.

# FAQ
## Why don't use a wiki? Or a CMS?

For the purpose of a collective (institutional) documentation a wiki would be a better option: Software like [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) or [DokuWiki](https://www.dokuwiki.org/dokuwiki) are made for this purpose, are great (easy to install and maintain, well documented and so on). Here are some grounds for our strange behavior:

The goal of the course was not to create an institutional documentation, but learning how to do it. Taking the longest path, i.e. using a more general software, is here an interesting option: anyone of the participants will feel more comfortable with this software. In the other way around (learning a wiki and then using a static website generator) will make less comfortable. We think our role is precisely this: to equip our students with a framework so solid, that they can answer to whatever situation (and hoping that the confronted situation is easier as the one we show them).

The conjectural situation in which this course took place, also played an important role: The university had only one employee taking care of the whole infrastructure, which was obviously overcharged and that presented his resignation during the course. Even if he supported the project (again, thank you!), we don't wanted to charge him with more work. That means that we had to consider **maintenance** and **interoperability** (the capacity to export the data to another system): we should be able to maintain it ourselves and the data we create should be easily exported to another system (if the situation changes).

The combination of GitHub and Jekyll seems to fulfill these requirements, and we had some experience working with them. Yes, there may be other alternatives out there, as good as this or even better. On the other hand, we wanted to avoid not being able to solve problems (or that we need so much time to solve some problems), which could lead to frustration. A more radical approach (starting using a tool we never used) would have been interesting, but as a teacher, we think we should talk about things we know.

## You talk about Free Software / Open Source, but you're using GitHub, which is owned by Microsoft....
That's completely true. The short answer is that sometimes things don't work as you would have them. And sometimes you need to check the pros and cons of a such decision. In a perfect world the university would offer a git environment with page pipeline, issue tracker and so on and where users can authenticate themselves with their university credentials. But this is not the situation we faced.

GitHub is a standard in software development and used from some of the projects which software is installed in our university. We wanted to stress the similarity between our small project and these, and the git interface played an important role in it. Even more, GitHub offers an interesting environment for our project and then (especially for me) allowed to create and maintain a website with not so much work.

We considered the potential lock-ins (the things that make it harder to change from a program to another one) that we were facing. As we limit our use to the control version, issue tracker and page-pipeline, these were the elements to consider. The control version and the page-pipeline seems not an enormous problem for this kind of project. The issue tracker may not be easily transferred, but, from my perspective, it can be a sacrifice we can be confronted with. Important here is the dimension of the project.

## This website is hideous...
That's not a question... But, yes, it may be. Why is it ugly? What would you like to change? Then change it or (at least) [open an issue]({{ site.repo }}/issues) with your ideas! The course took place in a design university, so we should have plenty of people more capable than me to make it nicer. This ugly design is our way of saying: you can (and probably should) change it.

We considered the design with two goals (which are not in contradiction with beauty): that the site is accessible and that it took as less resources as possible without losing important things with this constriction. The first one is a must and should be taken seriously, as we want to welcome and share our research with everyone, no matter which media are using to access the information. The second is a good practice for access and ecological reasons: people with old devices will be thankful!

## And there are some mistakes...
Again, this is not a question... Where did you find the mistake? Can you correct it? Then do it!
Even if we would love to write perfectly in any language, we make mistakes, or sometimes we don't express ourselves with enough clarity. We hope that what we're trying to say is more interesting than the mistakes we're doing.

In opposition to other text, we are doing a documentation and hence we refuse the notion of author (and we talk of contributors): we are open to any change that can make the text better. That also means that text are in constant development, which means that, if you want to quote any of our texts, you may find something different the next time you're visiting this site.

{% include toc.html %}
{% include permalinks.html %}
