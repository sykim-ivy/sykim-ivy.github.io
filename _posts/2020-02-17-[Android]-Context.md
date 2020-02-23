---
layout: post
title: "[Android] Context"
category: Android
tags: [Android]
---

# Context

To insert highlight code inside of a post, it's enough to use some specific tags, 
has directly described into the [Jekyll documentation](http://jekyllrb.com/docs/templates/#code-snippet-highlighting). 
In this way the code will be included into a ``.highlight`` CSS class and will be highlight according to the [syntax.scss]
(https://github.com/mojombo/tpw/blob/master/css/syntax.css) file. This is the standard style adopted by **Github** to highlight the code. 

This is a CSS example:
{% highlight css linenos %}

body {
  background-color: #fff;
  }

h1 {
  color: #ffaa33;
  font-size: 1.5em;
  }

{% endhighlight %}

And this is a HTML example, with a linenumber:
{% highlight html linenos %}

<html>
  <a href="example.com">Example</a>
</html>

{% endhighlight %}

Last, a Ruby example:
{% highlight ruby linenos %}

def hello
  puts "Hello World!"
end

{% endhighlight %}


## 참조
* Context 개념 : <http://blog.naver.com/huewu/110085457720>
* Context 개념 : <https://zxcv5500.tistory.com/258>
* Context 개념 : <http://sunphiz.me/wp/archives/tag/applicationcontext>
* Context & ContextWrapper: <https://black-jin0427.tistory.com/220>