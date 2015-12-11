neutrino-php-client
===================
NOTICE: This client has been replaced with: https://github.com/NeutrinoAPI/NeutrinoAPI-PHP 

A PHP client for Neutrino API: https://www.neutrinoapi.com

For the comprehensive API documentation see: https://www.neutrinoapi.com/api/

**Examples:**

```php
<?php

require_once 'NeutrinoAPI.php';
$neutrino = new NeutrinoAPI();

// get IP info
$ipInfo = $neutrino->ipInfo("162.209.106.137", true);
echo $ipInfo['country'].PHP_EOL;

// convert currency
$conversion = $neutrino->convert(10, "USD", "NZD");
echo $conversion['result'].PHP_EOL;

?>
```

