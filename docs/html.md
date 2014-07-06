# HTML Template
...

* * *

## A breakdown of the HTML template
**Language Attribute**<br>
By default, the language attribute <code>(lang)</code> is set to English. It is recommended you update this to your [local language](http://www.w3.org/International/questions/qa-choosing-language-tags).

**The NO-JS Class**<br>
Allows you to add custom styles when JavaScript is disabled (<code>no-js</code>).

**X-UA-Compatible**<br>
This makes sure the latest rendering mode for IE is triggered.

**Mobile Viewport**<br>
To ensure scale settings remain consistent when switching orientations on the iPhone.

**Favicons**<br>
The standard favicon for Desktop devices and 3 icons for Apple mobile and tablet devices.

**Custom Modernizr**<br>
A custom build of Modernizr is included which checks support for JS, SVG and Touch (adds supported / fallback classes to the <code>html</code> element).

**jQuery (Google CDN)**<br>
The latest jQuery version is included (referenced from Google's CDN) along with a local fallback for offline development.

**Google Analytics**<br>
An optimized version of Google Analytics taken from [HTML5 Boilerplate](http://html5boilerplate.com/).
