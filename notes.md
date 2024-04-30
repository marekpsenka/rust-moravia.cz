# Notes

## Viewport

### [Responsive Web Design](https://en.wikipedia.org/wiki/Responsive_web_design)

Responsive Web Design is an approach to web design that aims to make web pages render well on
a variety of devices and window or screen sizes from minimum to maximum display size to ensure
usability and satisfaction.

### Viewport

[Responsive Web Design - The Viewport](https://www.w3schools.com/css/css_rwd_viewport.asp)

```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

The `width=device-width` part sets the width of the page to follow the screen-width of the device
(which will vary depending on the device).

The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

### Size Content to The Viewport

Users are used to scroll websites vertically on both desktop and mobile devices - but not horizontally!

So, if the user is forced to scroll horizontally, or zoom out, to see the whole web page it results
in a poor user experience.

Some additional rules to follow:

1. Do NOT use large fixed width elements - For example, if an image is displayed at a width wider
than the viewport it can cause the viewport to scroll horizontally. Remember to adjust this content
to fit within the width of the viewport.

2. Do NOT let the content rely on a particular viewport width to render well - Since screen
dimensions and width in CSS pixels vary widely between devices, content should not rely
on a particular viewport width to render well.

3. Use CSS media queries to apply different styling for small and large screens - Setting large
absolute CSS widths for page elements will cause the element to be too wide for the viewport on a 
smaller device. Instead, consider using relative width values, such as width: 100%.
Also, be careful of using large absolute positioning values. It may cause the element to fall
outside the viewport on small devices.

## [OpenGraph Protocol](https://ogp.me/)

The Open Graph protocol enables any web page to become a rich object in a social graph. For
instance, this is used on Facebook to allow any web page to have the same functionality as any other
object on Facebook.

Meta tags for social networks and modern chat tools are responsible for automatic thumbnails of 
pages where a user shares the URL of your website.

[Open Graph Meta tags validator](https://metatags.io/)
