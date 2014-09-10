---
layout: post
title:  "Usage Instruction"
date:   2014-09-10 20:45:35
categories: 
---

## Getting Started

(Assuming you know what Jekyll and Github pages are.)

* Download this theme's zip file from [here](http://goo.gl/iC85jv) or clone the repository using ```git clone https://github.com/brijeshb42/bitwiser.git```. If you are cloning, then make sure to delete the ```gh-pages``` branch as it includes the files for the theme website.

* Install ```ruby``` and then do ```gem install jekyll```. This theme uses the latest ```jekyll``` version. So if you already have it installed, then upgrade it.

* ```_config.yml``` describes all the variables which you are required to set. The description begins with double hash(```##```). And the value to be set is commented below it using ```#```.

* Edit ```_config.yml``` according to your requirements.
	* ```name``` : ```Your website name```
	* ```disqus``` : ```disqusForumName```
		If this value is present, disqus commenting will be automatically added to all your blog posts.
	* ```ga_id``` : ```googleAnalyticsID```
		If this value is present, google analytics will be added to your website/blog.
		If ```ga_id``` is present, make sure that ```ga_domain``` is also present.
	* ```description```: ```A short description of your website to be included in meta tag of your homepage```
	* ```keywords``` : ```a few frequently used keywords on your site```
	* ```links``` : This vriable has a few commonly used social networks' links
		* ```facebook```: ```facebookId```
		* ```twitter``` : ```twitterHandle```
		* ```email```: ```email@example.com```
		* ```github```: ```githubUsername```
	* ```about_image```: This is a new variable introduced. If defined, make sure the image is present in ```img``` directory. If not defined, a provided placeholder image is used. ** If github link is provided in ```links``` variable, then the github profile picture will be used if ```about_image``` is not defined.

* After setting the values in ```_config.yml```, you can start adding posts in the ```_posts``` directory. Remove the example posts from the directory. The name of files in this directory should be according to specifications by ```jekyll```, i.e, ```YYYY-MM-DD-your-post-title.md```. **Note** that the file name extenion can be anything from md, markdown, mkd, textile or html.

* Replace the image files ```favicon.png``` and ```sharer.png``` with images of your own.

* Test the site on local machine using ```jekyll serve``` in the theme directory.

* If all works well, ```git push``` your changes to your github pages repository ```https://github.com/githubUserName/githubUserName.github.io```

* Then visit your blog at [http://githubUserName.github.io](http://githubUserName.github.io).

* If you want to use a custom domain, then edit the ```CNAME``` file and add your own domain ```example.com```. Make sure your domain points to github ip address.