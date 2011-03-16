=== LogMyTrip ===
Contributors: johnwaters, frsh, mdawaffe, automattic
Tags: travel, adventure travel, maps, google map, route maps, trip, travel, journey, route
Tested with Wordpress version: 3.1
Donate link: http://www.LogMyTrip.co.uk
Tags: travel, adventure travel, maps, google map, route maps, trip, travel, journey, route
Requires at least: 2.6
Tested up to: 3.1
Stable tag: trunk

Posts show up on a Google map as points on a route in date order.
Just add the shortcode [logmytripmap] to a page to see your map appear.

== Description ==

This plugin allows WordPress users to geotag their posts by upload of geotagged images or via the Edit Post page.
Photo's containing EXIF location data will be automatically geolocated, other points can be geolocated via a Google map.
Add the shortcode [logmytripmap] to a Wordpress page to see your map appear.

Geolocated posts show up on a Google map as points on a route in date order.
Hovering over the address of individual posts reveals a map of the exact location.
Clicking on a point icon can show a picture taken at that location if one is attached to the post. 
See <a href="http://www.LogMyTrip.co.uk">www.LogMyTrip.co.uk</a> for more info.

== Installation ==

1. Upload the 'logmytrip' directory to the '/wp-content/plugins/' directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add photo's to your blog either directly into your text or as attachments. Photo's containing EXIF location data will be automatically geolocated.

== Frequently Asked Questions ==

Q.Does the LogMyTrip plugin work with the Geolocation plugin?
A.The LogMyTrip plugin works with, but does not require, the Geolocation plugin.

Q.Can I upload pictures directly from my mobile and have them show up on a LogMyTrip map?
A.You can upload your pictures using Wordpress for iPhone, Android, Blackberry or Nokia. Geolocate your post using these apps and then it will show up on a LogMyTrip map.

Note: This plugin plots ALL posts that have associated geoloation information in date order for the default (post_author = 1) user. 
Points without geolocation data, or for other users, will not be plotted. However, you can switch to a different user by creating a cookie 
called 'tid' on the root of your site with a value equal to the ID required; e.g. Cookie: tid=4 for post_author 4.

== Changelog ==

1.6 Initial non beta release in plugin form.

== Upgrade Notice ==

To upgrade, simply overwrite the existing logmytrip directory with the newer files

== Screenshots ==

screenshot.jpg

