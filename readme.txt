=== StoryChief WPML ===
Contributors: storychief
Tags: StoryChief, WPML
Requires at least: 4.6
Tested up to: 6.7
Stable tag: 1.0.10
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Add-on to map StoryChief languages with WPML Multilingual Plugin.

== Description ==

This add-on helps you to map StoryChief languages with WPML Multilingual Plugin.
This plugin requires the main plugin [StoryChief](https://wordpress.org/plugins/story-chief)

== Requirements ==

* WordPress 4.6 or higher
* [StoryChief](https://wordpress.org/plugins/story-chief)

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

== Frequently Asked Questions ==

== Screenshots ==

== Changelog ==

= 1.0.10 =
* improvement: tested up to WP 6.7

= 1.0.9 =
* improvement: tested up to WP 6.4

= 1.0.7 =
* Bugfix: Tag and category mapping could result in wrong ID's in some edge case.

= 1.0.6 =
* Feature: Map tags and categories on the source language term name

= 1.0.5 =
* Bugfix: Use wp_set_post_categories and wp_set_post_tags instead of wp_set_post_terms. Some events weren't triggered propely otherwise.
* improvement: tested up to WP 5.8

= 1.0.4 =
* Bugfix: connecting 2 articles broke if the post type was not 'post'.

= 1.0.3 =
* improvement: tested up to WP 5.6
* Improvement: Remove deprecated installation check

= 1.0.2 =
* Bugfix: image url uploads broken due to WPML adding trailing slashes to wp_upload_dir()

= 1.0.1 =
* improvement: tested up to WP 5.4

= 1.0.0 =
* improvement: tested up to WP 4.9
* Bugfix: Compatibility with StoryChief 1.x.x

= 0.1.0 =
First version

