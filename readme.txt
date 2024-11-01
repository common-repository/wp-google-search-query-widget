=== WP Google Search Query Widget Wordpress Plugin ===
Contributors: Johannes Lauter
Donate link: http://www.lautr.com/wp-google-search-query-widget-wordpress-plugin
Tags: widget, google, keywords
Requires at least: 2.7
Tested: 2.9.2
Tested up to: trunk

Implements a Widget with your Top Google Search Querys 

== Description ==

This Plugin implements an easy configurable Widget which can display your top Google search querys (Keywords) and link it to your internal search like a tag cloud by accessing an Google Analytics account.
You can use its default font sizes or override them by the classes that are applied. It is recommended to have APC installed to cache the Google API requests but its not necessary.
It is written and currently maintained by <a href="http://www.lautr.com">Johannes Lauter</a> and uses the Google Analytics API PHP Class from <a href="http://www.electrictoolbox.com">Chris Hope</a>.

== Installation ==

Upload the directory 'wp-gquery-widget' directory in your Plugin directory.
Fill out your Google Analytics account data.
Select your project and fill out the necessary options in the back-end and that's all.

= For those with Sidebar Widget compatible themes =

Simply at the Widget in your Design > Widget Menu.

= For those without Sidebar Widget =

Open your themes' `sidebar.php` file if you have one and add `<?php wp_gquery_widget::widget(); ?>`

== Screenshots ==

1. This is the backend with some example settings 

