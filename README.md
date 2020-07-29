# simple-scripts
A Collection of Simple Utilities I use for various tasks.
---
 - `deparametrizer`, probably my favourite, useful for debugging parametrized SQL queries. Does a fairly good job at recombinging a query string ("SELECT * from table where name = ? and age > ?") with a seperated list of parameters ("clarkbains,18")
 - `find-usb-device`, usefull to find the `/sys/bus/devices` path when you only have the output of `lsusb` to go on. I like to use it to poke around in the lighting files for various devices and see what I can do with them
 - `epoch`, finds datetime from epoch time. Used to be very helpful before I discovered MySQL has a built in function to do this
 - `desktop-run`, will run a system desktop app. If there are multiple different modes, it will display them all and let you pick which one to run

 These are all really basic, but get the job done for the most part
