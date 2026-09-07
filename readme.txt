=== Ocasio Disable Gutenberg ===
Contributors: ocas
Tags: disable gutenberg, classic editor, block editor, restore classic editor, editor
Requires at least: 6.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Restores the Classic Editor cleanly and prevents block editor CSS stylesheets from loading on the front end.

== Description ==

If you prefer the speed, simplicity, and reliability of the original WordPress Classic Editor (TinyMCE), the Gutenberg block editor gets in the way. It slows down post editing and loads unnecessary block stylesheets on your public pages.

Ocasio Disable Gutenberg replaces the block editor with the familiar Classic Editor on all posts, pages, and custom post types. It also dequeues core block library CSS styles (`wp-block-library`) so your front end stays fast and lightweight.

You get a clean writing interface with zero setup.

= Features =

* **Restores Classic Editor:** Replaces the block editor interface with TinyMCE across all post types.
* **Dequeues Block Stylesheets:** Stops WordPress from loading unused block library CSS on your front end.
* **Compatible with Page Builders:** Works seamlessly alongside page builders without block editor conflicts.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript.
* **Instant Dashboard Switch:** Turn the feature on or off in one click directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-disable-gutenberg` folder to your `/wp-content/plugins/` directory, or install it directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Go to **Ocasio Plugins -> Dashboard** in your sidebar to toggle your settings.

== Frequently Asked Questions ==

= Will my existing content be affected? =
No. Your existing post content remains completely safe and editable in the Classic Editor.

= Can I switch back to Gutenberg if needed? =
Yes. Just flip the toggle to OFF on the Ocasio Plugins dashboard or deactivate the plugin.

== Changelog ==

= 1.0.0 =
* Initial public release.
