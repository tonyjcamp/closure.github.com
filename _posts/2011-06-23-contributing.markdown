---
layout: post
title: Contribute to Closure Blog
author: @ritch
excerpt: This blog is open source, fork it a submit a post, who knows it might get pulled in?
comments: false
---
by <a href="http://github.com/ritch">@ritch</a>

##Why Open Source a Blog?
This blog is open for the same reason our projects are open. We want to help the community so why not help the community help the community too? Meta? Meta.

##Fork
If you want to contribute a post you're going to need to fork the <a href="https://github.com/closure/closure.github.com">closure.github.com</a> repo.

After you have it locally, explore the contents to see how the blog is setup. The easiest way to write a new post is to copy an existing one, but to make it easier, I've created a TextMate bundle.

With the bundle installed, create a new .markdown file, using the proper naming convention, and type 'post' and hit tab.

That will give you this template:

	---
	layout: post
	title: The Post Title
	author: @ritch
	excerpt:  A short descriptive sentence.
	comments: false
	---
	by <a href="http://github.com/ritch">@ritch</a>

	##Background

Hit tab to navigate through the different required fields and start you post below. If you're not familiar with markdown, check it out [here](http://www.simpleeditions.com/59001/markdown-an-introduction).

##Preview

When you're all done writing your post in markdown, you can preview it by running jekyll on the project.

Installing jekyll is simple:

	sudo gem install jekyll
	sudo easy_install Pygments

Once you have jekyll, you can preview the site by running:

	jekyll --auto --server
	
This will start a jekyll server at [http://localhost:4000](http://localhost:4000). You can change files and it will automatically regenerate the static site.


