# Consistent Pricing

## Description
**Consistent Pricing** is an OpenCart extension that allows customers to get the same gross prices as in the store located country, even if these countries have different VAT rates.
Compatible with OpenCart 3.x versions.

An example of pricing for a store in the UK and a customer in Finland:

| Location | Price (excl. tax), € | VAT, % | VAT, € | Price (incl. tax), € |
|---|---|---|---|---|
| UK (store) | 10 | 20 | 2 | 12 |
| Finland (customer) | 9.6874 | 24 | 2.3226 | 12 |


## Additional Information
Note that the extension does not determine the location of customers - it uses the address of registered customers, or shipping address (after it set in the cart). To determine customer countries, use third-party modules such as the excellent [Geo IP Tools](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=19084) module.

## Features
* Uniform gross prices regardless of the shipping country VAT rate.
* Supports shipping methods, handling and low order fee modules.
* Compatible with the Journal 3 theme (via addon).
* Compatible with the Geo IP Tools.
* Does not modify system files (OCMOD).

## Live demo
[Administration](https://demo.ocmod.space/a/admin/index.php?route=extension/module/consistent_pricing)  
[Store Front](https://demo.ocmod.space/a/)  

## License
[End-User License Agreement](../EULA.txt)  

## Download
[OpenCart Marketplace](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=44968)  

## Related extensions
[Invite Code](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42632) - allows customers to join other groups and get access to special prices or discounts available to this group.  
[Default Registration Group](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42480) - allows to specify default customer group to assign it for all new registered customers.  
[Customer Group Size](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42642) - allows to display customer quantity in groups.  
