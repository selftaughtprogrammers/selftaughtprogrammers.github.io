---
layout: post
title:  "How to Contribute to a Community Website with Jekyll on Github"
date:   2017-04-20 20:38:30 +0000
categories: jekyll
---

## Want to contribute?

![coding screen shot setting up jekyll on cloud9][coding-screen-shot]

### How to make a new post: 

Using Github, add a file in the [`_posts` directory][post-directory] that follows the standard `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter.

See this posts [raw text file][post-structure] as an example.


### How to make a new page:

Same method as making a new post.

See page [raw text file][page-structure] as an example.

Add page file to the [root directory][page-directory].


### How it works.

Jekyll works by generating a static website from basic `_config.yml` settings, front matter data and usage of [markdown][markdown].

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. 
File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. 
If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

Take a look at the [source][post-structure] for this post to get an idea about how it works.

You’ll find this post in the `_posts` [directory][post-directory]. 

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[jekyll-c9]: https://www.jflh.ca/2016-01-18-running-jekyll-on-cloud9

[post-structure]: https://raw.githubusercontent.com/selftaughtprogrammers/selftaughtprogrammers.github.io/master/_posts/2017-04-20-welcome-to-jekyll.markdown

[post-directory]: https://github.com/selftaughtprogrammers/selftaughtprogrammers.github.io/tree/master/_posts

[page-directory]: https://github.com/selftaughtprogrammers/selftaughtprogrammers.github.io/blob/master/about.md

[page-structure]: https://raw.githubusercontent.com/selftaughtprogrammers/selftaughtprogrammers.github.io/master/about.md

[coding-screen-shot]: /images/coding-screen-shot.gif
[markdown]: https://guides.github.com/features/mastering-markdown/
