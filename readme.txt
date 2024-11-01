=== VestaCP/myVesta Dashboard Widget ===
Contributors: SS88_UK
Donate link: https://paypal.me/SS88/
Tags: vesta, vestacp, myvesta, disk stats, disk usage, bandwidth, bandwidth stats
Requires at least: 3.0.0
Tested up to: 6.7
Stable tag: 1.4
License: GPL2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds a widget to the Dashboard showing your VestaCP/myVesta accounts details. Requires an API key from the control panel.

== Description ==

A simple plugin that shows the following stats from your VestaCP account:

* Disk Usage
* Bandwidth Usage
* Database Usage
* Web Domain Usage
* Mail Account Usage

To generate an API key, first login to the server as root and run the command:

`/usr/local/vesta/bin/v-generate-api-key`

== Installation ==

Use the automatic installer via WordPress or download the plugin and:

1. Upload the plugin files to the `/wp-content/plugins/vestacp-dashboard-widget` directory
1. Activate the plugin through the 'Plugins' screen in WordPress
1. View the Dashboard to configure the settings.

== Screenshots ==

1. The initial screen when you view your dashboard.
2. The view after you have entered the correct API settings.

== Changelog ==

= 1.4 =
* Version bump + fixes

= 1.3 =
* Database variable was incorrect. Switched to 'U_DATABASES' instead.

= 1.2 =
* Option to Verify SSL. This was enabled by default, but a lot of VestaCP servers come with self-signed certificates.

= 1.1 =
* Fix. WP options set even if Vesta information was wrong.

= 1.0 =
* Initial release.

== Upgrade Notice ==

