# Consistent Pricing

## Description
**Consistent Price** is an OpenCart module that ensures customers see the same final price regardless of their country's tax rate. It automatically adjusts base price and tax so the total order price stays consistent.

This is especially useful if your store uses tax-inclusive pricing and you want to avoid price variations caused by different VAT rates across EU countries.

Compatible with OpenCart 3.x (PHP 7.x and above).

**Note**: The source code is encrypted for security reasons. For purchasing and licensing details, please refer to the OpenCart Marketplace link in the **Download** section below.

## Features
* Maintains uniform gross prices regardless of the destination country's VAT rate.
* Supports shipping, handling, and low order fee adjustments.
* Compatible with the Journal 3 theme (OpenCart 3.x.x.x).
* Does not modify system files (OCMOD).

The module does not determine the customer's location — it uses the registered customer's address or the shipping address (once set in the cart). If you need to detect customer locations, use third-party modules like the excellent [Geo IP Tools](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=19084) module.

## Restrictions
This module does not work and is not supported for stores using the following domain extensions: `.ru`,`.рф`,`.рус`,`.by`,`.бел`,`.su`.

## Live demo
* [Admin dashboard](https://demo.ocmod.space/a/admin/index.php?route=extension/module/consistent_pricing)
* [Storefront](https://demo.ocmod.space/a/)

## License
[End-User License Agreement](../EULA.en.txt)

## Download
[OpenCart Marketplace](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=44968)

## Related extensions
* Automatically upgrade customers to privileged groups when their spending reaches set thresholds using the [Customer Loyalty](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42646) module.
* Use the [Invite Code](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42632) module to let customers join specific groups, e.g., to access exclusive discounts.
* Automatically assign newly registered customers to a predefined group with the [Default Registration Group](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42480) extension.
* Track the number of members in customer groups using the [Customer Group Size](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42642) extension.
