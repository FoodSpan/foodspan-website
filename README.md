# The FoodSpan Website

[![Build Status](https://travis-ci.org/FoodSpan/foodspan-website.svg?branch=master)](https://travis-ci.org/FoodSpan/foodspan-website)

Here, you can find the code that goes behind making the FoodSpan website as awesome as possible!

## Resources

Here's a list of all the awesome resources we've used to make this FoodSpan Website possible!

* Git and GitHub
* DigitalOcean LAMP-based Webserver (to host test site)
* GitHub Pages (to host final site)
* [jQuery](https://jquery.com/) JavaScript Library
* [Bootstrap](http://getbootstrap.com) HTML/CSS/JS Framework
* [Material Kit Bootstrap Theme](http://www.creative-tim.com/product/material-kit)
* [Font Awesome](http://fontawesome.io) Font Icon Toolkit
* [Google Material Icons](https://design.google.com/icons/)
* [Animate.css](https://github.com/daneden/animate.css) CSS Animation Library
* [Roboto](https://fonts.google.com/specimen/Roboto) and [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab) Fonts
* In-house graphic designs

## Setup

Want to run your own copy of this jekyll site? No problem. You'll need a few things:

* [Ruby](https://www.ruby-lang.org/en/), to install [Jekyll](https://jekyllrb.com)
* [Jekyll](https://jekyllrb.com), to build and run the website
* [Git](https://git-scm.com/), to clone this repository
* A Browser, to view the website of course!

First things first, we need to install Jekyll. We assume that you have Git and Ruby installed. If you don't, please visit the links above to install them. We also assume you're using a [Unix-based system](https://en.wikipedia.org/wiki/Unix); if you aren't, follow jekyll's alternatives instruction page.

Type in your command line:
```
gem install jekyll
```

After Jekyll completes its setup, clone the git repository:
```
git clone https://github.com/FoodSpan/foodspan-website.git
```

Then, cd into the repository:
```
cd foodspan-website
```

Inside the repository, all you'll need to do is "serve" the site. Type the following into your command line:
```
jekyll serve
```

After that, you should get a response that looks something like this:

```
jekyll serve
Configuration file: /Users/matthew.wang/github/foodspan-website/_config.yml
            Source: /Users/matthew.wang/github/foodspan-website
       Destination: /Users/matthew.wang/github/foodspan-website/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.605 seconds.
 Auto-regeneration: enabled for '/Users/matthew.wang/github/foodspan-website'
Configuration file: /Users/matthew.wang/github/foodspan-website/_config.yml
    Server address: http://127.0.0.1:4000/foodspan/
  Server running... press ctrl-c to stop.

```

Visit what follows the "Server address:" line (which is normally [http://127.0.0.1:4000/foodspan/](http://127.0.0.1:4000/foodspan/), but that might change soon)!

And voila! Everything should work for you. If something isn't, please let me know on our [issues tracker](https://github.com/FoodSpan/foodspan-website/issues).
