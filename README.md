# Rupert The Dye Merchant
A Vilkalizer™ brand mod (accept no substitutes!) for Baldur's Gate II, TuTu and/or BGT. 
*Now updated for BGEE BG2EE and EET by Vadász.*

## Introduction
This mod adds a new merchant who sells various dyes and new outfits. *In order to keep most of the original readme intact I, Vadász, will add relevant info for the EEs in italics.* 

Dyes work like potions. These can be used by anyone, and will permanently change the user's colours as specified by the particular dye: there are separate options for major and minor colours, leather (belts/boots/straps), armour, decorative items (like belt buckles/amulets) and hair.

Outfits will change the the character's appearance to match the specified class: fighter, mage, thief or cleric (I strongly suggested that you also install everything from 1 Pixel Productions.) 
*Never install 1PP on EEs*. These can be used by anyone but monks (which would look wonky). Halflings have no mage avatars and will use the gnome mage avatar instead. Half-orcs have no mage paperdolls in the unmodded game, meaning you won't see your character on the inventory screen (unless you install the 1PP update, which adds one).

All changes are purely cosmetic; you do not gain or lose abilities by using anything bought from Rupert's stores.

Rupert should be fully compatible with Baldur's Gate II (with or without Throne of Bhaal), as well as BGT and BG TuTu*, BGEE, BG2EE and EET are compatible too of course*. He will appear in the Mithrest Inn in regular BG2 *or BG2EE*, as well as the inns in Saradush and Amkethran if you have Throne of Bhaal installed. In TuTu and BGT *and BGEE*, he will appear in a room on the second floor of the Friendly Arm Inn (the second from the left on the top-left side of the screen).

## Installation
Simply unpack "rupert-v2_1_1.zip" to the folder where you have your game installed.

Run "setup-rupert.exe" and follow the instructions on your screen.

To uninstall the mod, run the setup program again and follow the on-screen instructions.

## Caution
*This info of the following paragraph or may not be outdated for the EEs so far it seems to be working fine*

Since I have had a couple of crash reports, I recommend saving before using dyes. This is not a problem with the mod, but rather the game engine itself; unfortunately, this is not something that can be fixed. Which colours are affected, if any, seems to vary between installs.

Dyes add a permanent "set colour" effect to the user. This overrides the character's original colours, and you will no longer be able to switch major/minor colours on the inventory screen if you use dyes to change them. (Well, you can, it just doesn't do anything.) If you want to change back to your original colours, you will have to use another bottle of dye.

Dyes also override colours specified by armour or other gear. If you use a dye to turn your armour hot pink, every piece of armour that character wears in the future will be hot pink (unless you re-dye it).

It appears that the drow disguise in the Underdark cancels the effect of any dyes used on your characters. You can, however, return to the Mithrest Inn upon leaving the Underdark and re-stock on dyes. 

## Notes
To summon Rupert anywhere:

CLUAConsole:CreateCreature('JL#RUPRT') *or C:CreateCreature('JL#RUPRT')*

This summons the regular BGT/TuTu *or BGEE/EET* version of Rupert. Use this if you're playing BG1.

CLUAConsole:CreateCreature('JL#RUPR2') *or C:CreateCreature('JL#RUPR2')*

This summons the SoA *or BG2EE* version. Use this if you're playing BG2.

(The Saradush version is JL#RUPR3 and the one in Amkethran is JL#RUPR4. All of them sell the same items at the same prices.)

To create items without Rupert:

CLUAConsole:CreateItem('JL#P&¤¤¤') *or C:CreateItem('JL#P&¤¤¤')*

Replace the & with an A for a dye for the major colour, B for minor colour, C for straps/boots/leather, D for armour, E for buckles/amulets, or F for hair.

¤¤¤ is the number of the colour gradient you want, from 000 to 115.

For example, JL#PF001 will create a brown dye that affects the user's hair, while JL#PA000 is slightly red-tinted black and will affect the character's major colour.

For a complete list of colour gradients, see the list at G3: http://iesdp.gibberlings3.net/appendices/colourgradients.htm

The codes for the outfits are JL#CCLRC (cleric), JL#CFGTR (fighter), JL#CMAGE (mage) and JL#CTHIF (thief).

## Version History
VERSION 2.2Beta (July 19 2018)
- Added the BWP fixes
- Modified the code so that it works in the EEs.

VERSION 2.1.1 (March 20 2010)
- Added Italian translation by ilot.

VERSION 2.1 (March 19 2010)
- Added Spanish translation by Lisandro.
- Fixed a gnome-related typo in the code.

VERSION 2.0 (December 2009)
- Added "outfits" to Rupert's store
- Re-arranged dyes: lower numbers are now at the top, rather than the bottom.
- English only so far.

VERSION 1.1 (25 November 2009)
- Miloch's fixes
- Traified the mod
- Added German translation by Meresin
- Changed to README-command
- Added VERSION-flag
- Updated to WeiDU v211

VERSION 1.0
- First initial release

## Credits
This mod was created and mantained by vilkacis up until v2.1.1.

Special thanks to Miloch and Leomar for help with bams, updating and... stuff. Y'know. Things.

## License
Public domain: no rights reserved. May be freely copied, edited and distributed. 
