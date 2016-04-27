---
layout: post
title:  "MYSQL - SHOW TABLES NOT LIKE..."
date:   2016-03-30 13:20:15 +0000
categories: kotlin dev learning
---

It is possible to wildcard search a list of tables:
{% highlight mysql %}
SHOW TABLES LIKE 'USER%';
{% endhighlight %}

However doing a negative search (not in) is not as nice. If I want to search for all tables without an underscore in the name I can do this:
{% highlight mysql %}
SHOW TABLES WHERE `Tables_in_<DATABASE>` NOT LIKE '%\_%';
{% endhighlight %}
