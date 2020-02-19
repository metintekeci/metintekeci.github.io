---
layout: post
title: Markdown for writing!
subtitle: ... boost your focus on ideas, and let rendering handled with a $ git push.
tags: [markdown, productivity]
comments: true
---

Markdown is a plain text formatting syntax for writers. It allows you to quickly write structured content for the web, and have it seamlessly converted to clean, structured HTML.
You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  

Now it is time to learn some more useful features. 

**Here is some bold text**

## Here is a secondary heading  
#### Here is a fourth level heading  

Here's a simple table:

| Financial Model | Actual | Budget | Forecast1 |
| :------ |:--- | :--- | :--- | :--- |
| Total Assets | 150 | 220 | 350 |
:------ |:--- | :--- | :--- | :--- |
| Total Liabilities | 100 | 160 | 280 |
| Shareholder's Equity | 50  | 60 | 70
:------ |:--- | :--- | :--- | :--- |


How about good news from me?

![good news](/img/good-news.jpeg)


It can also be centered!

![good news](/img/good-news.jpeg){: .center-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

This is well enough for this post.  
You can explore more of Markdown, while writing your own posts. 