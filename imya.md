# Noblesse Oblige

![thumbnail_16_9](https://github.com/user-attachments/assets/00fcc71e-fec6-409f-9723-684419bbb2ee)

In this repo you can find the Modification Noblesse Oblige for Anno 1800

Anno 1800 Noblesse Oblige is a mod that transfers and expands the concept of the official 'Seeds of Change' DLC to the Old World.

Für die deutsche Version des readmes, bitte [hier](readme_german.md) klicken.

Pour la version française du lisez-moi, veuillez cliquer [ici](readme_french.md).

If you like this mod and want to support me, feel free to share it with your friends. I have spent countless workhours into this Mod and its development lasted for well over a year! Please, if you download this mod and enjoy the additional content, consider supporting me by making a donation on my Ko-Fi page! Your support is highly appreachiated and will ensure further development of unique and engaging mods.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W8L558T)

## How to use

- Automatic install using the Anno Mod Browser, available from the main menu of your Anno 1800 game.
- Automatic install using [iModYourAnno](https://github.com/anno-mods/iModYourAnno/releases) mod managers access to the Github library.
- Manual Install: Know [how to install mods manually](https://github.com/jakobharder/anno1800-mod-loader#mods). If you download the mod manually from GitHub, use the archieve from [GitHub releases](https://github.com/Taludas/NoblesseOblige/releases). Don't download the whole repo!

1. **This mod is savegame compatible. You can start it mid-game.** 
**HOWEVER**: To experience the full potential of this mod, I recommend starting a new savegame to explore the additional content. This mod is specifically designed to expand the early game up to Engineers and also comes with a number of new fertilities. These are provided for free in an existing savegame, but are intended to provide an extra challenge in the early game!

2. **DLC Dependency:** 
- "Seeds of Change" DLC.

3. **HIGHLY RECOMMENDED:**
- "Old Town" cDLC

4. Multiplayer and AI: Not tested and therefore not supported! Use at your own risk! Although I have disabled all new content for the AIs, I cannot guarantee that they will not get stuck. In particular, the progress of scholars may be hampered by this mod's adjustments to certain products from the "Land of Lion" DLC.

5. Unlock Conditions of the mod: The content in this mod can be explored from the start of the game. In fact, you can choose to play exclusively with the new content until you reach Artisans. Note that the 4x4 Artisans in this mod can't be upgraded to Engineers.

## Incompatibilities
- This mod is incompatible with all other mods that alter the initial loadout of your starting ships.

-----

## Features

**TL:DR**

The Mod adds the following elements:

- New population tier called "Landowners" with two new mechanics: influence through the supply of luxury goods and traditional patronage (cultural set buffs getting stronger with increasing total numbers of landowners settled on your islands).
- The Administration: your interface for controlling land and production ("Hacienda"-like Main Building) with modules and five new edicts.
- Specialised agriculture: New recipe farms for the Old World with modified secondary modules (horse-drawn plough and fertiliser)
- Craftsmanship between tradition and modernity: New OW recipe breweries and recipe carpentries
- 4x4 residential buildings with new needs for OW population levels 1-3
- The Foreign Trading Company: Import exotic products from all over the world in exchange for Trade Licenses. A more balanced version of Docklands which also becomes an interface for mod interactions with future release of the Modding Season 2025.

-----

## FAQ

- **Administration**: The second UI, which increases the radius of the Administration, is unlocked by pressing Shift+C. To return to the normal Hacienda interface, press Shift+C again.
Additional Mansion build permits: You will receive one build permit for each island you settle. Once you have reached your first level 3 Mansion, you can purchase additional permits from the Queen for a total of 20 additional permits. The cost of these will increase exponentially.
- **Orangery**: The Orangery is a production building that consumes input. However, if you build its special modules around the main building, you can increase the productivity of the Orangery while consuming Tools.
Vanison Butchering: In the earlygame you can generate Beef by building a module for the Hunting Cabin that consumes Tools.
- **Apiary**: This building has a double output. One product is produced by the main building, while the other is produced independently by the fields (Electrified Pastures mechanic without electricity).
- **The Manor Park**: A special public building. You can build a "gate" from the build menu. However, this gate doesn't do anything by itself and only contributes a small percentage to the overall need reduction. You need to build more ornaments around it. The gate and the ornaments all have a radius. Inside this radius, the ornaments project a buff on all mansions, reducing their need for the public building "Manor Park" by varying percentages. Build enough ornaments around your mansions to reduce their need by at least 100% in total to fulfil the "Manor Park" need. Important to note: The need bar cannot show you the progress of your need reduction, but only 0 or 100%. So if the bar is still empty, and you already have built a lot of Ornaments, it is still not enough or they are not in range of that specific manor.
- **The Foreign Trading Company**: Start by building the main building from the Landowner build menu. You can then expand it with modules from its UI. Start with an export dock. This will consume goods in varying amounts. Read the module infotip for more information on cycle time and goods requirements. It produces Trade Licences in exchange. You can now spend these by building an import dock. Use the Special Warehouse module to add loading ramps to the port area and increase your storage capacity for all import products. Improve the efficiency of the import dock by building handling piers around it, which require barrels and ropes.
- **Traditional Patronage**:  As you settle more and more Landowners on your islands, you will get stronger and stronger buffs on the effects of your cultural item sets. This system starts with 300 Landowners (level 1) and you can increase the effect until you reach 12000 Landowners (level 20). At maximum level, most of your set buffs will be 5 times stronger than normal (Proud Savanah, for example, won't get these extreme numbers).

-----

## Known Issues


- **Build Menu**: Due to the introduction of an additional tab in the build menu for Landowners, a submod is used that reduces the size of the visible buttons to make room for more without overlapping on the left and right. Unfortunately, there is a problem with this: The hitbox for the clickable buttons is too big for the reduced buttons. This can lead to some mis-clicks until you get used to it.
- **Administration**: The radius increase interface has some features that are not required to work correctly. You only need the slider at the bottom to allocate landowner workforce to increase the radius. The modules (regular tier 1 landowner mansions), power requirement, cycle time, and the "broken" recipe book button are completely irrelevant. When you click on the Recipe Book button, a blank and transparent recipe book interface opens. You cannot adjust anything in it.
- **Traditional Patronage**: The quests that activate/deactivate the relevant buffs for the Traditional Patronage feature are sometimes a little slow to react to the preconditions. You may find that you have two buffs active at the same time, or none at all for a short period of time. It is best to keep a steady supply of goods for your landowners, especially for the level 3 mansions, as they move in and out more quickly and therefore a lot of buff (de-)activation can happen around the step up/down borders.
- **Influence from Happiness Needs**: For "shared" needs such as School, the buffs only become active if ALL residents are supplied with at least 95% of the need, so it is not limited to the satisfaction of the landowners in the case of non-exclusive goods!
- **Pontifical Mass Event in the Imperial Cathedral**: Upon completion of the event, the UI only shows the buff that will be granted after its completion as a reward. In fact you still get the promissed 3 Items from the respective loottables. The are just not shown in the UI and will be available in your Kontor as usual. Another issue with the Pontifical Mass is that the after-event festival blocks all other monument events (i.e. World's Fair exhibitions) from being started, not only the one in the cathedral.
- **Build permits for Manors**: Make sure you downgrade your level 2 and 3 landowner manors before you destroy them. Otherwise the build permit to build a new level 1 manor will be lost and cannot be claimed again!

-----

## Credits

**The graphics in this mod are not only created by myself, but also by people from the community. Here is a breakdown of all the artists involved and the graphics they created:**

- Apiary: parts of the model and field props by Taubenangriff
- Artisan Studio base model by Ricky (MrKoekie)
- Lobster Restaurant base model by Ricky (MrKoekie)
- Confectionery by Ricky (MrKoekie)
- Goulash Kitchen by Ricky (MrKoekie)
- Administration by Ricky (MrKoekie)
- 4 new ornaments by Ricky (MrKoekie)
- Patisserie by Ricky (MrKoekie)
- Farmer 4x4 residences by Ricky (MrKoekie)
- Artisan 4x4 straight varients by Ricky (MrKoekie)
- Apple Orchard by Xormenter/Kurila
- Universal breweries (Apple Cider, Schnaps, Beer, Wine) by Ricky (MrKoekie)
- Universal farms (Grapes, Hops, Vegetables (partly), Potato, Grain) by Ricky (MrKoekie)
- Fish Stew Kitchen by Ricky (MrKoekie)

**With their permission - other modders assets:**

- Imperial Cathedral originally ported by Fishboss from Anno 1404
- Reskinned Da Silva Portrait for the Landowner portrait by eadwearddemylae
- Chapel originally ported by Fishboss from Anno 1404 with improved textures from shane868 and Lion
- A modified version of xan (sealring) Metropolitan Hospital as a skin for the Landowner residence
- Foreign Trading Company graphics by Drakkam, jje1000, Taubenangriff and myself

**Part of the gameplay features have been developed together in the Anno modding discord.** However, the final decission on all gameplay features and their implementation into the game with assets happened by myself. So if you don't like a particular feature, don't blame them!

**Shared Mods from other modders, that are included in this mod:**

- Kurila: Vegetable Integration, Apples (Product), Barrels (Product), Shared Clay Works, Shared General Modules, Shared Herb Garden, Shared UI Change
- Jakob: Hemp (Product), OW Hemp, OW Linen, Ropes (Product), OW Ropes, Tea (Product), OW Tea, Tools (Product), OW Tools, Vegetables (Jakob), OW Vegetables, Shared Ground Textures, 
- jje1000: Municipal Theatre
- Taubenangriff: More Construction Tabs
- Hier0nimus: Water (Product), Horses (Product)
- Serp: Matchers (Helper Mod), ObjectDummies (Helper Mod), TooltipSupportModPalaceMinistryHacienda, TT_MenuInputOutputAmounts, Code to distribute Buffs via Quest only on the current island area, Code to limit a building to one per island without using an Enum for it.

-----

Suggested Mods, that play well with this one:

- River Slots by Taludas
- Industrial Cities by Jakob
- City Variations by Jakob
- Military Attention by Hier0nimus
- Old Town Extended by MrKoekie