# Overview

Are the Manifesti extremely unhappy with you?  This mod will help you make them quite a bit happier by fixing the impossible-to-fulfill
"Autonomous Munitions" demand.  Please note that part of the demand _also_ requires having 0 slave armies and 0 undead armies - something
that seems to be intentionally left vague in the tooltip by the developers.

# Changes

This mod replaces the `pop_faction_types\03_manifesti.txt` file that defines the Manifesti faction.  The only changes are to
replace the conditions to satisfy the "Autonomous Munitions" demand.  It previously was requiring the technology "Autonomous Combat Computers"
and at least 1 ship with a computer component that was unlocked by the technology.  However, this technology is restricted to gestalt empires,
which can't have factions!  The intent seems to be that the Manifesti want weapons to be able to decide their own use, which for non-gestalt empires
would be accomplished with the "Sapient Combat Computers" technology.  The relevant references are changed to refer to this technology and the Sapient
computer components unlocked by it.

## Compatibility
 
Because it replaces a core Stellaris file, this mod is inherently incompatible with any other mods that overwrite the same file.  Generally,
any mod that alters the Manifesti faction will not be compatible with this one.  Altering other factions should work as expected because they
are defined in other files.

This mod is not compatible with achievements because it overwrites a core Stellaris file.

## Known Issues

* None

## Changelog

* 1.0.0 Initial version
* 2.0.0 Compatible with Stellaris version 3.0.3
* 2.0.1 Update README

## Bug Report

Another Stellaris player helpfully filed a bug report for this issue. Please visit the [official forums](https://steamcommunity.com/linkfilter/?url=https://forum.paradoxplaza.com/forum/threads/stellaris-3-0-3-67bf-manifesti-faction-issue.1472781/) and upvote this bug report!