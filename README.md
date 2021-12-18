# hco_munitions
H Co. Munitions is a WIP mod for Cataclysm: Bright Nights (and now CDDA!) that adds a way to bulk craft factory-grade ammunition

This mod aims to enable automated, bulk crafting of factory-grade ammunition, through the production of powder, primer, cores and casings.
I'm hoping to accomplish this through the following additions:

- Several machines from H Co.
  1. Case Press : for making casings of various calibers
  2. Bullet Extruder : shapes lead and copper into bullets
  3. Priming Press : for making primers
  4. Powder Turret : produces and loads modern smokeless powder into rounds. Also the final machine in the assembly line
  
Currently, I have implemented everything that encompasses the base functionality of the mod. Further development will be aimed at balancing the crafting between realistic component requirements and enjoyment, as it may be more difficult to collect enough resources to craft ammo than it would otherwise be to simply loot it.

+++ Quick Guide +++

To begin with, you will need to up your skills, specifically Fabrication, Cooking, and Electronics. This will allow you to meet the skill reqs for building the furniture. You don't actually need to build the Case Press if you wish to use scavenged ammo casings, just be aware that certain ammunition destroys the case when used and is otherwise unreplenishable. Different ammunition requires different levels of skill in the either Pistols or Rifles. 

+++ Other Notes +++

Currently, shotgun ammo is not craftable using the H Co. toolset. You may also wish to play with mods that increase the presence of magnesium on the map or allow the refining of magnesium through mining or some other avenue.

=== Development Roadmap ===

1. Ammunition Crafting      	[ ]
  A. Rifle/SMG/Handgun Ammo 	[X]
    i. Casings              	[X]
	ii. Cores					[X]*
	iii. Powder					[X]*
	iv. Primer					[X]*
	v. Variants					[X]
  B. Shotgun Ammo				[ ]
    i. Shot types				[ ]
	ii. Powder					[X]*
	iii. Primer					[X]*
	iv. Shells					[ ]
	v. Variants					[ ]
  C. Explosives					[ ]
    i. Grenades					[ ]
	ii. Rockets					[ ]
2. Workstations					[ ]
  A. Placed						[ ]
    i. Case Press				[X]
    ii. Bullet Extruder			[X]
    iii. Priming Press			[X]
    iv. Powder Turret			[X]
    v. Shell Spinner			[ ]
  B. Items						[ ]
    i. Case Press				[ ]
    ii. Bullet Extruder			[ ]
    iii. Priming Press			[ ]
    iv. Powder Turret			[ ]
    v. Shell Spinner			[ ]
3. Buildings					[ ]
  A. H Co. Factory				[ ]
  B. Ruined Factory				[ ]
  C. Basement Setup				[ ]
  D. H Co. Headquarters			[ ]
4. NPCs							[ ]
  A. H Co.						[ ]

===========================

+++ THE FOLLOWING HAS BEEN [REDACTED] EITHER BECAUSE I DO NOT CURRENTLY HAVE THE TIME, THE SKILLS, OR THE PATIENCE. +++

- Each machine is capable of being: 
  1. crafted : as an unusable item
  2. built : as usable furniture
  3. installed : as usuable furniture
  4. deconstructed : either into a "compacted" item version or into the original parts

- Interacting with each machine should allow:
  1. loading of materials
  2. initiation of manufacture process
  3. unloading of finished products
