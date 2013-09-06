# WordPress Google CSE XML

This is a fork of [Google Custom Search Engine](https://github.com/ptz0n/wordpress-google-cse) using [Google Custom Search XML API](https://developers.google.com/custom-search/docs/xml_results?hl=en&csw=1). This version does not require a Google API key but does require a Google Custom Search Engine ID with a paid Business account. This is not another iframe embed or AJAX result listing plugin. Instead search results from your Google Custom Search Engine is served via WordPress search listing. No need to customize your theme or search box.

__You'll need to get a [Google Custom Search Engine ID](https://www.google.com/cse/) and upgrade to a paid Business account.__

## Dependencies

* WordPress 3.3

## Features

* Search results sorting by relevance
* Works with all post types
* Multisite &amp; network support

## Installation

1. Place the plugin (`google-cse/` directory) in the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enter and save your [Google Custom Search Engine](https://www.google.com/cse/) ID.
4. You're done, celebrate with a cup of coffee?

If you want to use images from the Google result in your search result (`search.php`) use `$post->cse_img` for image URL.

## Feedback and questions

Found a bug or missing a feature? Don't hesitate to create a new issue on [GitHub](https://github.com/rsrose21/wordpress-google-cse/issues) or contact me [directly](https://github.com/rsrose21).

## Credits

* [Ryan Rose](https://github.com/rsrose21)

## Original Credits

* [Jonas Nordström](https://github.com/windyjonas)
* [Andreas Karlsson](https://github.com/indiebytes)
* [Tom Ewer](https://twitter.com/tomewer)
* [Martel7](http://wordpress.org/support/profile/martel7)
* [Mike Garrett](https://github.com/MikeNGarrett)

## Changelog

### 1.0
* Updated to use Google XML API
