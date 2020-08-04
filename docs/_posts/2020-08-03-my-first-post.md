---
layout: post
title:  "My First Post!!"
date:   2020-08-03 16:08:07 +0100
categories: introduction test
---
Hi there,
I am trying to use this tool called Jekyll to create a new post.
Lets see how it looks.
I also need to learn markdown.

Testing Code:
```cs
static void Main(string[] args)
{
	System.Console.WriteLine("Welcome!");
	#region say_hello
	Console.WriteLine(new Cat().Say());
	#endregion
}
```

{% capture code %}
static void Main(string[] args)
{
	System.Console.WriteLine("Welcome!");
	#region say_hello
	Console.WriteLine(new Cat().Say());
	#endregion
}
{% endcapture %}
{% include code.html code=code lang="cs" %}

c ya
