================================================================
      S.T.A.L.K.E.R. Sound Attribute Viewer and Tweaker
               Copyright © 2011-2012 Metacognix
                All Worldwide Rights Reserved
================================================================
2012/06/28 - 1.1     - Launch Ogg sounds directly, minor bug fix
2011/08/17 - 1.0     - Initial public release
================================================================

     Purposes:

To permit the easy viewing of STALKER sound file attributes.
To simplify the editing of those attributes.
To simplify the adaptation of standard Ogg Vorbis sound files
  to a format compatible with STALKER.

================================================================

The S.T.A.L.K.E.R. Sound Attribute Viewer and Tweaker (SAVandT) 
is a simple program that can reduce the work needed to view 
and/or edit STALKER sound file attributes that are used by 
the game to determine initial volume, volume drop-off, and 
sensitivity of NPCs to the sounds.

After editing a sound's attributes, clicking the Apply button 
will automatically recalculate the CRC-32 checksum for the 
comment/setup header page in the sound file and then update 
the file on disk.

With SAVandT, there's no need for hex editing existing sound 
files, followed by the use of a checksum fixup program.  If 
you have done this in the past, you will greatly appreciate 
the simplicity of SAVandT.

The program can also adapt conventional Ogg Vorbis sound 
files to the format compatible with STALKER by inserting 
the sound attribute structure automatically -- no more 
"Invalid ogg-comment version" or "Missing ogg-comment" errors 
resulting in hyper-alert NPCs.

================================================================

     Installation:

SAVandT is a self-contained executable which can be placed in 
any folder.  You can create a separate folder for the program 
and copy the executable and the help and readme files to that 
folder.  If you do, you might want to create a desktop 
shortcut with a "Start in" folder like your STALKER sounds 
base directory.

     Uninstallation:

Just delete the associated files and/or folder.

================================================================

     Quick-start Usage:

Simply execute the program.  View the help via the Help button. 

You can click the Select Sound Directory button to display the 
Open dialog.  Navigate to the directory containing Ogg files 
and click the "Open" button.  Select a sound file to edit from 
the list on the left or click a <dir> directory to change to it.

View and optionally change the attributes.  Click the Apply 
button to save your changes.

Please see the SAVandT_Help.txt file for more details on the 
use of this program.  You can access this file by clicking the 
Help button in the SAVandT main window.

================================================================
There is no warranty expressed or implied as to the fitness or 
other value of this program for your purposes, so make backups 
of the stuff you value.

However, the program will automatically attempt to rename the 
original .ogg file to .bak before saving the modified version,
unless you have unchecked the corresponding checkbox.

================================================================
Credits and acknowledgements: 

The following resources were utilized in the making of this 
program:

Ross N. Williams discussed CRC-32 checksum algorithms and 
provided an easily-adapted public-domain implementation. 
The link can be found at Xiph.org.

{imperialreign} and Darius6 have provided extensive sound 
modding info on varius forum sites.

nihilant, the author of fixoggcs.exe, posted info on the 
GSC sound comment structure and constants:

    "Der missing ogg-comment error" (German)
    http://forum1.onlinewelten.com/showthread.php?t=152843

Xiph.org provided the specification details for understanding 
Ogg Vorbis sound streams.

    http://www.xiph.org/

I'd also like to thank Borland for the C++Builder 3.0 compiler, 
still useful after 13 years, and GSC Gameworld for standards-
compliant stuff like their sound files.

================================================================
Feedback:
 
You can post comments about this program in the Mod Discussion 
section of the GSC forum for English users:

http://www.gsc-game.com/main.php?t=community&s=forums&s_game_type=xr&sec_id=16

Enjoy, or let me know why you didn't.

--NatVac
