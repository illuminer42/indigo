---
title: "Markdown Common Elements"
layout: post
date: 2016-02-24 22:44
image: /assets/images/markdown.jpg
headerImage: false
tag:
- markdown
- elements
star: true
category: blog
author: johndoe
description: Markdown summary with different options
---

## Summary:

You can pick as item to see how to apply in markdown.
约翰·拉鲁·赫姆（1802年－1867年）是美国肯塔基州的第18任和第24任州长，不过他的实际在职时间一共还不到14个月。他还先后当选为哈丁县在肯塔基州议会两院中的代表，并四度获选担任肯塔基州众议院议长。1838年，他参选联邦众议员，但最终不敌对手威利斯·格林（Willis Green）。赫姆于1826年首度当选肯塔基州众议员，该议席每届任期仅有一年，但从1826到1843年间，他一共任职了11年。1844年，赫姆当选为州参议员，然后一直担任这一职务直至获选成为辉格党的副州长候选人，是州长候选人约翰·J·克里滕登的竞选搭档。辉格党在这场选举中获胜后，克里滕登于1850年7月底接受美国总统米勒德·菲尔莫尔的指派出任美国总检察长，赫姆也因此继任成为州长。州长任期结束后，赫姆成为当时已深陷运营困境的路易斯维尔和纳什维尔铁路公司总裁。他自掏腰包，投入了数万美元，并努力说服铁道主干线沿途居民出资购买公司股票。1859年铁路建成，但次年他就因与董事会就是否应该把铁路延长至孟菲斯存在分歧而辞职。南北战争期间，赫姆曾公开反对分裂，但北军还是认为他对联盟抱有同情。1862年9月，他因同情南方邦联的罪名被捕，幸而在转送路易维尔监狱时由州长詹姆斯·F·罗宾逊（James F. Robinson）认了出来并将他释放。内战结束后，赫姆成为民主党人，并于1865年再度获得哈丁县选民支持重返州参议院。1867年，赫姆成为该州民主党的州长候选人，虽然身体状况每况愈下，但他还是在全州进行了积极的竞选演说并赢得普选。由于身体太过虚弱，他已无法前往法兰克福举行就职典礼，因此州政府官员安排他于1867年9月3日在自己家中宣誓就职，仅仅五天后，约翰·拉鲁·赫姆就在任上与世长辞，享年65岁。



### Comum Elements
- [Basic formatting](#basic-formatting)
- [Headings](#headings)
- [Lists](#lists)
- [Paragraph Modifiers](#paragraph-modifiers)
- [Urls](#urls)
- [Horizontal Rule](#horizontal-rule)
- [Images](#images)
- [Code](#code)

---

## Basic formatting

This note **demonstrates** some of what [Markdown][1] is *capable of doing*.

And that's how to do it.

{% highlight html %}
This note **demonstrates** some of what [Markdown][some/link] is *capable of doing*.
{% endhighlight %}

---

## Headings

There are six levels of headings. They correspond with the six levels of HTML headings. You've probably noticed them already in the page. Each level down uses one more hash character. But we are using just 4 of them.

# Headings can be small

## Headings can be small

### Headings can be small

#### Headings can be small

{% highlight raw %}
# Heading
## Heading
### Heading
#### Heading
{% endhighlight %}

---

## Lists

### Ordered list

1. Item 1
2. A second item
3. Number 3

{% highlight raw %}
1. Item 1
2. A second item
3. Number 3
{% endhighlight %}

### Unordered list

* An item
* Another item
* Yet another item
* And there's more...

{% highlight raw %}
* An item
* Another item
* Yet another item
* And there's more...
{% endhighlight %}

---

## Paragraph modifiers

### Quote

> Here is a quote. What this is should be self explanatory. Quotes are automatically indented when they are used.

{% highlight raw %}
> Here is a quote. What this is should be self explanatory.
{% endhighlight raw %}

---

## URLs

URLs can be made in a handful of ways:

* A named link to [Mark It Down][3].
* Another named link to [Mark It Down](http://markitdown.net/)
* Sometimes you just want a URL like <http://markitdown.net/>.

{% highlight raw %}
* A named link to [MarkItDown][3].
* Another named link to [MarkItDown](http://markitdown.net/)
* Sometimes you just want a URL like <http://markitdown.net/>.
{% endhighlight %}

---

## Horizontal rule

A horizontal rule is a line that goes across the middle of the page.
It's sometimes handy for breaking things up.

{% highlight raw %}
---
{% endhighlight %}

---

## Images

Markdown can also contain images. I'll need to add something here sometime.

{% highlight raw %}
![Markdowm Image][/image/url]
{% endhighlight %}

![Markdowm Image][6]

*Figure Caption*?

{% highlight raw %}
![Markdowm Image][/image/url]
<figcaption class="caption">Photo by John Doe</figcaption>
{% endhighlight %}

![Markdowm Image][6]
<figcaption class="caption">Photo by John Doe</figcaption>

*Bigger Images*?

{% highlight raw %}
![Markdowm Image][/image/url]{: class="bigger-image" }
{% endhighlight %}

![Markdowm Image][6]{: class="bigger-image" }

---

## Code

A HTML Example:

{% highlight html %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1>Just a test</h1>
</body>
</html>
{% endhighlight %}

A CSS Example:

{% highlight css %}
pre {
    padding: 10px;
    font-size: .8em;
    white-space: pre;
}

pre, table {
    width: 100%;
}

code, pre, tt {
    font-family: Monaco, Consolas, Inconsolata, monospace, sans-serif;
    background: rgba(0,0,0,.05);
}
{% endhighlight %}

A JS Example:

{% highlight js %}
// Sticky Header
$(window).scroll(function() {

    if ($(window).scrollTop() > 900 && !$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeOut('fast');
    } else if (!$("body").hasClass('show-menu')) {
        $('#hamburguer__open').fadeIn('fast');
    }

});
{% endhighlight %}

[1]: http://daringfireball.net/projects/markdown/
[2]: http://www.fileformat.info/info/unicode/char/2163/index.htm
[3]: http://www.markitdown.net/
[4]: http://daringfireball.net/projects/markdown/basics
[5]: http://daringfireball.net/projects/markdown/syntax
[6]: http://kune.fr/wp-content/uploads/2013/10/ghost-blog.jpg
