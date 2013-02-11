Swap File Plugin for unRAID v5
=============================

Hello,

I am proud to present the Swapfile plugin for unRAID v5.

If you are low on memory and would like to add a Swap File to your unRAID server this plugin makes it simpler.
The plugin enables creation/starting/stopping/changing of a Swap File on your unRAID server.

To install:
-----------
1. Initial Download of plugin at https://raw.github.com/theone11/swapfile_plugin/master/swapfile.plg (future updates can be done via the WEBUI)
2. Copy plugin to /boot/config/plugins on your flash drive.

3. Reboot unRAID server
 or
3. Install from command line:
  * installplg /boot/config/plugins/swapfile.plg
  * /etc/rc.d/rc.swapfile boot

4. Go to plugin WEGUI and change initial settings

The WEBUI is divided into 3 parts:
----------------------------------
1. Status Summary - Shows status of configured Swap File and plugin version.
2. Actions - Shows all possible actions available to the user depending on the status of the user's server.
   - Start/Stop/Restart Swap File.
   - Update plugin.
3. Configuration - Change settings of the plugin and Swap File.

Configuration Notes:
--------------------
1. Boot and Startup options - Change what happens during boot or installplg.
2. Swapfile settings - Change Swap File location, name, etc...
   - Default Swap File location is on the Cache Drive - Change it if you must.

Please comment on any problems encountered and any enhancements or missing features, that you would like added.
(Here if possible: https://github.com/theone11/swapfile_plugin/issues)

Enjoy the plugin  :)

Note:
-----
I used cofin's initial plugin (http://lime-technology.com/forum/index.php?topic=23515.0) and Joe L's unmenu swafile plugin as reference.

