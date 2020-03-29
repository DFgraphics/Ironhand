# Ironhand

Ironhand is 18x18 graphics pack for Dwarf Fortress.

[Forum link](http://www.bay12forums.com/smf/index.php?topic=53180.0)

________________________________________

## Index
 1. [System Requirements](#system_requirements)
 1. [Installation](#installation)
    1. [Dfhack with TWBT](#dfhack_with_twbt)
 1. [Screenshots](#screenshots)
 1. [Credits](#credits)
 1. [Patreon/Donations](#patreon_donations)

________________________________________

## <a name="system_requirements"></a> System Requirements

This graphics pack requires the "SDL Windows", Mac, or Linux version of Dwarf Fortress.

Additionally, the main tilesets (located in the `/data/art/` folder) need one of the above 
versions from v0.31.04 or later, and the creature graphics (located in the `/raw/graphics/` 
folder) require one of the above versions from v0.31.05 or later.

Most critically, the raw data objects (located in the `/raw/objects/` folder) are only 
compatible with a *very limited* range of Dwarf Fortress versions. Trying to use these 
objects files in version of Dwarf Fortress not compatible with them will likely cause 
damage to save files. The versions of Dwarf Fortress that the included objects files are 
compatible with are listed on [the release page](https://github.com/DFgraphics/Ironhand/releases) before you download them.

As for the content in the `/data/init/` folder, it should generally be compatible with
any version of Dwarf Fortress (especially earlier versions than the listed in the range of 
compatible versions), but could cause minor graphical issues when used with newer versions
of Dwarf Fortress than the listed compatible versions.

As a 16x16 graphics pack, this tileset looks best at a display resolution of at least
1280 horizontally by 400 vertically. At smaller display resolutions, the game window 
may take up more space than is available on your screen but can be fixed by resizing 
the game window, which will cause the pixels to be drawn at a scaled-down size to-fit.


## <a href="installation"></a> Installation

 * Copy the contents of the `/data/art/` folder into Dwarf Fortress' `/data/art/` folder.
 * Copy the contents of the `/data/init/` folder into Dwarf Fortress' `/data/init/` folder.
 * Copy the contents of the `/raw/objects/` folder into Dwarf Fortress' `/raw/objects/` folder.
 * Copy the contents of the `/raw/graphics/` folder into Dwarf Fortress' `/raw/graphics/` folder.
 
 For any existing save files you have that you would like to use these graphics with, 
 copy the contents of the `/raw/objects/` and `/raw/graphics/` folders into the corresponding
 folders of your save files (located in the `/data/save/` folder).
 
 Do not copy the `/raw/objects/` folder into existing save files that were created with a 
 version of Dwarf Fortress that is not compatible with the graphics pack, or it is 
 likely to corrupt your save.


### <a href="dfhack_with_twbt"></a> DFHack with TWBT

The Text Will Be Text (TWBT) plugin for DFHack allows many improvements to graphics.
This pack includes optional components to take advantage of TWBT features.
If you wish to use these components, additional steps need to be taken.
In all of these steps, the TWBT components need to be installed over the normal graphics 
pack components so that the TWBT content overwrites the regular graphics pack content. 
It's probably easiest to install the TWBT content into the normal graphics pack folders 
before then copying those all into your copy of Dwarf Fortress.


#### Installing all the TWBT content

To install all the TWBT content, 

 * Copy the contents of the `/data/twbt\_art/` folder to the `/data/art/`.
 * Copy the contents of the `/data/twbt\_init/` folder to the `/data/init/`.
 * Copy the contents of the `/raw/twbt\_graphics/` folder to the `/raw/graphics/`.
 * Copy the contents of the `/raw/twbt\_objects/` folder to the `/raw/objects/`.
 * Copy the `onLoad\_gfx\_Ironhand.init` file into the `/raw/` folder.


#### Installing only the Transparent Backgrounds for Creature Graphics TWBT content
  
To get creature graphics with transparent backgrounds,

Copy the contents of the `/raw/twbt\_graphics/` folder to the `/raw/graphics/`.

(Note that this will need to be repeated in the corresponding folders of any existing save 
files you wish to have creature graphics with transparent backgrounds.)

Edit the non-TWBT `/data/init/init.txt` file to set the print mode to "TWBT".


#### Installing only the Transparent Backgrounds for non-creatures TWBT content
  
To get some buildings, items, and furniture with transparent backgrounds,

 * Copy the contents of the `/data/twbt\_art/` folder into the `/data/art/`.
 * Copy the "overrides.txt" file from the `/data/twbt\_init/` folder into the `/data/init/` folder.
 * Edit the non-TWBT `/data/init/init.txt` file to set the print mode to "TWBT".


#### Installing only the TWBT text Font
  
To get more readable, space-efficient text,

 * Copy the contents of the `/data/twbt\_art/` folder into the `/data/art/`.
 * Copy the "init.txt" file from the `/data/twbt\_init/` folder into the `/data/init/` folder.
 * Copy the contents of the `/raw/twbt\_objects/` folder into the `/raw/objects/` folder. (This last step is optional, but restores the full versions of the civilized languages.)


## <a href="screenshots"></a> Screenshots

[![roadmap](./_imgs/readme_img.png)](https://sun9-22.userapi.com/c857436/v857436359/1bb1ac/kwgy98IimfY.jpg)


## <a href="credits"></a> Credits

- Ironhand
- Wormslayer
- Phoebus
- Mayday
- RantingRodent
- Stele007
- Cyster
- DrD_AVEL
- Beefmo
- everyone else


## <a href="patreon_donations"></a> Patreon/Donations

If you really like Dwarf Fortress and/or this tileset and want to help indy developers, 
consider making a donation to the developers of Dwarf Fortress at bay12games: 
https://www.patreon.com/bay12games  

Thank you!
