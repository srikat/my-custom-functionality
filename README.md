# My Custom Functionality #

A basic starting point for a custom plugin to load CSS and JS files in WordPress.

## Installation ##

1. Click on the `Download ZIP` button at the right to download the plugin.
2. Go to Plugins > Add New in your WordPress admin. Click on `Upload Plugin` and browse for the zip file.
3. Activate the plugin.

## Usage ##

CSS:

1. Connect to your server using a FTP client and navigate to the plugin directory.
2. Upload the files you want to use/load in the corresponding directories inside the `assets` directory.
3. Edit `plugin.php` and use the commented sample code as an example to add enqueue or other site-specific code. While there you may also want to edit the plugin's header with your name, plugin and author URLs etc.

## Changelog ##

### 1.0.0 ###
* Initial Release
