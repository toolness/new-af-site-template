This is an attempt to convert Brynn Evans' new [Awesome Foundation][af] homepage mockup into HTML.

Currently, it's all HTML5, which basically means it looks as-intended on the latest versions of Firefox, Chrome, Safari, and Opera, but it looks a bit wonky on older versions of those browsers and Internet Explorer 8.

Not sure what it looks like on IE 9 yet.

## Issues

* Right now the AF logo is SVG, which is neat because it's small and can scale to whatever resolution we want. However, we might need to either replace this with an image or a Webdings equivalent for older browsers that don't support SVG.

* Page loading looks weird because the default background is set to the footer background, which results in a weird flash of color as the content background gets loaded and kicks in. Yuck.

* The CSS currently measures everything in pixels, ems, and percentges. Is that OK?

* We should make sure that this site is [ARIA][] compliant, but no work has been put into doing that yet.

* This template doesn't look great on mobile devices right now, as it requires the user to zoom into parts of the page to be able to read them. We might want to design a separate CSS for mobile devices.

[af]: http://awesomefoundation.org
[ARIA]: http://en.wikipedia.org/wiki/WAI-ARIA
