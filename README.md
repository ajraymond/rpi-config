rpi-config
==========
A dialog-based interactive configuration script for [Raspbian] [1] on the Raspberry Pi.

Disclaimer
----------
This script is still in a beta stage. Use at your own risks.

Pre-requisites
--------------
This tool requires dialog and [rpi-update] [2].

'dialog' is packaged with Raspbian and can be installed by running, as root:
`apt-get install dialog`

See [here] [2] for the installation instrutions of 'rpi-update'.


Instructions
------------
To install rpi-config, run this command as root:
`wget http://goo.gl/o23WG -O /usr/bin/rpi-config && chmod 755 /usr/bin/rpi-config`

The script can then be launched, using the following command as root:
`rpi-config`

Additional information
----------------------
Many options set by this script are detailed on the [eLinux] [3] web site. The description of many options is taken verbatim from there.

[1]: http://www.raspbian.org
[2]: https://github.com/Hexxeh/rpi-update/
[3]: http://elinux.org/R-Pi_Hub
