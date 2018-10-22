# Vidyard Wordpress Plugin

Adds oEmbed support for Vidyard players to Wordpress.

Will automatically convert the following Vidyard URLs into a video when editing a Wordpress site:
- `http(s)://embed.vidyard.com/share/PLAYER_UUID`
- `http(s)://play.vidyard.com/PLAYER_UUID`
- `http(s)://*.hubs.vidyard.com/watch/PLAYER_UUID`

To give the player a specific width or height, enclose the URL in an `[embed]` tag:

`[embed width="123" height="456"]https://embed.vidyard.com/share/PLAYER_UUID[/embed]`

___

### Installation

1. Create a `vidyard-wordpress-plugin` directory in `/wp-content/plugins/`.
2. Copy `vidyard-wordpress-plugin.php` into the `/wp-content/plugins/vidyard-wordpress-plugin` directory.
3. Open the `Plugins` menu in WordPress to activate the plugin.


*Visit the [Vidyard Knowledge Center](https://knowledge.vidyard.com/hc/en-us/articles/360010000393-Using-oEmbed-for-Vidyard-players) for more details.*
