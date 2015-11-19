---
layout: page
title: 脑洞者!
tagline: 脑洞者
---
{% include JB/setup %}

#### 欢迎来到脑洞者的空间
-------
这里是脑洞者的博客。博客会不定期分享一些有脑洞的文章，欢迎扫描下面的微信二维码关注我们。



#### 目标读者
--------
内容会以科幻和想象为主，也可能会记录一些现实中脑洞比较大的事情。

* 我们的目标阅读对象是所有的脑洞爱好者， 科幻迷。

* 除此之外，我们还特别推荐小孩子看，小孩子处于智力发育期，想象力有无限的发展空间，拓展他们的想象力会让他们一辈子收益。


#### 微信订阅号
-----

我们有微信订阅号，订阅号将同步更新最新的文章，欢迎扫描二维码关注"脑洞者"

<img src="{{ site.url }}/assets/img/qrcode_for_naodongzhe.jpg" width="200" height="200" title="微信订阅号-脑洞者" />	


#### 关于转载
-----
本空间内容除非特别声明，均为原创。脑洞者对原创内容保留所有权利，转载请联系作者。

#### 历史文章
----
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
