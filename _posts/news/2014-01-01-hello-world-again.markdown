---
layout: post
title:  "Hello World again!"
date:   2014-06-01
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

