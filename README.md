Audio Map Proof of Concept
=============

Quick proof of concept for audio map.  Random points are added to the map where each color represents a different frequency.  3 pins animate along pre-defined route.  As the pins move the corresponding frequency is played for the closest random point using the [WebAudio API](https://dvcs.w3.org/hg/audio/raw-file/tip/webaudio/specification.html).


###You try out the demo [Here](http://briefjudofox.github.io/audio-map-poc/web/) (Chrome and FireFox only for now)


It should look something like this:
![alt text](https://raw.github.com/briefjudofox/audio-map-poc/gh-pages/screen-caps/audio-map-poc.png "Audio Map PoC")



#####Additional Credits:
A [post by Chris Lowis](http://blog.chrislowis.co.uk/2013/06/05/playing-notes-web-audio-api.html) was really helpful in understanding the WebAudio API.

Built with [Leaflet.js](http://leafletjs.com/) and the [AnimatedMarker Plug-in](https://github.com/openplans/Leaflet.AnimatedMarker) by Aaron Ogle, whose example was also used as a starting point for this demo.





