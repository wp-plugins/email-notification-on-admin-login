=== Email notification on admin login ===
Contributors: Azumi93
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QKPPZSQYBU7KS
Tags: email notify on admin login, admin login notification, email notification
Requires at least: 3.0.1
Tested up to: 4.1
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

 Sends an email to a pointed email address when an admin user logs in

== Description ==

This plugin will send you an email every time a user logs in your website as an admin.
It displays the date the user logged in and their IP address.

Have fun!

www.dyulgerova.info

== Installation ==

How to install this plugin?

1. Upload `email-admin-notify` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= I am not getting an email when a user logs in as an admin =

That's because the default email address is the one you entered when you installed your WordPress
and you no longer use the email in question, or at least not too often.

= Can I change the email address the notifications are being sent to? =

Yes you can, but you must be careful not to mess things up. 

= I promise I won't mess things up, how do I change the email? =

Go to wp-content/plugins/email-admin-notify/config.php
In the file you will see a bunch of lines. Search for `define("ADMIN_EMAIL", "$admin_email");` 
and change "$admin_email" to whatever email you want.
For example define("ADMIN_EMAIL", "MY_AMAZING_EMAIL@AMAZING.COM");
That way all notifications will be sent to "MY_AMAZING_EMAIL@AMAZING.COM"
instead of the email you installed your WordPress with. 

= I messed things up, how can I fix everything? =

Pre-install and plugin and stop pretending to be a programmer.

= This is an awesome plugin, how can I thank Stefany? =

I will be very grateful if you put my website www.dyulgerova.info 
in your page.

== Changelog ==

= 1.0 =
