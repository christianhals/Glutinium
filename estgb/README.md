estgb
=====

Simply Sender TeleGram Bot based on telebot


License
=======

This sources is free software; you can redistribute it and/or modify it under the terms of
the GNU Lesser General Public License as published by the Free Software Foundation;
either version 2.1 of the License, or (at your option) any later version.

You should have received a copy of the GNU Lesser General Public License along with this
script; if not, please visit http://www.gnu.org/copyleft/gpl.html for more information.


Compile
=======

`sudo apt-get install libcurl4-openssl-dev libjson-c-dev`

`gcc -L/usr/lib/x86_64-linux-gnu/ -I./ -I/usr/include/curl -I/usr/include/json-c -o estgb estgb.c telebot.c telebot-core.c telebot-parser.c -ljson-c -lcurl`

Usage
=====

`Command line interface: estgb <command> <parameter> [options]`

More info for use estgb on OpenWRT routers you can see [here (Russian)](http://zftlab.org)


Links
=====

* [Original idea and project on GitHub from Denis Dugushkin](https://github.com/denzen84/sstgb)
* [C Library for Telegram bot API that uses json-c and libcurl on GitHub](https://github.com/smartnode/telebot)


