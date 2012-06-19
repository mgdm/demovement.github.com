---
layout: book
title: How To Get Involved
prev: '<a href="/about/editors.html">Prev: Our Editors</a>'
next: '<a href="/about/copyright.html">Next: Copyright And Licence</a>'
---
# {{page.title}}

## This Is Your Resource!

The people who create this website are digital engineers just like you, and we're making this website to help ourselves and our peers.

## How The Site Works

[The source for the website](https://github.com/demovement/demovement.github.com) is hosted on [Github](http:/github.com), and is built using [Jekyll](https://github.com/mojombo/jekyll) and GitHub Pages.

## Making Changes To The Website

To make your own changes to the website ...

__1. Install Jekyll on your local computer:__

{% highlight bash %}
sudo gem install jekyll
sudo apt-get install python-pygments
{% endhighlight %}

__2. Fork the [demovement.org](https://github.com/demovement/demovement.github.com) repository on GitHub.__

__3. Download the website's source code from GitHub to your local computer__

{% highlight bash %}
git clone https://github.com/your-username/demovement.github.com
{% endhighlight %}

__4. Run Jekyll, to automatically build a local copy of the demovement website:__

{% highlight bash %}
cd <where-you-put-it>/demovement.org
jekyll --auto --server
{% endhighlight %}

__5. Make your changes to the files ending in '.md'.__

These files use the [Markdown](http://daringfireball.net/projects/markdown/) syntax - an easy-to-use way of structuring plain text.

__6. Point your web browser at [http://localhost:4000/index.html](http://localhost:4000/index.html) to see the changes you have made.__

Jekyll automatically rebuilds any files that have changed, whenever you save them.

__7. Commit your changes and push them back to GitHub__

{% highlight bash %}
git commit -a -m 'A message to explain what has changed'
git push origin master
{% endhighlight %}

__8. Issue a pull request to us from the GitHub website__

At this point, our editors will review your pull request and merge it into the website :)
