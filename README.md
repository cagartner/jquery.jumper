# jQuery Jumper

### Install

Download package or install with bower:

	```
	bower isntall cagartner/jquery.jumper
	```

## Usage

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="dist/jquery.jumper.min.js"></script>
	```

3. Call the plugin:

	```javascript
	$("#input").jumper({
		equals: 2,
		target: '#input2'
	});
	```