---
layout: post
title:  "How to Contribute with Jekyll via Cloud9"
date:   2017-04-20 20:38:30 +0000
categories: jekyll
---
You’ll find this post in the `_posts` [directory][posts-dir]. 

### Want to contribute?

Get started using [Jekyll on Cloud9][jekyll-c9].

![coding screen shot setting up jekyll on cloud9][coding-screen-shot]

Jekyll works by generating a static website from basic `_config.yml` settings, front matter data and usage of [markdown][markdown].

To add new posts, simply add a file in the `_posts` directory that follows the standard `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter.

Take a look at the [source][example-front-matter] for this post to get an idea about how it works.

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

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[posts-dir]: https://github.com/selftaughtprogrammers/selftaughtprogrammers.github.io/tree/master/_posts
[jekyll-c9]: https://www.jflh.ca/2016-01-18-running-jekyll-on-cloud9
[example-front-matter]: https://raw.githubusercontent.com/selftaughtprogrammers/selftaughtprogrammers.github.io/master/_posts/2017-04-20-welcome-to-jekyll.markdown
[coding-screen-shot]: /images/coding-screen-shot.gif
[markdown]: https://guides.github.com/features/mastering-markdown/
