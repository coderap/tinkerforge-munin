Munin Plugins for Tinkerforge
=================

Some Tinkerforge Plugins, they're using the Shell Bindings for Munin.
Easy to use, install and modify!


Install
=================
1) Download the Files in /examples

2) Move the Files on a Debian System to /etc/munin/plugins/

3) /etc/init.d/munin-node restart

Now wait, and you can see your monitored Values on the Group "Tinkerforge".


Other
=================
You should change the Munin Node Cronjob from 5 Minutes to 1 Minute, so you can
better Values, e.g. if you're using the Ambientlight with Serverroom Kit.


Thanks to
=================
Tinkerforge, for making a lot of GREAT Products including Support fast as Hell :-) 
