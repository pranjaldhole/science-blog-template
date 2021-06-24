---
title: Markdown Typography
---
Markdown is a light-weight and easy to use syntax for styling all forms and
writing on [github](https://github.com/) platform. With Markdown, it is easy to
control the display of the document.
In the following sections, we'll have a look at how basic styling and
type-setting is done in Markdown format.
One can easily insert html code in Markdown in order to render more sophisticated
code. The Markdown files have extension `.md` or `.markdown`.

## Image
### Inserting local image
![]({{"img/logo.svg" | prepend: site.baseurl }}){:height="50%" width="50%"}

{% highlight markdown %}
![Img-Text](/path/to/img.svg){:height="50%" width="50%"}
{% endhighlight %}

### Inserting image from URLs
![](https://pranjaldhole.github.io/images/evolution.jpg){:height="40%" width="40%"}
{% highlight markdown %}
![Img-Text](https://address/to/img.png){:height="40%" width="40%"}
{% endhighlight %}

## Inserting URLs
Similar way external urls can be inserted like [this](http://www.example.com).
{% highlight markdown %}
[this](http://www.example.com)
{% endhighlight %}

## Headers

{% highlight markdown %}
 # This is a <h1> tag.
 ## This is a <h2> tag.
 <h3>, <h4>, <h5> and <h6> have the same style.
{% endhighlight %}

## Type-setting
Insert your text between two double asterisks to make it **bold**.

Insert your text between underscores to make it _italic_.

> This is a blockquote

### Unordered list
- list 1
- list 2
- list 3
- list 4

### Ordered list
1. one
2. two
3. three
4. four
