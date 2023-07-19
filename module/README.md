# Consistent Pricing

## Description
**Consistent Pricing** is an OpenCart extension that allows foreign customers to get the same gross prices as in the country (despite different VAT rates), in order to meet the requirements of the pricing policy in the EU.
Compatible with OpenCart 3.x versions.

An example of pricing for a store in the UK and a customer in Finland:

| Location | Price (excl. tax), € | VAT, % | VAT, € | Price (incl. tax), € |
|---|---|---|---|---|
| UK (store) | 10 | 20 | 2 | 12 |
| Finland (customer) | 9.6874 | 24 | 2.3226 | 12 |

## Features
* Uniform gross prices regardless of the shipping country VAT rate.
* Supports shipping methods, handling and low order fee modules.
* Compatible with the Journal 3 theme (via addon).
* Compatible with the Geo IP Tools.
* Does not modify system files (OCMOD).

## Live demo
* Extension [settings](https://demo.ocmod.space/a/admin/index.php?route=extension/module/consistent_pricing).
* [Store Front](https://demo.ocmod.space/a/.

## Additional information
Note that the extension does not determine the location of customers - it uses the address of registered customers, or shipping address (after it set in the cart). To determine customer countries, use third-party modules such as the excellent [Geo IP Tools](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=19084) module.

## License
[End-User License Agreement](../EULA.txt).

## Links
* **Consistent Pricing** on [**OpenCart Marketplace**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=44968).
* [**Consistent Pricing**](https://www.ocmod.space/consistent-pricing) web page.

## Related extensions
* Automatically move customers to more privileged customer groups when their spending reaches set thresholds using the [**Customer Loyalty**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42646) module.
* Use the [**Invite Code**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42632) module to allow customers to join other customer groups, for example to access discounts available to those groups.
* Automatically assign newly registered customers to a defined customer group by using the [**Default Registration Group**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42480) extension.
* Check the number of members in customer groups using the [**Customer Group Size**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42642) extension.
