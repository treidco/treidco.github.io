---
layout: post
title:  "Kotlin basics"
date:   2016-02-26 13:20:15 +0000
categories: kotlin dev
---

###Visibility
Four visibility modifiers: private, protected, internal, public.
Default is public

###Extending Java classes
... is straightforward:

{% highlight kotlin %}
class AppConfiguration() : Configuration() {

}
{% endhighlight %}
