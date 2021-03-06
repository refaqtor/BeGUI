File: ResEDgarPPC.zip
Author: Ed Musgrove
Be Dev #2076
Release Date: 22 March 1999
Compatibility: PPC R4
Location: Utilities
Description:

Program Name: ResEDgar
Version: 1.1.0
date: 22 March 1999

ResEDgar is a GUI string resource editor. It is shareware, the cost is on a
sliding scale, if you find use for it, send me at least $1. USD (yeah, that is
one US dollar), but no more than $10. USD, pay what you can afford. Send cash
only, in US dollar bills to:
Ed Musgrove
12770 Olalla Valley Rd SE
Olalla  WA  98359-9701 USA

ResEDgar is my premiere application using BeGUI, which has now become a shared
library for both PPC and x86. You may change the resource strings in any
program (or library) which has them using ResEDgar. The next time you run the
changed program, the new strings will be used. If the author of the program
has made proper provisions, any gadgets will re-size themselves to fit the
changes, as will the displays for text which may have been changed.

ResEDgar itself has string resources, so you may use it to edit itself! Run
ResEDgar from a Terminal or from the Tracker, select the gadget labeled
"Load", use the file panel to choose an application (or library) file which
contains string resources. ResEDgar will inspect the chosen file and let you
know if it has no string resources, if it has any, a new window will open
giving access to all the strings. On the left will be the original string for
reference, on the right is a text box which allows you to 
make any changes you desire.

Some resource strings are more than one line long, if this is the case,
ResEDgar shows only the first line in the reference, but allows you to edit
the whole thing in the text box. In most cases, it is wise to keep single line
strings as single lines. Multi-line strings may usually have fewer or more
lines.

When you have made all changes to your satisfaction, select the "Save" item
from the editor window's menu (or from the title window's menu or gadget). You
may go on to edit more files or quit at any time. If you quit without saving,
no changes will be made in the file.

I have included a small application which has string resources and must be run
from a Terminal. It is called Resourceful, and simply prints my name out when
run. Run it once, then edit it with ResEDgar, change my name to yours, save,
then run it again.

BeGUI is a simple to use programmer's tool which allows for rapid development
of a program. It is sensitive to font sizes, style and families; has a lot of
color control preferences and had a window class which is self-sizing and
recalls it's position from instance to instance (two preference files get
stored in /home/config/settings--thanks to Jon Watte's libPrefs).

A "Pref" menu entry allows access to a wide range of GUI settings, including
the font size and the color scheme of all the "gadgets". The application is
entirely font sensitive, so play about with various silly sizes! Messing about
with the "gadget" colors can be fun, it can also make things very ugly! Give
these a try as well.

The archive unzips into a folder called ResEDgarPPC which contains a
handful of folders and some loose source and text files. All source code is
included, so you can see how I have done the BeGUI stuff.

Extensive html documentation of BeGUI and a major re-write of all the code has
been completed for this release. Check the documentation folder for the html,
start with documentation/index.html and check it all out from there.

-Ed
edgar@harbornet.com



