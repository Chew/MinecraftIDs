---
layout: info
title: FAQ
permalink: /faq/
---

## What are block and item ids?

Each type of block and item is given a unique identification number. This is used by the game to remember which blocks you placed where, as well as to select the appropriate texture, icon and behaviour of a block or item.

These ids are also known as 'data values' in the Minecraft community.

## What is the meta data of an item?

Certain items have additional attributes that cannot be described by the id alone. For example, the damage on a sword, the age of some crops or the colour of some wool. These are stored in an additional field called 'meta data'. Some people also refer to it as the 'damage value' as originally it was only used for damage.

## How do I spawn a block or item?

Spawning an item generally means obtaining it without performing the actions the game normally requires. For example, instead of waiting for crops to grow and then harvesting them, you could spawn the wheat item instantly. Many players consider this to be cheating and it is sometimes frowned upon.

You can spawn items using the `/give` command, which is typed into the chat box. The syntax of this command is:

`/give [username] [id] [amount] [meta data]`
You should replace [username] with the name of the player who should receive the item, [id] with the id of the block or item, [amount] with the quantity of the item you wish to spawn and [meta data] with the meta data of the item. The default value for meta data is 0, and it can thus be omitted from the command if you do not need to change it from this default. An interactive list of item and block ids may be found on this website.

For example, if you wished to give the player Ancient three glowstones, you would type this:

`/give Ancient 89 3`
If you wished to give the player Notch a spawn enderman egg, which involves a non-zero metadata value, you would type this:

`/give Notch 383 1 58`
On most servers only the administrators of the server can use the /give command.

In newer versions of Minecraft, the text-based IDs are used instead of the numeric IDs. For example, to give the player Ancient three glowstones, you should type this:

`/give Ancient minecraft:glowstone 3`

## What are mob and entity ids?

Each type of mob and entity is given a unique identification number, in a completely analogous manner to blocks and items. They also have a text-based identifier known as a "SaveGame" id. For example, the "SaveGame" id of an experience orb is "XPOrb".

## How do I spawn a mob or entity?

You can spawn entities using the /summon command, which is typed into the chat box. The syntax of this command is:

`/summon [savegame id] [x] [y] [z] [metadata]``
You should replace [savegame id] with the "SaveGame" id of the mob or entity. The remaining arguments are optional - [x], [y] and [z] default to your current location, and [metadata] defaults to nothing.

For example, to spawn an experience orb at your location, you would type this:

`/summon XPOrb`
