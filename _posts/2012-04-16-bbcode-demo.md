---
layout: post
title: BBCode Demo
excerpt: Demo of SCEditor used to produce BBCode
tags: [BBCode, demo, example]
categories:
    - Demo
    - BBCode
---
## BBCode demo

<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"> </script>
<link rel="stylesheet" href="/minified/themes/default.min.css" type="text/css" media="all" />
<script type="text/javascript" src="/minified/jquery.sceditor.min.js"> </script>
<script>$(document).ready(function() {
	$("#demo-bbcode").sceditor({
		style: "/minified/jquery.sceditor.default.min.css",
		plugins: 'bbcode',
		emoticons: {
			dropdown: {
				":)": "/emoticons/smile.png",
				":angel:": "/emoticons/angel.png",
				":angry:": "/emoticons/angry.png",
				"8-)": "/emoticons/cool.png",
				":'(": "/emoticons/cwy.png",
				":ermm:": "/emoticons/ermm.png",
				":D": "/emoticons/grin.png",
				"<3": "/emoticons/heart.png",
				":(": "/emoticons/sad.png",
				":O": "/emoticons/shocked.png",
				":P": "/emoticons/tongue.png",
				";)": "/emoticons/wink.png"
			},
			more: {
				":alien:": "/emoticons/alien.png",
				":blink:": "/emoticons/blink.png",
				":blush:": "/emoticons/blush.png",
				":cheerful:": "/emoticons/cheerful.png",
				":devil:": "/emoticons/devil.png",
				":dizzy:": "/emoticons/dizzy.png",
				":getlost:": "/emoticons/getlost.png",
				":happy:": "/emoticons/happy.png",
				":kissing:": "/emoticons/kissing.png",
				":ninja:": "/emoticons/ninja.png",
				":pinch:": "/emoticons/pinch.png",
				":pouty:": "/emoticons/pouty.png",
				":sick:": "/emoticons/sick.png",
				":sideways:": "/emoticons/sideways.png",
				":silly:": "/emoticons/silly.png",
				":sleeping:": "/emoticons/sleeping.png",
				":unsure:": "/emoticons/unsure.png",
				":woot:": "/emoticons/w00t.png",
				":wassat:": "/emoticons/wassat.png"
			},
			hidden: {
				":whistling:": "/emoticons/whistling.png",
				":love:": "/emoticons/wub.png"
			}
		}
	});
});</script>

<textarea style="width:600px; height:300px" id="demo-bbcode">This [b]is[/b] [color=#ff0000]a[/color] [size=3]demo[/size] :).</textarea><!--more-->

## Code behind it

Include the required JavaScript and CSS:
{% highlight html %}
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<link rel="stylesheet" href="/minified/themes/default.min.css" type="text/css" media="all" />
<script type="text/javascript" src="/minified/jquery.sceditor.min.js"></script>
{% endhighlight %}

Then initialize the plugin on any textareas you want to convert:
{% highlight html %}
<script>$(document).ready(function() {
	$("textarea").sceditor({
		plugins: 'bbcode',
		style: "/minified/jquery.sceditor.default.min.css"
	});
});</script>
{% endhighlight %}

Done!
