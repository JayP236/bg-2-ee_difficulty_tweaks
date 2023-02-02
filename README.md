# Difficulty Tweaks
JP's BG:EE Difficulty Tweaks

This mod is aimed at experienced players who want some extra challenge during a BG(2):EE playthrough. The idea is to promote adventuring by making resources in stores scarcer/more expensive. Additionally some extra tweaks are included for the more diehard players.

**Version History**
- v0.1: Initial version.
- v0.2: Added 2 Hardcore tweaks: "Remove all Items from Stores" and "Make Korax the Ghoul Turn Hostile if Injured".
- v0.3: Added full support for the SOD campaign. Replaced the "Remove All Joinable NPC's from the Game" tweak with the less intrusive "Block All Companions from Joining the Party" tweak.
- v0.4: Added support for BG2:EE. The "No Recharging of Items with Limited Charges" tweak is now made dynamic instead of using a fixed list of items. The "No Wild Camping" now has an additional option "No Wild Camping in Dungeons".

**Installation**
Copy the contents of the zip folder to your Baldur's Gate Enhanced Edition folder. Run setup-jptweaks.exe to install via WEIDU. Make sure to first install the SOD DLC-Merger.

**Compatibility**
This mod is intended for BG(2):EE v2.6.6. In general it will be compatible with most mods. It is recommended to install this mod as late as possible, especially after installing any mods that alters item placing and/or store inventories (like the Item Randomiser mod).

**Notes**
This mod now covers BG:EE with the SOD campaign and BG2:EE.

## Store Tweaks

### Remove Protection Scrolls from Stores
Removes protection scrolls from stores.
This component has 3 options:
- Remove all Protection from Undead scrolls
- Remove all Protection from Undead and Protection from Magic scrolls
- Remove all (green) protection scrolls

### Remove Wands from Stores
Removes all wands from stores.

### Remove Spell Scrolls from Stores
Removes all spell scrolls from stores.

### Remove Potions from Stores
Removes potions from stores.
This component has 2 options:
- Remove all potions except Potions of (Extra) Healing, Antidotes and Elixirs of Health
- Remove all potions

### Remove Magical Ammo from Stores
Removes magical ammo and magical throwing weapons from stores.
This component has 3 options:
- Remove all Arrows of Dispelling and Detonation
- Remove all magical ammo
- Remove all magical ammo and magical throwing weapons

### Remove Magical Items from Stores
Removes magical items from stores.
This component has 3 options:
- Remove generic (+1, +2...) enchanted weapons and armor
- Remove all enchanted weapons and armor
- Remove all magical items

### Make Unlimited Supply of Items Limited
Sets all items with an unlimited supply to a stock of just 10 items.

### Decrease Amount of Items in Stock
Decreases the amount of items the stores have in stock. Atleast one item will still always be available.
This component has 3 options:
- Decrease by factor 2
- Decrease by factor 5
- Decrease by factor 10

### Increase Store Sell Markup
Increases the sell markup of stores.
This component has 3 options:
- Increase by 50%
- Increase by 100%
- Increase by 200%

## Hardcore Tweaks

### Remove All Items from Stores
Removes all items from stores.
This component has 2 options:
- Remove all items except item containers (keeps gem bags, scroll cases etc)
- Remove all items

### No Recharging of Items with Limited Charges
In an unmodded game, items like wands etc are recharged when sold to a shop, this component sets them to 1 charge when bought back from a shop. Additionally items that are normally not destroyed when empty, like the Myconid Bloom-Sac, Cloak of Minor Arcana etc. will now vanish when empty. Items added by other mods will also be affected.

### No Traveling during Combat
This component blocks the ability of the party to travel on the worldmap while in combat. 

### No Wild Camping
This component sets the probability of a rest encounter to 100% in areas with active rest encounters, effectively making resting impossible.
This component has 2 options:
- No wild camping in dungeons
- No wild camping in all areas

### Make Potions of Invisibility and the Sandthief's Ring Limited to Thiefs
The get out of trouble free cards for practically all classes. This component limits their availability to Thiefs (single, dual and multi class) only.

### Make Drizzt's Items Unobtainable (BG:EE only)
Drizzt is carrying some high-end equipment which can be obtained pretty much from the start of the game. This component flags his equipment as not stealable and undroppable, making it unobtainable.

### Make Korax the Ghoul Turn Hostile if Injured (BG:EE only)
Korax is a bit too friendly, willing to die for charname he just met. This component makes him turn hostile if he is injured in any way.

### Block All Companions from Joining the Party
This component blocks all companions from joining the party, forcing charname to save the Sword Coast by himself/herself.
Companions added by other mods will also be blocked from joining the party. Note that the dialogue options for making them join are still in place, they just won't trigger the join action.