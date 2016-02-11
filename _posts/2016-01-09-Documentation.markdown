---
---

### Installation

I'd strongly recommend you to fork [bleu](http://github.com/bk2dcradle/bleu) and use the "upstream" strategy described on [this page](https://help.github.com/articles/fork-a-repo/) to
keep bleu up to date.

If you don't want to do that, just clone [bleu](http://github.com/bk2dcradle/bleu) and use `bundle exec jekyll serve` in the root of the bleu directory.

### Customization

You can edit the variables in `_config.yml` as per your needs. Edit only the variables under
the section marked *User Settings*.

Most of the variables are self explanatory. Notes about few of the non obvious ones:

1. Setting `about_footer` to *true* or *false* will turn the `about` section at the bottom of
every post to *on* or *off* respectively.

2. `meta_description` is the summary that will show up in places like facebook thumbnails,
twitter cards and google search results.

3. Note that you can change the variable `$blue-color` in `_sass/_style.scss` to any color
value that you want.

*Note:* Don't change any variable under *Build Settings*.

---

### Usage

* To create a new post, simply save the `.markdown` file in the `_posts` directory in the format.

{% highlight text %}
year-month-day-name-of-the-file.markdown
{% endhighlight %}

* For Syntax highlighting, bleu uses *Rouge* which is the default highlighter in Jekyll 3 and above. If you don't know how to highlight a code block, [refer](http://jekyllrb.com/docs/templates/).

* To set up Google Analytics tracking id, just set the `tracking_id` variable in `_config.yml`.

---

### License

[MIT](https://github.com/bk2dcradle/bleu/blob/gh-pages/LICENSE). Copyright &copy; [Ankit Sultana](http://twitter.com/AnkitSultana)
