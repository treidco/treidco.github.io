---
layout: post
title:  "Maven Archetypes"
date:   2016-03-30 13:20:15 +0000
categories: kotlin dev learning
---

Creating a root project pom:
{% highlight shell %}
mvn archetype:generate \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DarchetypeArtifactId=maven-archetype-quickstart \
-DarchetypeVersion=RELEASE
{% endhighlight %}

Creating a pom for a submodule:
{% highlight shell %}
mvn archetype:generate \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DarchetypeArtifactId=maven-archetype-quickstart \
-DarchetypeVersion=RELEASE
{% endhighlight %}