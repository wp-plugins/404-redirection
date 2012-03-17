=== 404 Redirection ===
Contributors: wordpress_website
Tags: 404, redirect, redirects, redirector, server error, redirection
Requires at least: 2.0.2
Tested up to: 3.3.1
Stable tag: 1.3

Permanently redirect all 404's to the main blog URL. The primary purpose is to salvage Google PageRank (TM) from missing pages.

== Description ==

This simple plugin tracks and permanently redirects all 404's to the main blog URL. There may be several reasons why you might want to do this, but the primary purpose is to siphon Google Page Rank (TM) from missing pages to the homepage.

== Installation ==

The installation process is very basic:

1. Upload the unzipped plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it!

If you're having issues with the installation, you can read detailed instructions here: http://codex.wordpress.org/Managing_Plugins#Installing_Plugins

== Frequently Asked Questions ==

= Do I have to configure anything? =

Nope. The plugin is ready to go once you install it. However, the date and time is based upon the timezone setting under the General Settings section of WordPress, and NOT that of your server time. If you find that the 404 logs are not displaying the accurate time, you may need to adjust your timezone.

= Can I view a log of the 404's? =

Yes! The "404 Tracker" link is located under the "Tools" tab. Just to be clear, no 404's were actually generated. The log serves as a way of tracking the 404's that would have otherwise been created if not for this awesome plugin.

= Why do some rows within the "404 Tracker" tinted red? =

The red tinted rows serve as an easy visual reference for every 404 that occured within the past 24 hours.

= What does "URL Typo" in the Referring URL column mean? =

For instances when there is no referrer, it is assumed that the requested URL that generated a 404 was mistyped. 

= Can you give me some examples for why this plugin may be beneficial to me? =

Sure!

Example #1: If you acquire a pre-owned domain (that you intend to run WordPress with), you might not want to recreate every page that was part of the original site. Alternatively, you might not want to build an exhaustive list of 301's either. Enter the 404 Redirection plugin. Now, you'll never have to worry about not salvaging every drip of link-juice.

Example #2: Let's face it, having an exuberant amount of 404's is bad form. Search engines might consider your site "broken", and drop your rankings.

== Changelog ==

= 1.3 =
* Set a high priority of plugin execution.
* Switched to native WP redirection.
* Replaced depreciated 'site_url' function call.

= 1.0 =
* Created plugin 