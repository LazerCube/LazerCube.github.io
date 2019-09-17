---
layout: posts
title: Code highlighting in jekyll
author: Elliot
tags: Test
published: false
about: This post shows how markdown can be used to create a post on a website.
image:  https://unsplash.it/730/500/?image=391
image_preview: https://unsplash.it/73/50/?blur=2?image=391
---

#   Html

{% highlight HTMl linenos %}
<div class="row">
    <div class="col-lg-12 intro">
        <h1>Projects</h1>
    </div>
</div>
{% endhighlight %}

#   Ruby

{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}

#   CSS

{% highlight css linenos %}
.thumb-tags{
    position: absolute;
    bottom: 25px;
    left:15px;
    width:85%;
}

.skills{
    list-style: none;
    margin:0px;
    padding:0px;
}

.skills li{
    color:#fff;
    text-shadow: 0 1px 0 rgba(0,0,0,.15);
    line-height: 32px;
    display: inline;
    border-radius: 4px;
    font-size: 12px;
    background: #46a396;
    padding: 4px 9px;
    margin-right: 5px;
}
{% endhighlight %}


<pre>Pre Test</pre>

<code>code test</code>

<pre><code>pre code test</code></pre>
