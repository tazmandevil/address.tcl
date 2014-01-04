address.tcl
-------------
a simple address book written in tcl/tk
released according to the the GPL v.3 or later

This program is cross-platform, and has been tested on 
Windows 7 and Debian 7.

Dependencies
-----------------
This program requires Tcl8.5 or newer.
Linux folks can simply install tcl with their usual package manager.
Windows folks, go to 
http://www.activestate.com/activetcl
to download and install Tcl.

Install and Use
-----------------
Linux folks, stick the address.tcl in your path.
Windows folks, probably just make a desktop shortcut to the file.
If you have installed ActiveTcl, Windows should know what to do with it.

Make sure you properly set the address file directory.
Edit line 14 to do so.
For Windows users, if you simply make a Folder in your My Documents
folder called "addresses", you're all set.
Linux folks are probably smart enough to figure this out,
but make a directory somewhere, maybe ~/.addresses, or something, 
and change the directory under line 14 comments of address.tcl to reflect that directory.

Eventually I'll make a proper config for this thing so when you install it,
it writes a config file and uses that to set the directory.

The program should be fairly self-explanatory.
At the moment, it's very basic.
You can enter and save address information for your contacts.
You can search through the addresses.
Tags and notes are useful for adding extra information to facilitate searches.
If you open an existing address, change the name, and save it, 
you will now have a new file, with the new name, and the old file will still exist.
Sometimes that can be handy (someone gets married, 
and having a file under their maiden name is still useful), 
but sometimes it just means extra files and possible confusion.

Hack it up, make it better, have a go, if you think it needs improvement.
It's GPL code.

