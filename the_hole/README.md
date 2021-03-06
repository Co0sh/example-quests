# The Hole

_Quest package for BetonQuest_

## Story

The mysterious hole appears out of nowhere near Old Man's house.
The demons start coming out of there and only the Player can stop
them. Fight the monsters and outsmart the evil necromancer!

## Description

The Hole is a small quest, containing two conversations and two
small dungeons. It's not very hard, and it can take up to 20 minutes
to complete it for the first time. It contains the MCEdit schematic
with the setting, and the configuration is only two options.
Three separate endings with varying rewards. A global location adding
an entry to the journal.

## Installation

1. Install **BetonQuest 1.9** or later.
2. Install **WorldEdit 6.1** or later.
3. Install **MythicMobs 2.0** or later.
4. Paste _the_hole_ schematic somewhere in the world.
5. Write down coordinates where you used `//paste` command.
6. Move the package into the _BetonQuest_ directory.
7. Open _main.yml_ file.
8. Edit `loc` variable to match coordinates from 4.
9. Edit `town_name` to the name of the nearest town in your world.
10. Edit `boss` and `boss_lvl` to the name and level of MythicMobs boss.
11. Optionally adjust `items` rewards (matching the ones in _items.yml_ file):
    - `low` is lower reward for being evil,
    - `high` is higher reward for being evil,
    - `iron` is a reward for choosing warrior path,
    - `gold` is a reward for choosing paladin path,
    - `diamond` is a reward for choosing merchant path,
    - `bonus` is an additional reward for not being greedy.
12. Use `/q reload` to reload the plugin.
