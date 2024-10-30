=== Kashing Payments for WordPress ===
Contributors: kashingonline
Tags: kashing, kashing payments, payment gateway, payment technology, smart payment
Requires at least: 4.0
Tested up to: 5.6.2
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Kashing allows you to easily integrate Kashing Smart Payment Technology with your WordPress website.

== Description ==
Start accepting secure card payments instantly with the Kashing plugin on your WordPress website. The plugin works across all browsers and with desktop, tablet and mobile devices. It’s so quick and easy to set up that you can do it yourself in no time. 

All the transactions are logged though your Kashing membership account and are available for you to view and search anytime. 

Never miss out on an online sale again.

Do you sometimes need to sell things face-to-face as well? Have a look at the Kashing Smart App and ditch your old fashioned card reader.

**Note:** This is a standalone Kashing Smart Payment Technology integration plugin. No other plugins are required.

**Plugin Features**

1. Integrate your Kashing Smart Payment Technology account with your WordPress website and allow your site visitors & clients to pay directly on your website.
2. Build unlimited payment forms - each with a different transaction amount and description - so you may easily recognise them in your Kashing transaction history.
3. Easily place payment forms anywhere on your website using simple shortcodes (shortcode generator included).
4. Debug and test the integration with a convenient \"Test Mode\" before you go live.
5. Easily change the transaction currency.
6. Translation ready.
7. Fully customize the payment failure and success pages.
8. Four layers of form data validation.

== Installation ==

**Automatic Installation**

1. When you are logged in to your WordPress dashboard, navigate to the Plugins menu.
2. Click Add New button.
3. In the search field, type Kashing and click Search Plugins.
4. After you find our plugin in the search results, click on it.
5. In the popup window, you will see plugin details along with the Install Now button. Click it.
6. When the plugin installation finishes, activate it. You will see a new side menu item: Kashing.

**Manual Installation**

1. First, download the plugin files by clicking the blue Download button located at the top right of this page.
2. Log in to your WordPress dashboard and navigate to Plugins menu.
3. Click Add New button.
4. Click Upload Plugin button.
5. Click Choose file button and select the plugin .zip file you downloaded in Step 1. When the file is selected, click Install Now button.
6. When the plugin installation finishes, activate it. You will see a new side menu item: Kashing.

**Plugin Configuration**

1. Navigate to Kashing / Settings menu (located in your WordPress admin dashboard, in the sidebar navigation).
2. Click the Retrieve Your Kashing API Keys button - that will take you to the latest version of Kashing documentation where you will be explained how to retrieve the plugin configuration data. 
3. After you receive the configuration data in Step 2, fill all 4 fields in the Configuration tab: Test Merchant ID, Test Secret Key, Live Merchant ID, Live Secret Key. The first two are going to be used only if the Test Mode is enabled. When you're done, click Save Changes button.
4. For test purposes, it is recommended to use the Test Mode.

**Changing the Currency**

1. Navigate to Kashing / Settings menu and click the General tab.
2. Choose your desired currency from the Choose Currency dropdown menu.

**Payment Success & Failure Pages**

By default, upon plugin activation, Kashing automatically creates two plugin related pages: *Payment Success* and *Payment Failure*. They are being automatically assigned in Kashing / Settings / General tab. You may change those pages content as you wish. You may, of course, set them to be any other page. 

**Creating a Payment Form**

1. Navigate to the Kashing menu and click Add New Form button.
2. Enter the form title and fill out the required fields: Amount and Description.
3. When you're done, save the form by clicking the Publish button on the right.

**Inserting a Payment Form**

1. Edit the page or post you wish to insert the payment form on.
2. Right above the WYSIWYG content editor (next to the Add Media button), you will find Add Kashing Form button. Click it.
3. A popup window will appear where you will be presented with a dropdown list of payment forms you previously created.
4. Choose the one you need and click the blue OK button.
5. A form shortcode will be automatically inserted into your page/post content in a form like: [kashing_form form_id="XX"] where XX is a unique ID of that particular form.
6. Save your page/post.


== Frequently Asked Questions ==
= How to install the plugin? =
Please visit the Installation tab of this plugin page for extensive installation instructions.
= How to configure and use the plugin? =
Please visit the Installation tab of this plugin page for extensive plugin instructions.
= Are there additional paid features? =
No, there are not. You receive all features without any additional fees. There are no plans for a paid plugin version.


== Changelog ==

= 1.1.0 =

* Fixed payment form

= 1.0.4 =

* ...

= 1.0.3 =

* ...

= 1.0.2 =

* Screenshots and description update.


= 1.0.1 =

* Screenshots update.


= 1.0.0 =

* Plugin release!


== Screenshots ==

1. Payment Form view on a website frontend. Form styling is inherited from the theme currently in use (here Twenty Fifteen theme).
2. Kashing Payment Gateway your site visitors are redirected to upon filling out the form. After the payment is processed, they are being redirected back to your desired website.
3. Transaction Approved message in the Kashing Payment Gateway. After clicking Continue, person is redirected back to your website (in this case a Success page).
4. Payment Success page with some basic content and additional transaction details displayed to a site administrator (useful for testing and debugging). 
5. Kashing plugin configuration page.
6. Kashing plugin general settings page.
7. Payment form creation page.
8. Adding a payment from to a page/post using a simple shortcode generator.
