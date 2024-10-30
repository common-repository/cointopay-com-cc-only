=== Cointopay.com CC Only ===
Contributors: Cointopay, therightsw, goshila
Requires at least: 3.8.1
Tested up to: 6.6.1
Stable tag: 1.3.2
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Extends WooCommerce with card payments gateway.

== Description ==
Card payment plugin for Wordpress WooCommerce, you can receive card payments into any currency and we can payout to your bank or you can keep it in crypto currency. Your choice.


*There are three prerequisites to get started:*
1. Please create an account on Cointopay.com, note down MerchantID, Security Code and Default Receive Currency as preferred checkout currency from the Account section (625 = EUR, 1 = bitcoin, 2 = litecoin etc.). Here is a complete list [https://tinyurl.com/ujfk7qy](https://tinyurl.com/ujfk7qy)
2. Install the Curl PHP Extension on your server
3. Install JSON Encode on your server

== Installation ==
1. Install zip file using WordPress built-in Add New Plugin installer (https://github.com/Cointopay/Wordpress-WooCommerce-CC-International/archive/refs/heads/master.zip)
2. Go to your WooCommerce Settings, and click the Checkout tab, find Cointopay CC Only.
3. In settings "MerchantID" <- set your Cointopay ID.
4. In settings "SecurityCode" <- set your Cointopay Security code (no API key required)
5. In settings "Default Receive Currency", this can also be found in the Account section of Cointopay.com. 625 for euro, 1 for bitcoin (default), 2 litecoin etc.
6. Save changes

*Tested on:*
WordPress 3.8.1 --> 6.6.1
WooCommerce 2.1.9 --> 9.1.4

*Notes:*
- Please note that the default checkout currency is Bitcoin, the customer can pay via other currencies as well by clicking the currency icon. Enable other currencies on Cointopay.com by going to Account > Wallet preferences and selecting multiple currencies e.g. Bitcoin, Litecoin, Ethereum, Ripple etc.
- We set a paid, on hold and cancelled, a partial payment stays on hold in WooCommerce. You will receive the partial payment in your account on Cointopay.com. Payment notifications via IPN messaging.

This plugin is using a https://cointopay.com backend integration, the Coinplusgroup S.R.O. Terms and conditions incl. privacy policy are applicable, please read the following information carefully: Terms: https://cointopay.com/terms and privacy policy: https://cdn-eur.s3.eu-west-1.amazonaws.com/Coinplusgroup-sro-Privacy-Policy.pdf. Any questions, please send to support@cointopay.com.

Thank you for being our customer, we look forward to working together.


== About Cointopay.com ==
We are an international crypto currency payment processor, meaning that we accept payments from your customers and make the funds available to you (incl. in form of fiat currency like euro). The direct integration with Wordpress Woocommerce provides you with a seamless payment experience while underlying dealing with diverse and complex blockchain technologies like Bitcoin, Ethereum, Neo, Dash, Ripple and many more. P.S. If you want your own crypto currency to become available in this plugin, we can provide that for you as well, Cointopay has been a technological payment incubator since 2014!

== FOR DEVELOPERS AND SALES REPS ==
PLEASE NOTE OUR AFFILIATE PROGRAM, YOU RECEIVE 0.5% OF ALL YOUR REFERRALS!
Create an account on Cointopay.com and send your prospects the following link: https://cointopay.com/?r=[yourmerchantid], you will receive mails when payments come into your account. 
