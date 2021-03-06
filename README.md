# addrwatch
## A Bitcoin Cash address watcher and notifier

Addrwatch is a script that can be installed on your webserver or run from your personal computer to keep watch on a list of Bitcoin Cash addresses for balance changes.

### How to Use?

Place the executable script and library file in a convenient location. Be sure to copy `addrwatch.cfg.sample` to either `addrwatch.cfg` or `$HOME/.addrwatch.cfg` and edit it to your preferences.

Start the script via your preferred method (direct execution, cron, systemd, your desktop environment's autostart capabilities etc.).

If running `addrwatch` via systemd, be sure to edit `addrwatch.service` as well and place it where relevant (see the comments in that file for reference).

### Other Notes

This program is free software, released under the Apache License, Version 2.0. See the LICENSE file for more information.

The program's canonical project page resides at https://simonvolpert.com/addrwatch/

I gratefully accept appreciation for my work in material form at __[bitcoincash:qq8vjvf946u8ghxklt792ugc48uejpfgpvzjhwajwt](bitcoincash:qq8vjvf946u8ghxklt792ugc48uejpfgpvzjhwajwt)__.

