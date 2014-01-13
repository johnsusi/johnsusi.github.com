---
layout: post
title:  "Hello World!"
date:   2013-10-21 10:36:59
categories: news
---

Hello, World!

{% highlight c++ %}



template <typename O> class Deferred {

public:

	explicit Deferred(O* object) : object(object) {}

	Deferred& done(function<void()> fn);
	Deferred& fail(function<void()> fn);

private:

	O* object;

};



{% endhighlight %}

