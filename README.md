Version 1.0.0-alpha Mon 14 Nov 2022 01:49:36 AM UTC

# minetest-tnt
This is a modified tnt mod for minetest.  It's designed to work in such a way that servers won't crash when it's used.  This is done by introducing a delay between explosions.  

-- Here is the README.txt from the original mod --
Minetest Game mod: tnt
======================
See license.txt for license information.

Authors of source code
----------------------
PilzAdam (MIT)
ShadowNinja (MIT)
sofar (sofar@foo-projects.org) (MIT)
Various Minetest developers and contributors (MIT)

Authors of media (textures)
---------------------------
BlockMen (CC BY-SA 3.0):
All textures not mentioned below.

ShadowNinja (CC BY-SA 3.0):
tnt_smoke.png

Wuzzy (CC BY-SA 3.0):
All gunpowder textures except tnt_gunpowder_inventory.png.

sofar (sofar@foo-projects.org) (CC BY-SA 3.0):
tnt_blast.png

Introduction
------------
This mod adds TNT to Minetest. TNT is a tool to help the player
in mining.

How to use the mod:
Craft gunpowder by placing coal and gravel in the crafting area.
The gunpowder can be used to craft TNT or as fuse for TNT.
To craft TNT place items like this:
-- wood - gunpowder -- wood -
gunpowder gunpowder gunpowder
-- wood - gunpowder -- wood -

There are different ways to blow up TNT:
  1. Hit it with a torch.
  2. Hit a gunpowder fuse that leads to a TNT block with a torch or flint-and-steel.
  3. Activate it with mesecons (fastest way).

Be aware of the damage radius of 6 blocks!
