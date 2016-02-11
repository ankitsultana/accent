---
---

### Installation

Installation is easy. Simply download the theme [here](http://github.com/bk2dcradle/Chaplin/archive/master.zip) and run `bundle exec jekyll serve` inside the directory.

However, before going live, set the following variables in `_config.yml`

1. `url` : This is the base url of your website. If you are hosting on GitHub, it should be set to `http://your-username.github.io` for example.
2. `baseurl` : This is the subpath of your site. If you are hosting on GitHub, in a repository named `Blog`, then it should be set to `/blog`.
3. `tracking_id` : Set this to your google analytics tracking id.

Change other variables under *User Settings* in `_config.yml` as you see fit. 

*Note:* Don't change any variable under *Build Settings*.

---

### Usage

* To change the font for the heading, change the `heading_font` variable in `_config.yml`

* To create a new post, simply save the `.markdown` file in the `_posts` directory in the format.

{% highlight text %}
year-month-day-name-of-the-file.markdown
{% endhighlight %}

* For Syntax highlighting, Chaplin uses *Rouge* which is the default highlighter in Jekyll 3 and above. If you don't know how to highlight a code block, [refer](http://jekyllrb.com/docs/templates/).

* To set up Google Analytics tracking id, just set the `tracking_id` variable in `_config.yml`. You also need to set `google_analytics` to `true`

* To use Disqus for Comments, copy the *universal code* from disqus' website, and copy it in `_includes/disqus.html`.

---

### License

MIT. Copyright (c) [Ankit Sultana](http://twitter.com/AnkitSultana)
