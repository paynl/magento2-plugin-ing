
<h1 align="center">ING Checkout for Magento</h1>

All the payment options your Magento 2 store needs — in one plugin.

# Requirements
    Minimum PHP 8.1  
    Maximum PHP 8.4
    Magento minimum version: 2.4.4
    Magento maximum version: 2.4.8  

# Installation
#### Installing

In command line, navigate to the installation directory of Magento2

Enter the following commands:

```
composer require paynl/ingcheckout
php bin/magento setup:upgrade
php bin/magento cache:clean
```

The plugin is now installed


##### Setup

1. Log into the Magento Admin
2. Go to *Stores* / *Configuration*
3. Go to *Sales* / *Payment Methods*
4. Scroll down to find the ING Checkout Settings
5. Enter the API token and serviceID (these can be found in the ING Checkout Admin Panel --> https://mijnzakelijk.ing.nl/banking/ing-checkout/details
6. Save the settings
7. Enable the desired payment methods and set allowed countries
8. Save the settings

Go to the *Manage* / *Services* tab in the ING Checkout Admin Panel to enable extra payment methods.

# Support
Contact us: support.ingcheckout@ing.com
