# Aromicon Invoice Payment (M2)

> Magento 2 Module for Adding Invoice Payment to your store. Invoice can be created automatically and set to paid or unpaid. [Buy here](https://www.aromicon.de/magento-download-extensions-modules/de/magento-2-invoice-payment.html ':ignore')

## Installation
Installation is very easy and works straight forward, like any other Magento 2 Extension.
1. Adding Aromicon Composer Repository
	```
		nice ssh 
	```
1. Install Code
	```
		composer require aromicon/module-invoice
	```
1. Rebuild Store
	```
		php bin/magento setup
	```
1. Run Uprade Script
	```
		php bin/magento setup:upgrade
	```
1. Enable Caches (if caches where enabled before)
	```
		php bin/magento cache:enable
	```

?> Good Job. Installation is done!

## Configuration
After installation you will find the config section in "Stores > Configuration" "Sales > Payment Methods > Other Payment Methods"

## API
There's no API provided by this extension.

## Frequently Asked Questions

## Changelog

## Support