# How to Make Your Inkscape Theme Dark and Add Flat Icons On Mac OS

The following are Instructions and resources for changing the theme and incons in Inkscape on Mac OS

I searched high and low, forums big and small, and came up empty on this. Almost everyone said "you can't do it", which is actually not the case. With a few clues from blog comments and some trial and error. I figured it out. Finally.

![][image1]

[image1]: https://github.com/abirnie/inkscape-dark-theme-mac/blob/master/inkscape-dark-theme-mac.png

## Get and Prepare Files
1. Download [Unarchiver](http://unarchiver.c3.cx/unarchiver). We'll use it to extract the ZIP file **and** the .exe file that contains the theme (note: the default Mac utility for zip files doesn't work for this)
2. Download a dark theme for Inkscape. I used [this one from iOVERD](http://ioverd.deviantart.com/art/Inkscape-0-91-dark-theme-547919927) on DeviantArt.
3. Unzip the file with [Unarchiver](http://unarchiver.c3.cx/unarchiver) (right click, Open with..., Unarchiver).
4. Unzip the dark theme's .exe file (either 32- or 64-bit) with [Unarchiver](http://unarchiver.c3.cx/unarchiver) (right click, Open with..., Unarchiver).
5. Navigate to Share/themes/Default. There will be a file named "gtkrc" there that we'll use to replace another file. Keep this window open for the following steps...

## Replace theme file
4. In a different Finder window, go to your Applications folder, right click on Inkscape, select "Show Package Contents"
5. Navigate to Contents/Resources/etc/gtk-2.0
6. Replace the only file in that folder (named "gtkrc") with the file of the same name from step 5 above.

## Replace the icon.svg file (optional)
7. Now navigate to Contents/Resources/share/inkscape/icons
8. Replace the icons.svg file that is currently there with the icons.svg file from your new dark theme folder that you unzipped in step 5 above (found in share/icons)
9. Start (or restart) Inkscape. Hopefully, yours looks like the screenshot from my setup above. 

