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
	<google-analytics domain="example.com" code="UA-XXXXX-Y"></google-analytics>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`domain`   | *string*                  | `example.com`       | Your website domain
`code`     | *string* 				   			 | `UA-XXXXX-Y`        | Your Google Analytics tracking code


> See Google Analytics [official documentation](https://support.google.com/analytics/).

## History

* v0.0.6 November 19, 2014
	* Fix bug

* v0.0.5 October 4, 2014
	* Fix bower usage

* v0.0.4 July 1, 2014
	* Add bower

* v0.0.3 August 29, 2013
	* Changing to CDN Polymer API version

* v0.0.2 August 29, 2013
	* Changing Polymer API version and custom element name
* v0.0.1 August 28, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
