# Convenient Bags

__Convenient Bags__ (_previously Unpack Bags_) is a mod for [Project Zomboid](http://projectzomboid.com/) which adds several new features to the vanilla item containers.

## Overview

- Add tags to a bag to allow quick sorting of items
- Quickly pack items into a bag
- Quickly unpack items from a bag
- Includes translations for English, German, French, Russian and Finnish
- [Tiny AVC](https://github.com/blind-coder/pz-tiny_avc) Support

![preview](https://raw.githubusercontent.com/rm-code/convenient-bags/master/RMConvenientBags/poster.png)

## Unpacking Bags

Bags can be quickly unpacked via a context menu. The bag will drop its contents into the container in which it currently is contained (this can be the player's inventory, a container or even the floor). If the container is full the bag will only be partially emptied.

## Adding tags

Tags can be added to a bag to limit it only to certain types of items. When you click "Edit Tags" a small text box will show up, allowing you to add a new tag. This can be an item category (Food, Weapon, etc.) or an item's full or partial name (Water, Bowl, Garbage Bag). 

Tags can be removed by editing the tags and entering the tag you want to remove, preceded by an exclamation mark (```!tagtoremove```).

These tags are used by the packing option.

## Packing Bags

Bags can also be conveniently filled with items. Clicking on "Pack items" will move all items in the same container as the bag except for containers and equipped items into the bag.

By using tags this option can be limited to certain types of items. If a bag has at least one tag only items fitting the tag will be transferred into the bag.

![packing.gif](https://cloud.githubusercontent.com/assets/11627131/9081433/8f21224a-3b5c-11e5-94ac-5097bd4e9214.gif)

## Installation

[Look here](http://theindiestone.com/forums/index.php/topic/1395-) for installation instructions.

## Translations
The mod has already been translated to a bunch of different languages. If you want to add a translation, feel free to fork this project and send a pull request.

Adding new languages is quite easy. Just take a look at the ```media/lua/shared/Translate``` folder in this mod.

For more information about translations check the [official forums](http://theindiestone.com/forums/index.php/forum/56-).
