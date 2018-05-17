---
title: Code Syntax
---
To insert highlight code inside of a post, it's enough to use some specific tags, has directly described into the [Jekyll documentation](http://jekyllrb.com/docs/templates/#code-snippet-highlighting). In this way the code will be included into a ``.highlight`` CSS class and will be highlighted according to the [syntax.scss](https://github.com/mojombo/tpw/blob/master/css/syntax.css) file. This is the standard style adopted by **Github** to highlight the code.

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

Last, a python example:

{% highlight python linenos %}

import numpy as np

x = np.array([2, 3, 1, 0])
print(x)

def sum(a, b):
  return a+b
{% endhighlight %}
