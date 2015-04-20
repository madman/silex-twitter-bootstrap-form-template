silex-twitter-bootstrap-form-template
=====================================

Adding Bootstrap3 from Twitter to your Silex forms without I18n support

Based in the Bootstrap Bundle
https://github.com/braincrafted/bootstrap-bundle/

### Install

1. Register Twig provider:

```php
$app->register(new Silex\Provider\TwigServiceProvider(), array(
	'twig.path' => __DIR__.'/views',
));
```

2. Copy ``form_div_layout.html.twig`` file into ``__DIR__.'/views'`` directory.

3. Done.
