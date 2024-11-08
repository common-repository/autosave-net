=== AutoSave Net ===
Contributors: majick
Donate link: http://wordquest.org/contribute/?plugin=autosave-net
Tags: autosave, auto save, autosave net, autosave manager, quicksave, content backup, content save, draft
Author URI: http://dreamjester.net
Plugin URI: http://wordquest.org/plugins/autosave-net/
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires at least: 3.0.0
Tested up to: 5.6.0
Stable tag: trunk

Auto-saves on steroids! QuickSave Timed Backup of your Post Content while writing. Compare and Restore QuickSave backups metabox.

== Description ==

AutoSave Net was built to catch your content from being lost as you are writing or saving it. Sometimes you get a disconnect or timeout on clicking Save or Update... or you get the dreaded "Are you sure you want to do this screen?" and lose your work... No more! Simply install the plugin and it will be there for you - when you really need it!

[AutoSave Net Home](http://wordquest.org/plugins/autosave-net/)
[Support Forum](http://wordquest.org/support/autosave-net/)

AutoSave Net adds a timed QuickSave Backup via AJAX for just your post content (not metadata) that saves your work regularly, and lets you easily compare your saved content with the Pageload or Autosave content using the inbuilt WordPress visual difference function. This means you can quickly and easily see your latest content and restore it without hassles. Why lose or rewrite any more sentences?

You can also control if, when and how often the QuickSave Backup is done on a post by post basis via the post metabox, or using the Admin screen, adjust which post types you want the QuickSave Backup to run for.

The QuickSave Backup works independently and side-by-side the inbuilt WordPress AutoSave, but the AutoSave Net plugin also allows you to modify the in-built WordPress AutoSave Options:

* Change the WordPress AutoSave backup interval
* Disable WordPress AutoSave entirely if you like
* Limit Number of Post Revisions stored for each post

[AutoSave Net Home](http://wordquest.org/plugins/autosave-net/)
[Support Forum](http://wordquest.org/support/autosave-net/)


== Installation ==

1. Upload `autosave-net.zip` via the Plugins upload page.
1. Activate the plugin through the 'Plugins' menu in WordPress
1. QuickSave metabox will now be active for all post types.
1. You can adjust the post types from the Settings screen.


== Frequently Asked Questions ==

= How do I use this plugin? =

A metabox is added to post writing screen (below the post content box.) Be sure to save an initial draft so that the QuickSave timer can start. Timer controls are available for adjusting the backup timer if you wish. By default the content is Quicksaved every minute. If the plugin finds a Quicksaved copy of the post content on pageload you will see an alert box at the top of the screen when you load the page. 

= How do I access or compare the QuickSave backup content? =

Scroll down to the QuickSave metabox. There you will find buttons to show/hide the latest QuickSaved content as well as the content from pageload. You can compare these to the current content by clicking the compare buttons to show the line-by-line visual comparison (similar to the WordPress revision comparison.) From there you can restore the QuickSaved content if you wish.


== Screenshots ==

1. A screenshot of the QuickSave metabox.
1. A screenshot of the QuickSave comparison box.
1. A screenshot of the AutoSave Net admin screen.


== Changelog ==

= 1.3.4 =
* Update to Plugin Panel 1.1.8
* Update to WordQuest Helper 1.7.8
* Update to Freemius SDK 2.4.1
* Improved to WordPress Coding Standards
* Changed edit screens setting to filter
* Fix to Autosave Interval override
* Fix to recheck post type revision support
* Added string output sanitization
* Added month output translations

= 1.3.3 =
* Update to Freemius SDK 1.2.2.9
* Update to Wordquest Helper 1.6.9
* Improved get filtered plugin settings

= 1.3.2 =
* Hotfix for default function typo

= 1.3.1 = 
* Update to Freemius SDK 1.2.1.5
* Update to Wordquest Helper 1.6.6
* Added fallback to default options
* Fix to empty settings warnings
* Added activation welcome message

= 1.3.0 =
* Update to Wordquest Helper 1.6.5
* Change plugin_dir_url usage to plugins_url
* Added settings validation

= 1.2.5 = 
* Update to Freemius Library
* Added Translation-ready Wrappers
* Added Dashicons / Colour Icons Option
* Fix to Comparison View Table Layout
* Compact Plugin Options to Single Option
* Added Auto-Filtering to Plugin Options
* Fix to Notice Screens Save Option

= 1.2.0 = 
* Public Release Version
* Added WordPress AutoSave Options
* Added WordQuest integration
* Added Freemius features

= 1.1.0 =
* Beta Version
* Added Quicksave tool menu icons instead of button text
* Added disable/enable for this post button

= 1.0.0 =
* Development Version


== Other Notes ==

[AutoSave Net Home](http://wordquest.org/plugins/autosave-net/)

Like this plugin? Check out more of our free plugins here: 
[WordQuest Alliance](http://wordquest.org/plugins/ "WordQuest Alliance Plugins")

Looking for an awesome theme? Check out my child theme framework:
[BioShip Child Theme Framework](http://bioship.space "BioShip Child Theme Framework")

= Support = 
For support or if you have an idea to improve this plugin:
[AutoSave Net Support](http://wordquest.org/support/autosave-net/ "AutoSave Net Support Quests")

= Contribute = 
Help fund support, improvements and log priority feature requests by a gift of appreciation:
[Contribute to AutoSave Net](http://wordquest.org/contribute/?plugin=autosave-net)

= Development =
To aid directly in development, please fork on Github and do a pull request:
[AutoSave Net on Github](http://github.com/majick777/autosave-net/)
