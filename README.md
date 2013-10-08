Munin Plugins for Tinkerforge
=================

Some Tinkerforge Plugins, they're using the Shell Bindings for Munin.
Easy to use, install and modify!

Currently are following Plugins included:

Temperature Bricklet 
PTC Temperature Bricklet
Ambilight Bricklet

Requirements
=================
tinkerforge shell bindings (found be here: http://www.tinkerforge.com/en/doc/Kits/ServerRoomMonitoring/ServerRoomMonitoring.html#simple-monitoring)

ethernet brick (or you modify the collect code to use usb)


Install
=================
1) Download the Files in /examples

2) Move the Files on a Debian System to /etc/munin/plugins/

3) Change the IP-Address in the Files AND (!!!) the IDs of the Bricks

4) /etc/init.d/munin-node restart

Now wait, and you can see your monitored Values on the Group "Tinkerforge".


Other
=================
You should change the Munin Node Cronjob from 5 Minutes to 1 Minute, so you can
better Values, e.g. if you're using the Ambientlight with Serverroom Kit.


Thanks to
=================
Tinkerforge, for making a lot of GREAT Products including Support fast as Hell :-) 
