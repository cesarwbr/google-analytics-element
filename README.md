# &lt;google-analytics&gt;

Web Component wrapper for Google Analytics code using Polymer.

> Maintained by [Cesar William](https://github.com/cesarwbr).

![Test on Google Analytics](http://test-analytics.herokuapp.com/images/test-google-analytics.png)

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/google-analytics.html">
	```

3. Start using it!

	```html
	<google-analytics domain="example.com" code="UA-XXXXX-Y"></google-analytics>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`domain`   | *string*                  | `example.com`       | Your website domain
`code`     | *string* 				   | `UA-XXXXX-Y`        | Your Google Analytics tracking code


> See Google Analytics [official documentation](https://support.google.com/analytics/).

## History

* v0.0.3 August 29, 2013
	* Changing to CDN Polymer API version

* v0.0.2 August 29, 2013
	* Changing Polymer API version and custom element name
* v0.0.1 August 28, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)