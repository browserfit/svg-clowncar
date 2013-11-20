##Techniques Showcase

This Repo is part of [Browser Fit](https://github.com/BrowserFit) project.

##About this Repo
This is just example of using the Clown Car Technique with SVG to serve optmized images with no extra HTTP request.

##Credits
This example is heavily based on [Nicolas Hoizey's article](http://gasteroprod.com/blog/responsive-icons-with-svg)

##Clown-car Technique

Consists in a way of serving device-optmized images to your user without increasing the number of HTTP Requests, nor inflating your site's size.

##SVG-Clown Car Technique

Conditioning the loaded image to the viewport size.

This technique doesn't condition the image loaded to the viewport size, as considered to be the best option.

But it gets close to it by embbeding the `svg` within the mark-up and conditioning its display with `media queries`. Achieving the best cost/benefit balance.

##Demo
Check the it [live](http://browserfit.github.io/svg-clowncar)