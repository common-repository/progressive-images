=== Progressive Images ===
Contributors: jacobarriola
Author URI: http://jacobarriola.com
Tags: performance, images
Requires at least: 4.7.4
Tested up to: 4.7.5
Stable tag: 0.0.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Load post thumbnail after page has loaded.

== Description ==
Load your post thumbnail after all of the page content and assets have been loaded.

== Installation ==
1. Upload the plugin to wp-content/plugins
2. Activate the plugin in WordPress.
3. Enjoy!

== Issue reporting ==
I built this plugin for the 2017 Orange County WordCamp plugin contest, so I won't be actively maintaining this project.

Probably best to fork this repo on [GitHub](https://github.com/jacobarriola/wordpress-progressive-images) and adjust it to your use case.

== Filters ==
View the repo on [GitHub](https://github.com/jacobarriola/wordpress-progressive-images) to view available filters.

== Changelog ==
= 0.5 =
* Add class on image parent after image loads. This helps in the event there are
more than one images on a page.

= 0.4 =
* Remove background color once an image loads [#1](https://github.com/jacobarriola/wordpress-progressive-images/issues/1)
* Fix how aspect ratio is calculated

= 0.3 =
* Drop functionality on images in post content. Too many conflicts with oEmbeds.

= 0.2 =
* Add filters

= 0.1 =
* Init

== Upgrade Notice ==

= 0.3 =
This version drops support for images in post content.
