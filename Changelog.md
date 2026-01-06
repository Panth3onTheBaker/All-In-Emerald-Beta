In all proceeding entries, the major patches (0.x.0) include:

* Updated wild encounter tables
* New areas to explore
* Updated Trainers
* Updated Trainers and Gym Leaders
* Added NPCs where noted for obtaining additional items/Pokemon

Minor patches may include new additions to areas, additional events, more NPCs, and more as noted.



0.3.0 Dewford Gym to Mauville Gym

* Fixed where the player avatar warps to after the intro Zigzagoon fight, so Birch is no longer talking to thin air
* Professor Birch now gives the EXP share at the same time that he gives you the Pokedex, which allows you to toggle party EXP share from your backpack
* The Pokedex also now automatically includes the National Dex
* Fossil Maniac in Granite Cave now correctly faces the player, as does the guy who checks your badge outside the Dewford Dojo
* Cleaned up the Roxanne Tera Orb text, fixing a funky break in the text.
* Petalburg Woods 2F is now shorter, height-wise. There was a lot of space that looked nice in the map editor, but it was too much nothing to walk through. There is now less nothing.
* HMs are now CORRECTLY forgettable. Additionally, you no longer need to have the HM taught to a Pokémon to use it in the field. As long as you have the HM in your bag and have the prerequisite gym badge, you can use it (like in more modern Pokémon games)
* Devon Corp president will now gift you a Z-Power Ring based on your starter instead of the EXP share he gives in the base game after delivering the letter to Steven.
* The Summary Screen can now be toggled to show IVs and EVs
* All Cooltrainer class trainers are Double Battles by default
* Gym Leaders are now smarter, tougher, and correctly have an Ace
* Options Man in Oldale Town now has a toggle for turning all battles into Double Battles. Eventually, I hope to have this be toggleable in the Options menu, but I don't know how to actually add anything to that menu quite yet.
* Fishing has been update for all routes covered from 0.1-0.3
* Lilycove City (not seen until much later) Department Store now has a vending machine on the first floor where you can purchase all the starter Pokémon! That's right, all of them!



\*NOTE\* It has been like 6 months since I had worked on this, so there is possibly some changes that I forgot about and didn't notate previously. Oh well!



0.1.0 Game Start to Rustboro

* System upgrades, as per the README
* Added Route 101 Meadow
* Added Oldale Forest Entry
* Added Petalburg Meadow
* Added Options Man in Oldale Town

  * Options Man currently only turns on or off Party EXP Share, but once I figure it out, he will also enable:

    * Forgettable HMs
    * All battles are Double Battles
    * More as I think of it/is requested and I figure it out

0.1.1 Minor Adjustments

* Roxanne now correctly gives you the Tera orb after defeating her.
* Route 101 Meadow > Route 101 had an NPC that was popping in, but that has been fixed now.
* Route 104 > Rustboro City had an item ball that was popping in, and is now a hidden item
* Oldale Forest 1F is now designed, but does not yet have encounters. In testing it on my own, it does not even attempt to run encounters (which is fine for now).

  * I would not recommend trying to go into Oldale Forest 2F. The warp in, but there is no way out. I did not think it would warp in without a target, but I was WRONG.

0.2.0 Rustboro to Dewford

* As of this patch, all HMs are by default forgettable. Options Man does not currently toggle this.
* Professor Birch is currently standing in Rustboro's Pokémon Center. If you talk to him, you get the National Dex upgrade, which is nice, since otherwise all national Pokémon are #0000.
* On game initializing, Birch also now gives you the National Dex from the start.

0.2.1 Adjustments

* Added the Roxanne Tera Orb tutorial
* Fixed Mr. Briney's movement event from Petalburg > Dewford and back, so now you can actually land on Dewford which is nice.
* Updated Granite Cave layout, added fossils!
*  	I am aware that the Fossil Guy has some weird directional things. I stared at this for a couple hours before deciding that I would just have to come back to it.
* Fixed the Dewford Dojo guy to correctly push you back from the door
*  	There's still some weirdness where the second time+ you try to push past the guy, the player character turns down when stopped. I haven't yet figured that out, but it's in my list of things to get sorted (eventually)
* Fixed the surprise at the end of the Dojo
