jekyll-starter
==============

A super-simple starter kit for a bare-bones Jekyll instance.  To use, just install Jekyll  (if you haven't already):

    gem install jekyll

... then:

	mkdir my-new-blog; cd my-new-blog
	git clone git@github.com:cnunciato/jekyll-starter.git .

... and then finally:

    jekyll --server

Then open your browser and hit http://localhost:5000.

That'll get you a home page and one post.  The rest is all you!  See the [Jekyll docs](https://github.com/mojombo/jekyll/wiki) for details.

### What This Actually Does	

All this kit does is set you up with the typical Jekyll directory structure, a sample index.html file, a sample post, and a couple of tweaks to the default configuration (port 5000, auto-regenerate true).  That's it -- no header, no footer, no categories, no tags, no Twitter or Disqus, no fanciness.  Deliberately simple, just the basics.