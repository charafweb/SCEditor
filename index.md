---
layout: default
title: SCEditor - A lightweight WYSIWYG HTML and BBCode editor
navtitle: Home
permalink: /
---

## Demo

<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"> </script>
<link rel="stylesheet" href="minified/themes/default.min.css" type="text/css" media="all" />
<script type="text/javascript" src="minified/jquery.sceditor.min.js"> </script>
<script>$(document).ready(function() {
	$("textarea").sceditor({
		plugins: 'bbcode',
		style: "minified/jquery.sceditor.default.min.css"
	});
});</script>

<textarea style="width:600px; height:300px">This [b]is[/b] [color=#ff0000]a[/color] [size=3]demo[/size] :).</textarea>

## Setup
First include the JS and CSS files for jQuery and SCEditor:

{% highlight html %}
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<link rel="stylesheet" href="minified/jquery.sceditor.min.css" type="text/css" media="all" />
<script type="text/javascript" src="minified/jquery.sceditor.min.js"></script>
{% endhighlight %}

Then simply do:

{% highlight javascript %}
$(document).ready(function() {
	$("textarea").sceditor();
});
{% endhighlight %}

or for the BBCode WYSIWYG editor do:

{% highlight javascript %}
$(document).ready(function() {
	$("textarea").sceditor({
		plugins: 'bbcode'
	});
});
{% endhighlight %}

For options or more details see the readme or [documentation](http://www.samclarke.com/2012/04/sceditor-documentation/).


## Features

* Bold, underline, italic, superscript and subscript
* Left, center, right and justify text
* Text size, color and font
* As You Type emoticon conversion
* Tables
* Lists
* Code and quote tags
* Images and links
* I18n support


## Compatibility

SCEditor should work in at *least*: IE 6+, FF 3.5, Chrome, Opera 9.5+ &amp; Safari 4+.


## Support
If you find any bugs or have any questions you can contact me via
[my website](http://www.samclarke.com/contact),
via [GitHub](hhttps://github.com/samclarke/SCEditor/issues/)
or by [leaving a comment](http://www.samclarke.com/2011/07/sceditor/).


## Donate

If you would like to make a donation you can via
[PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AVJSF5NEETYYG)
or via [Flattr](http://flattr.com/thing/400345/SCEditor)


## Credits

**SCeditor by:**  
Sam Clarke ([@samclarke](http://github.com/samclarke))

**Nomicons: The Full Monty Emoticons by:**  
Oscar Gruno, aka Nominell v. 2.0 -> oscargruno@mac.com  
Andy Fedosjeenko, aka Nightwolf -> bobo@animevanguard.com

**Icons by:**  
Mark James (http://www.famfamfam.com/lab/icons/silk/)  
Licensed under the [Creative Commons CC-BY license](http://creativecommons.org/licenses/by/3.0/).

