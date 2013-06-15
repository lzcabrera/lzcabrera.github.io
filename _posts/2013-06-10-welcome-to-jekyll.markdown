---
layout: post
title:  "Jekyll and Foundation Update"
date:   2013-06-10 11:49:57
categories: jekyll update
---

I am doing a little bit of cleaning up, organizing and merging online properties to try to have everything all under one domain. It is all part of the branding strategy. 

This blog now runs on [Jekyll 1.0.3](http://jekyllrb.com). It is still hosted on Github, and the front-end is now using Zurb Foundation 4.

I know it still looks the same, but I figured I should update it because I hope to make some time in the future to maybe make use some of the cool features built-in into Foundation.

While working on the upgrade, I was debating between Middleman and Jekyll, but decided to go with Jekyll because Middleman doesn't work with Ruby 2.0 yet.

I went with Jekyll because it runs on Ruby 2.0 and  also because it offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
