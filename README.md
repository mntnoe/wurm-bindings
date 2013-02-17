wurm-bindings
=============

Keyboard bindings for Wurm Online

Base setup can be found at [/common/base](http://github.com/mntnoe/wurm-bindings/blob/master/common/base.txt).


Description
-----------

Read [Daray's Keyboard Guide](http://forum.wurmonline.com/index.php?/topic/76025-darays-keyboard-guide/) on the Wurm Online Forum for a description of this config.


Installation
------------

1. Download [wurm-bindings](http://github.com/mntnoe/wurm-bindings/archive/master.zip),
   and extract it to a temporary location.

2. Backup your `keybindings.txt` file.

3. Copy the `common/` folder into your Wurm installation folder.

4. Copy the files in `configs/daray/` into the folder of the config you wish to install
   this setup into. If your config name is `default` for instance, the files should go
   to `configs/default/`.

5. In Wurm, open your Console (default by pressing `F1`). Type the command `exec base.txt`.

6. Enjoy your new key binding setup!

*Note:* In order to load your tools into your toolbelt when switching modes, you need to
replace the tokens `item_id_here` with your items' ids in the mode scripts. Also remember
to remove the two leading slashes. Read the above linked guide to see how you determine 
your items' ids.

