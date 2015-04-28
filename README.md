# Bitwiser Jekyll theme.
A minimalist Jekyll theme that puts focus on content.

### For subdirectory blog support, checkout [subdirectory](https://github.com/brijeshb42/bitwiser/tree/subdirectory) branch.

## Features

* Clean, simple and responsive layout
* Code formatting.
* Sitemap included.
* Google analytics.
* Disqus commenting (Loaded lazily).
* Share post to facebook and twitter.
* Robots.txt included.
* Custom 404 error page.
* Clean material like layout.
* Awesome navigation menu on small screens.

Theme website: http://bitwiser.in/bitwiser/

Demo post: http://bitwiser.in/bitwiser/demo.html

Usage: [http://bitwiser.in/2014/09/10/bitwiser-jekyll-theme.html](http://bitwiser.in/2014/09/10/bitwiser-jekyll-theme.html)

Download latest Zip: [Here](http://goo.gl/iC85jv)

Or browse releases: [Releases](https://github.com/brijeshb42/bitwiser/releases)

To get started with this theme, read the [usage guide](http://bitwiser.in/2014/09/10/bitwiser-jekyll-theme.html). After that start creating post files in the ```_posts``` directory and push your changes to github.

Report issues: [Issues](https://github.com/brijeshb42/bitwiser/issues/new)

If you are using this theme, do not forget to :star: this repo or tweet [@brijeshb42](https://twitter.com/brijeshb42).

Pull requests are also welcome :thumbsup:.


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
	* ```links``` : This variable has a few commonly used social networks' links
		* ```facebook```: ```facebookId```
		* ```twitter``` : ```twitterHandle```
		* ```email```: ```email@example.com```
		* ```github```: ```githubUsername```
	* ```about_image```: This is a new variable introduced. If defined, make sure the image is present in ```img``` directory. If not defined, a provided placeholder image is used. ** If github link is provided in ```links``` variable, then the github profile picture will be used if ```about_image``` is not defined.
	* ```sidebar```: This is a new variable introduced. It is used to enable/disable sidebar. If present, a sidebar will be displayed. To disable sidebar, just comment this line using ```#```.

* After setting the values in ```_config.yml```, you can start adding posts in the ```_posts``` directory. Remove the example posts from the directory. The name of files in this directory should be according to specifications by ```jekyll```, i.e, ```YYYY-MM-DD-your-post-title.md```. **Note** that the file name extenion can be anything from md, markdown, mkd, textile or html.

* Replace the image files ```favicon.png``` and ```sharer.png``` with images of your own.

* Test the site on local machine using ```jekyll serve``` in the theme directory.

* If all works well, ```git push``` your changes to your github pages repository ```https://github.com/githubUserName/githubUserName.github.io```

* Then visit your blog at [http://githubUserName.github.io](http://githubUserName.github.io).

* If you want to use a custom domain, then edit the ```CNAME``` file and add your own domain ```example.com```. Make sure your domain points to github ip address.
