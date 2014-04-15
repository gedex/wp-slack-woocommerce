=== Slack WooCommerce ===
Contributors:      akeda
Donate link:       http://goo.gl/DELyuR
Tags:              slack, api, chat, notification, woocommerce, payment
Requires at least: 3.6
Tested up to:      3.8.1
Stable tag:        trunk
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html

Send notifications to Slack channels whenever payment in WooCommerce is marked as complete.

== Description ==

This plugin is an extension to [Slack plugin](http://wordpress.org/plugins/slack) that allows you to send notifications to Slack channels whenever payment in WooCommerce is marked as complete.

The new event will be shown on integration setting with text **When a payment in WooCommerce is marked as complete**. If checked then notification will be delivered once payment is marked as complete.

You can alter the message with `slack_woocommerce_order_status_completed_message` filter. The filter receives following parameters (ordered by position):

* `$message` &mdash; Default string of message to be delivered
* `$order` &mdash; Order object

**Development of this plugin is done on [GitHub](https://github.com/gedex/wp-slack-woocommerce). Pull requests are always welcome**.

== Installation ==

1. You need to install and activate both WooCommerce and [Slack](http://wordpress.org/plugins/slack) plugins first.
1. Then upload **Slack WooCommerce** plugin to your blog's `wp-content/plugins/` directory and activate.
1. You will see new event type with text **When a payment in WooCommerce is marked as complete** in integration setting. If checked then notification will be delivered once payment is marked as complete.

== Screenshots ==

1. Event option in integration setting
1. Your channel get notified whenever payment is completed

== Changelog ==

= 0.1.0 =
Initial release
