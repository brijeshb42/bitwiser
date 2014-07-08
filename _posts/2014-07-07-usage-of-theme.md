---
layout: post
title:  "Using Bitwiser Jekyll theme"
date:   2014-07-08 12:25:35
categories: 
---

## How to get started with this theme

* Download this theme's zip file from [here](http://goo.gl/iC85jv).

* Edit ```_config.yml``` according to your requirements.
	* ```name``` : ```Your website name```
	* ```gituser``` : ```githubUsername```
	* ```email``` : ```email@example.com```
	* ```disqus``` : ```disqusForumName```
		If this value is present, disqus commenting will be automatically added to all your blog posts.
	* ```ga_id``` : ```googleAnalyticsID```
		If this value is present, google analytics will be added to your website/blog.
		If ```ga_id```, is present, make sure that ```ga_domain``` is also present.
	* ```desc```: ```A short description of your website to be included in meta tag of your homepage```
	* ```keywords``` : ```a few frequently used keywords on your site```
	* ```twitter``` : ```yourTwitterHandle```

* After setting the values in ```_config.yml```, you can start adding posts in the ```_posts``` directory. The name of files in this directory should be according to specifications by ```jekyll```, i.e, ```YYYY-MM-DD-your-post-title.md```. **Note** that the file name extenion can be anything from md, markdown, mkd, textile or html.

* Replace the image files ```favicon.png``` and ```sharer.png``` with images of your own.

* ```git push``` your changes to your github pages repository ```https://github.com/githubUserName/githubUserName.github.io```

* Then visit your blog at [http://githubUserName.github.io](http://githubUserName.github.io).

* If you want to use a custom domain, then edit the ```CNAME``` file and add your own domain ```example.com```. Make sure your domain points to github ip address.