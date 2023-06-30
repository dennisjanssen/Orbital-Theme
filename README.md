# Orbital Theme
 A stellar theme for the Anbernic RG35XX
Contains a boot logo and a full theme. Might need some tweaks on your end for localisation and a decent list of games (depending on your game art).
See instructions below.

Preview of the theme:

![Theme preview](https://github.com/dennisjanssen/Orbital-Theme/blob/main/Orbital%20Preview.jpg?raw=true)

Boot logo preview:

![Boot logo preview](https://github.com/dennisjanssen/Orbital-Theme/blob/main/Bootlogo%20Preview.png?raw=true)

## Instructions
### Skin
Simply drag the skin, lang and font into the CFW folder on your SD card. It'll ask you to replace a bunch of files, hit yes.
If you want the dark mode, you will need the 'skin --dark' folder, you can remove the 'skin' folder from your download and rename the 'skin --dark' to just 'skin'. 

### Boot logo
Replace the boot logo file in the misc partition

### RetroArch theme
Drag the retroarch folder into your CFW folder, it should merge the needed files too.
After booting your RG35XX, head into RetroArch/SETTINGS, then pick settings in the list. Select 'User interface', 'Appearance', set 'Menu color theme' to 'Custom' and then 'Custom Menu Theme Preset' to 'Orbital'. That should do it.
There's also a dark version of this, just copy over the --dark version instead of the regular one, but don't forget to remove --dark from the folder name.

### Charging animation
Replace the ramdisk.img file in the misc partition and drag the entire battery folder in there too.

## Boxart
Currently, the theme is adjusted to have boxart next to your titles. If you downloaded the Tiny Best Set and are looking for a cropped view of box arts, this might help: [click](https://www.reddit.com/r/RG35XX/comments/12dijyj/tiny_best_set_go_box_art_for_rg35xx/)
Otherwise, you can always align the titles to the center by changing the settings.json in the skin folder. Text-margin should be lowered to 30 and text-alignment changed to center.
