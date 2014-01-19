lirc
====

My LIRC config. Allows control of monitor brightness and smplayer using my tv's remote.

Requirements
====

IR reciever, I suggest MCE.
IR remote

Guide
====

1. Install and Configure lirc (sudo apt-get install lirc)
2. Ensure remote is working with irw or cat /dev/lirc#
3. Use IRRecord to create a configuration file for remote
4. Take configuration and paste into your lircd.conf.mceusb (will be lircd.conf.<manfac>)
5. Configure irexec by using the key names which you named in IRRecord and set them to do things.

