# &lt;google-analytics&gt;

Web Component wrapper for Google Analytics code using Polymer.

> Maintained by [Cesar William](https://github.com/cesarwbr).

![Test on Google Analytics](http://f.cl.ly/items/3R1p2h2B462z1v0J0X3v/test-google-analytics.png)

## Installation

#### Using [Bower](http://bower.io):

1. Run this command from your project root:

	```shell
	bower install google-analytics
	```

2. Import the component by adding this to your HTML file:

	```html
	<link rel="import" href="bower_components/google-analytics/google-analytics.html">
	```

3. Start using it!

	```html
	<google-analytics code="UA-XXXXX-Y"></google-analytics>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`code`     | *string* 				   			 | `UA-XXXXX-Y`        | Your Google Analytics tracking code
`displayfeatures`     | *boolean* 				   			 | `false`        | Define the display features option


> See Google Analytics [official documentation](https://support.google.com/analytics/).

## History

For detailed changelog, check [Releases](https://github.com/cesarwbr/google-analytics-element/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
