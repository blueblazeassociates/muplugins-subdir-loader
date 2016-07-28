MU Plugins Subdirectory Loader
============================

Enables the loading of WordPress plugins sitting in mu-plugins (as folders)

For more information about this plugin, read this blog post:
https://richardtape.com/2014/08/22/composer-and-wordpress-mu-plugins/

The original code is located in this Gist:
https://gist.github.com/richardtape/05c70849e949a5017147

How to install
--------------

Because of the way Composer works, this plugin has to be installed manually.  It is for this reason, also, that this plugin has its Composer *vendor* directory stored in the repository.

To install:

1. Copy the file *muplugins-subdir-loader.php* into your WordPress mu-plugins folder.
2. Copy the *muplugins-subdir-loader__vendor* folder into your WordPress mu-plugins folder.
3. The plugin will auto-activate.

Note: The Composer *vendor* directory has been renamed to *muplugins-subdir-loader__vendor*.  This is to avoid any name collisions with anything else.
