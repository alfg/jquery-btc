work-in-progress

# jQuery-BTC
jQuery Bitcoin utilities.

## Usage

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="dist/jquery.btc.min.js"></script>
	```

3. Add markup
  ```html
  <div class="btc" data-usd="10.00">$10.00</div>
  ```

4. Call the plugin:

	```javascript
	$(".btc").btc();
	```

That's all! jquery-btc will fetch the current rates from Coinbase (via Firebase) and append
the conversion after your price.

## License

[MIT License](http://alfg.mit-license.org/) © Alfred Gutierrez
