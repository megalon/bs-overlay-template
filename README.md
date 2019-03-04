# Beat Saber Overlay Template

This is a simple template project to build OBS overlays for Beat Saber.

I use this template for many of the overlays I've created on my twitch channel, https://www.twitch.tv/megalonttv

This project relies on the HTTP Status plugin to get data from Beat Saber over a websocket.


Make sure you have that plugin installed, or else this won't work.
https://github.com/opl-/beatsaber-http-status

To use the overlay, you can either 
* Open the `index.html` file within OBS as a local file using the Browser Source.

OR

* Serve the file as a local webpage, then access the webpage from the URL. The npm package `serve` works well for this.
