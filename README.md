# &lt;google-analytics&gt;

Web Component wrapper for Google Analytics code using Polymer.

> Maintained by [Cesar William](https://github.com/cesarwbr).

![Test on Google Analytics](http://f.cl.ly/items/3R1p2h2B462z1v0J0X3v/test-google-analytics.png)

## Installation

#### Using [Bower](http://bower.io):

1. Run this command from your project root:

	```shell
	bower install google-analytics --save
	```

2. Import Web Components' polyfill:
	```html
	<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
	```

3. Import the component by adding this to your HTML file:

	```html
	<link rel="import" href="bower_components/google-analytics/google-analytics.html">
	```

4. Start using it!

	```html
	<google-analytics code="UA-XXXXX-Y"></google-analytics>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`code`     | *string* 				   			 | `UA-XXXXX-Y`        | Your Google Analytics tracking code
`displayfeatures`     | *boolean* 				   			 | `false`        | Optional. Define the display features option
`pages`     | *array* 				   			 | `[]`        | Optional. The path portion of the page URL. Should begin with '/' like this '["/sample1", "/sample2"]'


> See Google Analytics [official documentation](https://support.google.com/analytics/).

## History

For detailed changelog, check [Releases](https://github.com/cesarwbr/google-analytics-element/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
