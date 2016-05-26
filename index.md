---
layout: page
title: Qingyu Li's Blog
---
{% include JB/setup %}
<!--
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

$ git clone https://github.com/plusjade/jekyll-bootstrap.git
$ cd jekyll-bootstrap
$ jekyll serve
$ git remote add myorigin https://github.com/USERNAME/USERNAME.github.io.git
$ git fetch myorigin -p
$ git push myorigin HEAD:master
$ gem install jekyll
$ jekyll serve
$ rake post title="Hello World"
$ rake page name="pages/about.md"
$ rake page name="pages/about"
# this will create the file: ./pages/about/index.html
# see https://github.com/plusjade/jekyll-bootstrap/blob/master/Rakefile
-->
<p>
Qingyu Li Blog
</p>

<div id="outline-container-sec-1" class="outline-2">
<h2 id="sec-1">Posts</h2>
<div class="outline-text-2" id="text-1">
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    <em>{{ post.excerpt}}</em>
  {% endfor %}
</ul>
</div>
</div>


