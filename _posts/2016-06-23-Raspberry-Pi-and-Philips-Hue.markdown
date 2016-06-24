---
layout: post
title: "Project: rPi Sense HAT Switch for Philips Hue"
---
<img src="{{ site.baseurl }}/images/light_switcher.gif" class="image" style="margin: 0 auto; display: block;">
In one of our [recent meetups](http://www.meetup.com/Sacramento-Open-Hardware/events/231319343/) we were showing off how quickly you can prototype with the [Raspberry Pi Sense HAT](https://www.raspberrypi.org/products/sense-hat/).

Beyond having a really cool 8x8 LED Matrix and a myriad of sensors, you are also given a joystick input on the device. To me, one of the quickest and most impactful demo applications is showing that the joystick input on the Sense HAT can be used to control your smart home devices. In our case, we wanted to connect and work with a [Philips Hue](http://www2.meethue.com/en-us/) internet connected lightbulb.

<img src="{{ site.baseurl }}/images/pi_hue.jpg" class="image" style="margin: auto; width: 50%; display: block;">

So, basically, what you can do to replicate this application of a Sense HAT is set up the Raspberry Pi and simply [get started with the Philips Hue API](http://www.developers.meethue.com/documentation/getting-started). Once you know the URL with which to manipulate the lights and get an idea of how to change values, simply take that URL (including which light to address) and use the code below.

{% gist rjulian/b92d43f8b6378c57dd96d71eaf064438 %}

This code could use cleaning up and being a little more pythonic, but should get the job done as a quick and dirty switch for your Philips Hue. In the future, we'll make an iteration to make use of the 3-axis accelerometer and possibly control the lights based on temperature!

Questions, comments, concerns? <a href="http://community.makerhq.org/t/project-rpi-sense-hat-switch-for-philips-hue/">Discuss this post on our forum.</a>

<div id='discourse-comments'></div>

<script type="text/javascript">
  DiscourseEmbed = { discourseUrl: 'http://community.makerhq.org/',
                     topicId: 69 };

  (function() {
    var d = document.createElement('script'); d.type = 'text/javascript'; d.async = true;
    d.src = DiscourseEmbed.discourseUrl + 'javascripts/embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(d);
  })();
</script>