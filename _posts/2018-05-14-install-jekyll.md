---
title: Installing Jekyll
---
## Installing Jekyll in Ubuntu 16.04

### Step 1
Update your package list:

> $ sudo apt-get update

### Step 2
Install Ruby and its development libraries as well as ```make``` and
`build-essential` so that Jekyll's libraries will compile once Jekyll is
installed.

> $ sudo apt-get install ruby ruby-dev make build-essential


### Step 3
Add Ruby's `gem` package to your `.bashrc` file:

{% highlight ruby linenos %}
  export GEM_HOME=$HOME/gems
  export PATH=$HOME/gems/bin:$PATH
{% endhighlight %}

### Step 4
Install Jekyll as well as Bundler which manages `gem` dependencies:
> $ gem install jekyll bundler

### Step 5 (optional)
In case you want to use pagination in on your site:
> $ gem install jekyll-paginate

## Viewing your site
In order to view your site, `cd` to your site folder and run:

> $ jekyll serve

Use the `Server address` link generated to view your site in browser.
