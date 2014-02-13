## Shiving IE8

Modernizr runs through a little loop in JavaScript to enable the various elements from HTML5 (as well as abbr) for styling in Internet Explorer. Note that this does not mean it suddenly makes IE support the Audio or Video element, it just means that you can use section instead of div and style them in CSS.

Youll need to style these elements with [normalize.css](http://necolas.github.io/normalize.css/)
