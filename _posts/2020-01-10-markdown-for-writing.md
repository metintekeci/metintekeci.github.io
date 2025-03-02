---
layout: post
title: Markdown for writing!
subtitle: ... boost your focus on ideas, and let rendering handled with a $ git push.
tags: [markdown, productivity]
comments: true
---
## MARKDOWN:Create top level Heading with single '#' character

Markdown is a plain text formatting syntax for writers. It allows you to quickly write structured content for the web, and have it seamlessly converted to clean, structured HTML.
You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  

Now it is time to learn some more useful features.

you can add some emphasis using double underscore '_' before and after the text to make it look like this __Here is some bold text__

Lets test the headings by increasing '#' characters:

## Here is a secondary heading  

### Here is a third level heading  

#### Here is a fourth level heading  

Markdown enables creating tables also, here's an example:

| Financial Model | Actual | Budget | Forecast1 |
| :------ |:--- | :--- | :--- | :--- |
| Total Assets | 150 | 220 | 350 |
:------ |:--- | :--- | :--- | :--- |
| Total Liabilities | 100 | 160 | 280 |
| Shareholder's Equity | 50  | 60 | 70
:------ |:--- | :--- | :--- | :--- |

Creating tables with hyphens and pipes can be tedious. To speed up the process, you can try using the [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables). Visit the website, build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file.

Images can also be added from your preferred folder.  
`'!\[text_about_image](/foldername/imagefile.extension)\]'`  

How about an image of good news from me?

![good news](/img/good-news.jpeg)

the image can also be centered using a `{: .center-block :}` following the image link above.

![img](/img/good-news.jpeg){: .center-block :}

Here's a code chunk with syntax highlighting by using " ``` " character and to wrap the code and also mention the programming language.

template:

\```  language_name ie : javascript  

some code block here  

\```

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
__Note:__ This is a notification box.

### Warning

{: .box-warning}
__Warning:__ This is a warning box.

### Error

{: .box-error}
__Error:__ This is an error box.

This is well enough for this post.  
You can explore more of Markdown, while writing your own posts.
