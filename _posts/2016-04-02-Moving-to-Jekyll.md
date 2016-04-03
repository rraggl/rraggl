---
layout:     post
title:      Switching blogging platform
date:       2016-04-02 11:21:29
summary:    ... my move from Wordpress to Jekyll
categories: Internet
---

Hi there!

Today I am writing you regarding a technical update on this site.

For years I have been running it on Wordpress. However, recently I found all the updating of plug-ins, themes etc. more of a hassle and detrimental to my writing. Therefore I started looking for a new way to run my blog and stumbled across an article on Opensource.com (https://opensource.com/life/16/2/my-jekyll-workflow) which made me quite curious. The promises that were made in this article were almost too good to be true. Free and open source, secure, quick and easy to use, as you can write your blog posts in Markdown. Also, as you are basically just editing text files, you can use any kind of computer to access and edit your blog as you see fit.

So I began checking out how I could make this work. For this, you have to know that I am not a programmer.
Well, unless you need some C64 BASIC, but even that I would call rusty at my best day.
I do have some rudimentary knowledge about HTML and CSS and can read code to figure out / guess what
it does. Jekyll (https://jekyllrb.com) looked promising to save me from having to hand-code every bit of my site and I would not be as vulnerable as I am with a database-run CMS like Wordpress. (Jekyll generates static HTML files, which are basically text files. If a possible attacker wants to do something with that, well, he will just have a text file. Not a database from which he can extract user data or passwords etc.)

To put it in one sentence: The simplicity of Jekyll makes it damned attractive for me!

First, I of course wanted to run it through my domain hosting provider (http://www.mijndomein.nl) but to no avail: Jekyll is programmed in a language called Ruby / Ruby Gems, which is not (yet) supported by them. Hmm... big stumbling block there... If I can't run it, I can't use it, no matter how promising the software is.

Well, after some hours of further research, I came across the following site: https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/

And this got me the right pointers to set up a site on GitHub pages (Which was REALLY new to me but so far I really like this!) and run Jekyll from a repository there. Then, all I had to do was to adjust the necessary CNAME records and "Presto!". That's it!

Now, importing my posts from Wordpress was the next task and it turned out to be quite a pain in the ass: The recommended WP-plugin did not work for me and I could not run the script (or at least I did not know how). So I had to copy and paste everything by hand. Hmm, there must be an easier way... And yes, there was: a nifty little text editor called "Atom" that I had wanted to try out for some time works great. Still copy and paste, but the workflow is a lot easier.

I know, I know, the site does not look like much right now, but please keep in mind that I am still trying to get the hang of this, so please bear with me. The content on here is at the moment more important than the looks. And yes, I know, links are not working yet, some have altogether disappeared, the formatting is off and there are still a bunch of other things to be fixed. Have patience with me, I'll get there!

If you want to leave me your thoughts, please feel free to do so either by Twitter (@rraggl) or by using the mail form on the site.

So long and see you around next time!
