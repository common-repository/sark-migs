=== Sark Migs ===
Contributors: mycholan
Tags: Visa Mastercard gateway Plugin, Payment Gateway, MasterCard Internet Gateway Service, MIGS, Axis Bank, MIGS Payment Gateway Integration with woocommerce
Requires at least: 3.5.1
Tested up to: 5.4.2
Stable tag: 1.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extends WooCommerce with MasterCard Internet Gateway Service (MIGS)

== Description ==
This plugin enables MIGS payment gateway support for your WooCommerce sites. It Allows you to use MasterCard Internet Gateway Service or any other bank that uses MIGS ( like HSBC, Bendigo Bank, Axis Bank ... ) with the woocommerce plugin. 

It uses the redirect method, the user is redirected to MIGS payment gateway page so that you don't have to install an SSL certificate on your site.

== Installation ==
1. Ensure you have latest version of WooCommerce plugin installed ( 2.2 or above )
2. Unzip and upload contents of the plugin to your /wp-content/plugins/ directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Visit the WooCommerce settings page, and click on the Checkout tab.
5. Select the Sark Migs and click Save changes. 
6. Use the settings button to configure MIGS payment gateway.
6. On your MIGS setting page, check the Enable MIGS Payment Module check box.
7. Add your Merchant Id, Access Code and Secure Hash Secret.
8. Click Save changes.

== Screenshots ==
1. WooCommerce Checkout section's payment gateway setting page
2. Sark Migs setting page
3. MIGS payment option at Checkout page

== Changelog ==

= 1.5 =
* Invalid Digital Receipt Delivery URL - fix

= 1.4 =
* SHA256 support added

= 1.3 =
* vpc_OrderInfo param value fix
* cusrrency code & lang param added
* Fields added for Success & Failed message of transaction

= 1.2 =
* Order total rounding error fixed.

= 1.1 =
* Some minor optimization work done.

= 1.0 =
* First Public Release.



