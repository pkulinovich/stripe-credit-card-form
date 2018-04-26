A simple credit card payment form for Stripe
==========================================
This a simple credit card payment form that does integrates with Stripe.js

See [Stripe.js and Elements](https://stripe.com/docs/stripe-js) for details.


## Installation

Clone repository and install dependencies
```sh
$ cd path/to/install
$ composer update
```

You need update index.php file and set your secret key
```php
$ \Stripe\Stripe::setApiKey("YOUR_SECRET_KEY");
```

Run Project
```sh
$ php -S localhost:8000 -t public
```

After this command you can copy this link and check on your browser:
```sh
http://localhost:8000/
```

## Preview
![GitHub Logo](img/preview.png)
Format: ![credit card payment form](url)