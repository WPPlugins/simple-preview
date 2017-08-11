=== Simple Preview ===
Contributors: gabrielmcgovern
Donate link: http://www.dreamhost.com/donate.cgi?id=17157
Tags: simple-preview, draft, anonymous, public, post, preview, posts
Requires at least: 2.7
Tested up to: 4.7.3
Stable tag: 0.1.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

Enables you to give a link to anonymous users for public preview of a post before it is published.

Have you ever been writing a post that needs to be reviewed by someone who does not have access to log into your blog? This plugin generates a simple URL that can be given out for public preview.

Based on Public Post Preview 1.3 by Matt Martz and Jonathan Dingman. Unlike Public Post Preview, the Simple Preview can be accessed by more then one user. The 24hr  time limit has also been removed.
	
== Installation ==

= From wordpress admin screen =

1. Choose 'Plugins > Add New'.

1. Search for 'simple preview' and install! 

= From this page =

1. Click 'Download'

1. Upload the simple-preview folder to your /wp-content/plugins directory.

= Remember to: =
1. Activate the plugin through the 'Plugins' menu in WordPress or by using the link provided by the plugin installer

== Screenshots ==

1. It's just that simple!

== Upgrading ==

1. Click update from the WordPress plugin menu.

or

1. Click 'Download' on this page.

1. Deactivate the simple preview plugin through the Plugins menu in Wordpress Admin.

1. Upload the folder to your /wp-content/plugins directory, overwriting the previous version.

== Frequently Asked Questions ==

= How is this different then Public Post Preview? =

1. Completely removed the use of "nonce" variable. Posts marked preview are now accessible by multiple anonymous users. There is no longer a 24hr time limit.

1. Public_Post_Preview used the option variable as an array to store preview state - genius! However, it's use seemed backwards with an empty item == preview true. This logic was reversed so: simple_array[,,true,,true] now means that p=1 and p=4 have previews. This also allows for the preview to be turned off by default. 		

1. Removed extra variables for a cleaner URI: http://www.yourblog.com/?p=1502&preview=true

= How do I use it? =
1. Unlike public post preview, simple preview is not turned on by default. 

1. To enable simple preview for a specific post, check 'Allow Preview' and save the post. A simple URL will be created.

1. To disable, uncheck the box and save the post again

== Change Log ==

= 0.1.7 =
- Tested on 4.7+
- Moved from seperate meta box to the publish area. 
- Cleaned up the code a bit.
- Fixed bug: Regulare preview works again 
- Figed bug: Preview will remain active when a post is scheduled

= 0.1.6 =
- Tested on 3.6+. Cleaned up the code a bit.

= 0.1.5 =
- Initial release. Has been well tested.

= 0.1.4 =
- This version (and previous versions) were just used in testing. They weren't event submitted to http://wordpress.org/extend/plugins/
