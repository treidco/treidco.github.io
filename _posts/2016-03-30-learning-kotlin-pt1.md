---
layout: post
title:  "Learning Kotlin (part 1)"
date:   2016-03-30 13:20:15 +0000
categories: kotlin dev learning
---

### Basics
Investigating some language features by going through the [Kotlin Koans][try-kotlin].

Basic function syntax:

{% highlight kotlin %}
fun start(): String = "OK"
{% endhighlight %}

#### Named and Default Arguments

{% highlight kotlin %}
fun doSomething(
    arg1: String = "abc", 
    arg2: String) 
    {...}

doSomething(arg2= "def")
{% endhighlight %}
Like Scala, Kotlin supports both named and default arguments. 
This reduces the need for overloaded methods that are common in Java. 

#### Lambdas
Lambda support as expected:
{% highlight kotlin %}
fun containsEven(collection: Collection<Int>): Boolean = 
    collection.any { x -> x %2 == 0 }
{% endhighlight %}

{% highlight kotlin %}

{% endhighlight %}

[try-kotlin]: http://try.kotlinlang.org/#/Kotlin%20Koans/Introduction/Hello,%20world!/Task.kt