# rc.d

This folder is meant for user startup scripts.
Originally these where placed in the /etc/rc.* location and loaded through rc.local.

rc stands for `Run Commands`.

The synology user systems takes this to the next level. Due to DSM upgrade, updates,
configuration can be lost. Within rc.d you place your user scripts. If you make any new scripts, you can deploy then with `usystem update rc`.
