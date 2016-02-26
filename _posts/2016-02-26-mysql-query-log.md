---
layout: post
title:  "MySQL Query Log"
date:   2016-02-26 10:51:15 +0000
categories: mysql dev
---

It's sometimes useful to have MySQL print the queries you hit it with.
Here's how (with version 5.5):

{% highlight mysql %}
SET global general_log_file='/path/to/query.log';
SET global general_log=1;
{% endhighlight %}
