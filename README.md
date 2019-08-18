👋 [Available on Molkobain I/O!](https://www.molkobain.com/product/service-catalog-as-tree-by-default/)

# iTop extension: molkobain-portal-tree-service-catalog
* [Description](#description)
* [Compatibility](#compatibility)
* [Installation](#installation)
* [Configuration](#configuration)

## Support
If you like this project, you can buy me beer, always appreciated! 🍻😁

[![Donate](https://img.shields.io/static/v1?label=Donate&message=Molkobain%20I/O&color=green&style=flat&logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BZR88J33D4RG6&source=url)

## Description
Set the *tree* view as default for the service catalog of the user portal.

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-tree-service-catalog/master/docs/service-catalog-tree.PNG)

## Compatibility
Compatible with iTop 2.3+

## Installation
* Unzip the extension
* Copy the ``dist/molkobain-portal-tree-service-catalog`` folder under ``<PATH_TO_ITOP>/extensions`` folder of your iTop
* Run iTop setup & select extension *Portal: Service catalog as tree by default*

*Your folders should look like this*

![Extensions folder](https://raw.githubusercontent.com/Molkobain/itop-portal-tree-service-catalog/master/docs/mptsc-install.PNG)

## Configuration
### Standard portal
No configuration needed.

### Customized portal
If you customized the user portal, you will have to check/modify 2 things on the ``datamodel.molkobain-portal-tree-service-catalog.xml`` file of the extension, then run an iTop setup.
* Portal ID: If your portal ID is not ``itop-portal``, change it to your custom ID on line 4.
* Service catalog brick: If you are not targetting the standard service catalog, change the brick ID on line 6 (``services``) with yours.

## Licensing
This extension is under [AGPLv3](https://en.wikipedia.org/wiki/GNU_Affero_General_Public_License).
