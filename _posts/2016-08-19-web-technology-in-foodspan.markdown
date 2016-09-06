---
layout: post
title:  "Dev Corner: The Web Technologies Behind FoodSpan"
date:   2016-08-19 0:12:34 -0500
categories: dev
image: devs-corner/matt.png
author: "Matthew Wang"
---

Heya there, it's your friendly developer Matt here! Today, I want to talk about the technology stack, and more specifically the web technology stack behind FoodSpan's website. For some of you, it may not sound like English; and that's okay! But if you are interested in the technology behind our websites, get ready to go on a journey with me!

## FoodSpan Website Stack

### The Tools

![GitHub Octocat]({{site.baseurl}}/img/blog/devs-corner/github.png)

I go over this a bit in my previous [devs corner](https://foodspan.ca/dev/2016/08/12/dev-corner-matt.html) post, but I use a few tools consistently whenever I code: [GitHub](https://github.com) and [Atom](https://atom.io). GitHub is *the* git-based version-control software/website hybrid, often known as the pariah of open source; Atom is a text-editor developed by the people at GitHub, made in web technologies and is *hackable to its core*. I'm a bit of a GitHub fan myself, and I love their products. But no hate if you don't; to each their own!

We use GitHub at FoodSpan (you can check out our [company organization](https://github.com/FoodSpan/)) to streamline multi-developer work, keep track of all of our code revisions, and generally make coding easier for everyone. If you're someone who programs even a bit, I'd definitely recommend using GitHub.

### The Frontend Stack

I'll be straightforward here: we use [Jekyll](https://jekyllrb.com) as our site-generator, [Bootstrap](https://getbootstrap.com) as our primary CSS framework, and [Font Awesome](https://fontawesome.io) and [Google Material Design Icons](https://design.google.com/icons/) as our font-icon sets. Let's explore them!

#### Jekyll

![GitHub Octocat]({{site.baseurl}}/img/blog/devs-corner/jekyll.png)

The FoodSpan Website is mostly a static, front-end site: there's no backend, no passwords, and no dynamic data. Because of that, CMS-esque tools are super helpful in generating parts of our site: so styling stays consistent, and so the site looks clean. In order to accomplish this, we use [Jekyll](https://jekyllrb.com). Jekyll is a dveloped-in-ruby liquid-based static site generator: it makes things like keeping consistent navbars, post layouts, or generating any type of web content easy! It also has gh-pages support, and is used extensively by the people at GitHub and many other open source projects (like Bootstrap). It's easy to get started with, but has a lot of functionality. I'd definitely recommend it to anybody who's looking into making static sites!

#### Bootstrap

![GitHub Octocat]({{site.baseurl}}/img/blog/devs-corner/bootstrap.png)

[Bootstrap](https://getbootstrap) is pretty well known in the web design community, and once you pick up on what Bootstrap is you'll see it on a lot of sites. **A lot of sites.** Because of that, sites will often get flak for using Bootstrap, as it lowers the amount of coding any developer needs to do, and for a lack of a better term, often acts as a "crutch" for developers. Respectfully, I disagree with this attitude: I think that using tools to make your own work easier is the hallmark of doing anything, just like using a multi-tool. Bootstrap is one pretty good multitool: it's designed for responsive-design, features many CSS utilities, and looks pretty cool! We use a Material Design toolkit in conjunction with Bootstrap so our CSS Components follow the Material Design Guidelines.

That being said, *I don't think that copy-pasting code is the answer,* and we didn't do that with the FoodSpan website. We don't [copy and site layouts](https://startbootstrap.com/template-overviews/agency/), and we spent a lot of time designing our pages, our colour palette (which follows the Google Material Design Guidelines), and making sure that everything plays nicely. I'm proud of the work that we have done with our website, and I've certainly learned a lot about website development from this endeavor (responsive design, flexbox, and accessibility come to mind).

If you don't know what Bootstrap is, you're definitely missing out: it can turn a relatively awful-looking website into a not-so-awful looking website. But if you want your website to be the best, just Bootstrap isn't enough.

#### Icon Fonts

![GitHub Octocat]({{site.baseurl}}/img/blog/devs-corner/font-awesome.jpg)
![GitHub Octocat]({{site.baseurl}}/img/blog/devs-corner/material-design-icons.png)

Icons are pretty important to your website: they help the user understand what's going on! For the FoodSpan website, we used [Font Awesome](https://fontawesome.io) and [Google Material Design Icons](https://design.google.com/icons/): two standard staples of the web-dev circle. Google's Material Design Icons fit well with our design theme, and are pretty well-known; Font Awesome is another icon font addition that helps with the holes missing from Google's MD. Mostly just standard stuff.

One small note I want to make is in terms of accessibility: if you use a screen reader, an icon isn't really the best idea. During the development of the website, that's something I had to consider and reconsider several times: ultimately, I ended up using `aria` attributes and `sr-only` screenreader-specific text to ensure that everybody could navigate our website with ease. That's something that every developer needs to keep in the back of their mind: whether or not your website is usable by everybody.

## So Long, and Thanks for All the Fish!

That just about wraps up our FoodSpan web tech stack overview. Hopefully, you ended up learning something about how FoodSpan was made, and what we used to make this website: I certainly did!

Until next time!

*You can learn more about Matt on his [GitHub](https://github.com/malsf21), [website](https://matthewwang.me/), or [his blog](https://blog.matthewwang.me/).*
