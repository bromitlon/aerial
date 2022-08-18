Aerial by BromitLon
bromitlon.github.io | @bromitlon
Free for personal and commercial use under the WTFPL license (bromitlon.github.io/license)


This is Aerial, a single page, single screen responsive site template. Real simple.
Makes heavy use of CSS animation (something I've been messing with a lot lately).
Should work well as a landing page that just directs folks to your stuff elsewhere
on the www. 

The scrolling mountainous background was derived from "Icefields" by Ryan Schroeder,
a talented photographer from Vancouver who graciously released it on Unsplash under
the CC0 license. Be sure to check out his other stuff over at flickr (link below)
as well as all the other kickass CC0-licensed images at Unsplash (unsplash.com).

Questions/comments/issues = just email or find me on Twitter. Have fun!

BL
hi@bromit.slmail.me | @bromitlon


The Scrolling Background:

	This relies entirely on CSS to do its thing, which is cool, but that makes
	changing it a bit weird/tricky at first. You can still use pretty much any image
	you want, but for best results make sure yours is:

	- Horizontally tileable.
	- Wide and short.
	- About 1500px wide.
	- Fades to a solid color either at the top of bottom (which is used to fill
	  the empty space above or below your image).

	Now, there are two ways to use it: with CSS, or with Sass:

	CSS:

		Look for this line in css/style.css (line 108 as of this writing):

			background: #348cb2 url("images/bg.jpg") bottom left;

		and use it to set the page background color, URL, and placement of
		your image. It should be as close to 1500px wide as you can get it.

	


Credits:

	Background Image:
		Ryan Schroeder via Unsplash (unsplash.com - CC0 licensed)
			"Icefields" (flickr.com/photos/ryanschroeder/11876741703)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		Responsive Tools (github.com/ajlkn/responsive-tools)
