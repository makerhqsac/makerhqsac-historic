---
layout: post
title: "Project Noiseometer: Wrap-up and Moving Forward"
---
<img src="{{ site.baseurl }}/images/cat_noiseometer_filter_crop.jpg" class="image" style="margin: 0 auto; display: block; width:45%">
<span id="hq">W</span>e began our first community project build just about a month ago with the making of a sleek noise pollution data collection device, dubbed "Project Noiseometer".

The project idea started with the majority of us living in the somewhat dense Midtown, Sacramento neighborhood, where there are corridors plagued by incessant noise pollution. This can come in the form of loud, fast one way streets that host vehicles with modifications to increase noise generation or it can come from the ever constant construction occuring Downtown. Regardless, we noticed that absolutely no one was collecting, plotting, and analyzing this sound data to better educate civic leaders of the potential problem of noise pollution.

At MakerHQ, we're huge fans of getting our hands on raw data. Despite searching, we could not find any current, context-rich datasets put out by the city for noise pollution. So, we decided to collect the data ourselves using the Arduino MKR1000, sound sensors, and the infrastructure already in use by the internet of things devices that are growing in popularity. A lot of the education materials and resources that we used in this project can be found on <a href="http://community.makerhq.org/t/project-noiseometer-noise-pollution-grapher/">our forum post for the project.</a>

<img src="{{ site.baseurl }}/images/noiseometer_breadboard.jpg" class="image" style="margin: 0 auto; display: block; width:45%">


Over four weeks, a group of citizens, some with backgrounds in technology and engineering and some without, came together to go from zero to maker by building, testing, deploying, and fixing these noise pollution detectors. Beginning with simply breadboarding our device to test functionality and configure our server-side requirements for data collection, we quickly moved into creating a printed circuit board that would allow us a more compact form factor.


After solidifying our software stack and receiving our custom designed PCBs, it was time to ice the cake by designing the casing using Autodesk's Fusion360. Once a final design was chosen, we quickly moved to 3D Printing the final components for assembly. To give our case a bit of design flare, we decided to use an accented clear filament at the top of the base, adding just a little complexity to the process of 3D Printing.

<img src="{{ site.baseurl }}/images/noiseometer_board.jpg" class="image" style="margin: 0 auto; display: block; width:35%">

Ultimately, we believe we realized our goal in this build, going from a problem we see in our community to working together to create the beginning prototype of a device that can enable us to better understand our issue. At the same time, there was certainly a huge element of prototype design and execution in this build, going from breadboard to case design in a matter of weeks. These skills are essential and a launching point for anyone interested in starting up a hardware focused company.

Going forward, we hope to produce more of these devices and focus on creating a sleek web application for plotting and exposing the data. All of our assets for the project are open source and we will gladly document and aid in the process of contributing data or development work to the Noiseometer project. The next phase of the project involves producing the device at a lower cost (as of now, the unit is about $70 in parts) and seeking funding for a larger rollout in Sacramento for better data availability.


Questions, comments, concerns? <a href="http://community.makerhq.org/t/join-and-build-with-us/">Discuss this post on our forum.</a>

<div id='discourse-comments'></div>

<script type="text/javascript">
  DiscourseEmbed = { discourseUrl: 'http://community.makerhq.org/',
                     topicId: 86 };

  (function() {
    var d = document.createElement('script'); d.type = 'text/javascript'; d.async = true;
    d.src = DiscourseEmbed.discourseUrl + 'javascripts/embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(d);
  })();
</script>
