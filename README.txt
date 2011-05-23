Module: GoSquared LiveStats
Author: Aaron Parker <http://drupal.org/user/881678>

Summary
=======
The official GoSquared LiveStats for Drupal Module to integrate the GoSquared Tracking Code into your Drupal site.

This plugin allows site owners to easily integrate their GoSquared Tracking Code into their Drupal site without having to change any source code or theme files.

This enables you to monitor your Drupal site's traffic in real-time with LiveStats and Trends, the real-time analytics platform.

To use LiveStats and Trends on your Drupal site, simply download this plugin and sign up for a free account at https://www.gosquared.com/plans/

Installation
============
	1. Sign up to LiveStats for free at https://www.gosquared.com/plans/
	2. Extract the module (If you haven't already done so) to a temporary folder on your computer.
	3. Upload all of the files from the archive to `site-root/sites/all/modules/livestats`. You may need to create the modules and livestats folders if they don't already exist.
	4. Go to the administration pages of your Drupal installation and go to `Administer -> Site Building -> Modules`. From this page you can enable the module under the `Other` modules section at the bottom of the page.
	5. Go to the modules's configuration page (`Administer -> Site Configuration -> LiveStats`) and enter your account code, which can be found in the tracking code tab of the LiveStats Settings screen at https://www.gosquared.com/settings/ 

Configuration
=============
Once you have enabled the module and entered your account code on the configuration page (`Administer -> Site Configuration -> LiveStats`) then there are a few more options to configure to get the module working exactly how you want it to. The options available are described below:

= Display Users As =
This option allows you to select if you want user identifiers passed to LiveStats so that you can see who actual users are in LiveStats if they are logged in, as well as how you want them to be displayed. There are 3 options:
	`Off` - This is self-explanatory, an identifier of logged in users is not passed to LiveStats and everyone is shown by their LiveStats ID
	`User ID` - This turns the feature on and passes a users ID number, as stored by your Drupal installation, to LiveStats and sets the ID of that visitor as the User ID. This can be useful for support purposes.
	`Username` - This turns on the feature and passes the username of the logged in visitor to LiveStats and sets the LiveStats ID of that visitor to their username. This is useful to see who is on your site as well as to provide support and more detailed analytics.

FAQ
===
= Do I need a GoSquared account for this module to work? =
You'll need to sign up for LiveStats at https://www.gosquared.com/plans/ to make use of this module. If you're already using LiveStats, you'll simply need your Account Code (which can be found in the Tracking Code tab of the LiveStats Settings screen) to make use of this module.

= I don't have an account code. How do I get LiveStats? =

Check out LiveStats at http://www.gosquared.com/livestats/ and sign up for an account.

= Where can I find my Account Code? =

Sign in to LiveStats and go to the Site Manager, then click on the "Tracking Code" tab.

= I can't get this thing to work. Where can I contact you? =

Wing us an email at http://www.gosquared.com/contact/ or check out support documentation at http://www.gosquared.com/support/

Contact
=======
Website:      http://www.gosquared.com/
Support Site: http://www.gosquared.com/support/
Contact Form: http://www.gosquared.com/contact/