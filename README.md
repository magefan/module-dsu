# Magento 2 Development Store Update by [Magefan](https://magefan.com/magento2-extensions)

[![Total Downloads](https://poser.pugx.org/magefan/module-dsu/downloads)](https://packagist.org/packages/magefan/module-dsu)
[![Latest Stable Version](https://poser.pugx.org/magefan/module-dsu/v/stable)](https://packagist.org/packages/magefan/module-dsu)

This [Magento 2 Blog module](https://magefan.com/magento2-extensions) allows you to easly update dev/stage database and media folder

## Requirements
  * Magento Community Edition 2.1.0-2.3.x or Magento Enterprise Edition 2.1.0-2.3.x
  * **IMPORTANT!** [Magefan Community Extension](https://github.com/magefan/module-community) >= 2.0.4 . Please install this extension first if you use installation via FTP.
        
## Features
  * Update Database Data
  * Update Media Files (product, WYSIWYG images)
  * Configure Skipping Some DB Tables
  * Anonimize Customer Data (GDPR compatibility)
  * Command Line and Web Interface
 

## Installation Instruction
```
 composer require magefan/module-dsu
 bin/magento setup:upgrade
 bin/magento setup:di:compile
 bin/magento setup:static-content:deploy
```


## Support
If you have any issues, please [contact us](mailto:support@magefan.com)
then if you still need help, open a bug report in GitHub's
[issue tracker](https://github.com/magefan/module-blog/issues).

Please do not use Magento Marketplace Reviews or (especially) the Q&A for support.
There isn't a way for us to reply to reviews and the Q&A moderation is very slow.

## Need More Features?
Please contact us to get a quote
https://magefan.com/contact

## License
The code is licensed under [EULA](https://magefan.com/end-user-license-agreement).

## Other Magefan Extensions That Can Be Installed Via Composer
  * [Magento 2 Blog](https://magefan.com/magento2-blog-extension)
  * [Magento 2 Auto Currency Switcher Extension](https://magefan.com/magento-2-currency-switcher-auto-currency-by-country)
  * [Magento 2 Login As Customer Extension](https://magefan.com/login-as-customer-magento-2-extension)
  * [Magento 2 Conflict Detector Extension](https://magefan.com/magento2-conflict-detector)
  * [Magento 2 Lazy Load Extension](https://github.com/magefan/module-lazyload)
  * [Magento 2 Rocket JavaScript Extension](https://magefan.com/rocket-javascript-deferred-javascript)
  * [Magento 2 CLI Extension](https://magefan.com/magento2-cli-extension)
  
