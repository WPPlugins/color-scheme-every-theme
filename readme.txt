=== Color Scheme every Theme ===
Contributors: danielauener
Donate link: http://www.danielauener.com/
Tags: color scheme, themes, customizer, css, customization
Requires at least: 3.4
Tested up to: 3.5
Stable tag: 2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

This plugin lets you change the entire color scheme of the current theme via the
theme customizer.

**4 steps to your customized color scheme**

1. The plugin extracts all the color settings from the css of your current 
theme. You trigger this process from the plugin settings page. All css files in 
your theme folder will be scanned.
2. After scanning the css, a template file gets created which will overwrite all
the color settings of the current theme with your custom colors.
3. You create a custom color scheme by following the instructions on the plugin
settings page.
4. You go to the theme customizer and choose your custom color scheme in the
'Color schemes' section.

A more detailed description is available on my blog [http://www.danielauener.com/color-scheme-every-theme/](http://www.danielauener.com/color-scheme-every-theme/). You are wellcome to give feedback/ask questions directly on my blog as well.

Read about the new features in version 2.0 here: [http://www.danielauener.com/plugin-update-color-scheme-every-theme/](http://www.danielauener.com/plugin-update-color-scheme-every-theme/).

There is even a github-repository on: [https://github.com/danielauener/color-scheme-every-theme/](http://github.com/danielauener/color-scheme-every-theme/)


== Installation ==

1. Upload the `color-scheme-every-theme` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'Settings/Color Scheme every Theme' page and generate a new color scheme. 
Follow the instructions adjust your functions.php.
4. Go to 'Appearance/Themes' and click on 'Customize' for your current theme.
5. Choose the color theme you just added and save the changes

== Frequently Asked Questions ==

== Screenshots ==

1. Theme customizer
2. Edit color schemes directly on the settings page

== Changelog ==

= 1.0 =
* Version 1.0 done

= 1.1 =
* Fixed a bug that resulted in a blank page after generating the color scheme - thanks to Stiaan for reporting the bug and Ulrich P for helping me to reproduce it!

= 2.0 =
* Tested for multisite environment
* Making schemes editable on the settings page
* Adding an option to make all color schemes available on the front-end, could 
be used for a javascript color scheme switcher

= 2.1 = 
* Fixed some minor bugs: settings link from plugins page, options.css added. Thanks, again,
Ulrich P!