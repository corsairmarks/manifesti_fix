**_DEPRECATED:_** Paradox has applied this fix in 3.3 "Libra" - if you have that version or higher, you do not need this mod.  It remains listed for players who choose to play the 3.2 "Herbert" versions of Stellaris.

# Overview

Are the Manifesti extremely unhappy with you?  This mod will help you make them quite a bit happier by fixing the impossible-to-fulfill "Personal Autonomy for Munitions" demand.  Please note that part of the demand _also_ requires having 0 slave armies and 0 undead armies - something that seems to be intentionally left vague in the tooltip by the developers.

# Changes

This mod replaces the `common/pop_faction_types/00_manifesti.txt` file that defines the Manifesti faction.  The only changes are to replace the conditions to satisfy the "Personal Autonomy for Munitions" demand.  It previously was requiring the technology "Autonomous Combat Computers" and at least 1 ship with a computer component that was unlocked by the technology.  However, this technology is restricted to gestalt empires, which can't have factions!  The intent seems to be that the Manifesti want weapons to be able to decide their own use, which for non-gestalt empires would be accomplished with the "Sapient Combat Computers" technology.  The relevant references are changed to refer to this technology and the Sapient computer components unlocked by it.

The Manifesti also want you to allow water to exist in a variety of blockers.  This mod also allows "Toxic Kelp" to satisfy the relevant demand.

## Compatibility

Because it replaces a core Stellaris file, this mod is inherently incompatible with any other mods that overwrite the same file.  Generally, any mod that alters the Manifesti faction will not be compatible with this one.  Altering other factions should work as expected because they are defined in other files.

Built for Stellaris version 3.2 "Herbert."  This mod is not compatible with achievements because it overwrites a core Stellaris file.

### When to Install

This mod can be safely added or removed from your savegame after the game has started.  It only alters the Manifesti faction and will not alter your savegame.  If you remove it, your game will work normally.

## Known Issues

None

## Changelog

* 1.0.0 Initial version
* 2.0.0 Compatible with Stellaris version 3.0.3
* 2.0.1 Update README
* 2.0.2 Remove extra linebreaks README
* 2.0.3 Fix source link
* 3.0.0 Updated for Stellaris version 3.1 "Lem" - no changes to what the mod does, just integrated the underlying game changes
* 4.0.0 Updated for Stellaris version 3.1 "Herbert" - no changes to what the mod does, just integrated the underlying game changes
* 4.0.1 Mark as deprecated - unnecessary in Stellaris 3.3 "Libra" and higher

## Bug Report

Another Stellaris player helpfully filed a bug report for this issue. Please visit the [official forums](https://steamcommunity.com/linkfilter/?url=https://forum.paradoxplaza.com/forum/threads/stellaris-3-0-3-67bf-manifesti-faction-issue.1472781/) and upvote this bug report!

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/manifesti_fix)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.
