=== Monelib Officiel ===
Contributors: monelib
Tags: payment, monelib, protection
Requires at least: 4.5
Tested up to: 4.7.3
Stable tag: 1.4
License: Beerware
License URI: https://en.wikipedia.org/wiki/Beerware

Use your created account on our website "www.monelib.com" to protect pages or articles with the online payment solution.

== Description ==

The purpose of this plugin is to use your created account on our website "www.monelib.com" to protect pages or articles with the monelib online payment solution.

== Installation ==

You'll have to configure your Point of Sale as described in the admin section, you'll find it under "Monelib".
The gateway password has to be configured in the webmaster section of our website Monelib.

In the admin section, you can create protected zones with the 3 types of payment solutions that Monelib provides :
    - Payment by phone or SMS
    - Payment by Credit Card (one shot)
    - Payment by Credit Card (subscription)

When you edit an article or a page, you can use "monelib" short code instead of protecting the entire document.

Feel free to ask us if you have any question on contact@monelib.com
If you have any problem with this plugin, please report on contact@monelib.com with all the information that can help us to fix the issue.

== Changelog ==
 
= 1.0a =
* First release with one payment method

= 1.0b =
* Three payment methods

= 1.0c =
* Fixes on language issues
* Add shortcode monelib to protect few parts of documents
* Fixes mixed content issue (https vs http)
* Fixes problems with other plugins

= 1.0d =
* Add comments
* Add recommendations from wordpress.org before publishing

= 1.0e =
* Start session only if needed

= 1.1 =
* Multiple zone is possible in shortcodes separate with comma example : [monelib zone="1,2" solo="true,false"] Content [/monelib]

= 1.2 = 
* Add shortcodes [monelibDownload] and [monelibVideo] to protect content in a hidden folder
* Add shortcodes [monelibPre] to display content when the protected content has to be unlocked
* Remove full page/article based protection

= 1.3 = 
* Add language (fr_FR)
* Force language in front-end

= 1.4 =
* Add column in admin, remove the title "Protected by monelib"
