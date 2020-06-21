
* timeline event redo
    * settlement events with dropdown and custom
    * real showdowns with selection with dropdown and custom
    * new UI
    * icons for search events

* fixed broken lion god
* slendy shouldn't replace kingsman directly...use unspecified
* campaign-specific milestones

----------------------------------------

test script
should say "right click to delete" somewhere
reimport *all* images bigger than 4k
camera view abstraction
    hunt, showdown, rules

import/export

redo all decks so archive is *in front*
sunstalker token
showdown/settlement/timeline event ICONS for the checkBoxes when adding a custom event
steam screenshots
mutually exclusive menus
hide f&t and founding stone
population UI
swap innovations / resources on settlement board
lifetime reroll token space
settlement event type on timeline -> auto show event
dependency injection
redo settlement board: settlement events, tokens, settlement locations


# High Priority
* dice tray?
* battle die rollers / end of turn / reset turn?
* sharp/devastating?
* Spidicules
* reset infinity bag for char sheets  in tut
* Reroll card
* Spawn Anything
* Spiderling/Shade fixed movement -> "Minion" type
* Message to move survivors/terrain after spawning a showdown
* "lay out cards"
* Tutorial
* Monster board auto-token support
* Tooltip states for token/flipped
* append (CE) to rest of CE cards

# Medium Priority (will do, but not next release)
* Blurred events
* Reimport CE cards
* Rescan gear
* Missing Oxidized Ring Whip
* Scan additional survivors
* Scan spiderlines
* Scan lonely fruit
* Scan resin dung ball
* Add "Drag Bar" to char sheets
* Grey models (states_)
* Multi-overlay
* CE slocs should have black background
* Table of Contents
* Two-page rules allowing easy "copy this over here"
* Lock nonsquare terrain
* Automatic innovation consequnces
* Custom life counter
* Gigalion vignette
* Strains
* Support for "Enter" to select first item in search
* Dice infinites
* Organ grinder back central filigree is a lighter color than the others...not terrible but slightly noticable.
* "Show" gear, like gloomhaven
* Slot for terrain bag
* Rethink the scripting system's abstraction for "creating decks"....we need a build deck abstraction that accepts input from multiple locations, spawns them in "the back" and then groups them and moves.
* Move resets for promo/rare/starting gear to the other side...to hard to click next to big slocs
* More space in between sloc and gear due to snapping, slocs can block gear
* Move "pack button" to below surv action so it's clearer what it affects
* Switch Innovations with Resource storage

# Possibly Will Do
* Battle UI work with weird shit like slenderman katana
* Battle UI remove duplicates for paired
* Battle UI better border
* Scan all my own models
* Rescan DK to get rid of black
* Settlement Location / Innovation "replacement" when adding CE
* Mineral gathering/herb gathering/sky fishing buttons
* Hunt event roller and rules spawner
* Cards have inconsistent sizes: disorders, backs. check everything
* Rescan monster rules
* Rulebooks board frills
* Dice rollers?
* Add additional rules indexes: legendary monsters, life
* Some easy way to reset survival actions
* Heal and Reset should reset surv actions
* Battle interface? What would we do here? End-of-round stand up stuff/flip surv actions?
* Error logging?
* Two-sided char sheet: great deeds, parents
* Rescan terrain tiles
* Expand settlement board to have the settlement flow and placeholders for endeavor tokens and settlement locations
* Redo *all curved corners* with 10/6 or 10/7
* Consider redoing survival actions with black/white and colored font
* Rescan tokens
* Redo the permanent tokens so the art is the *exact* same size...will involve resizing "permanent token" circles on player board and redoing the snap points
* Flip "innovation deck" text horizontally
* Move all reset buttons to the sides, so you can see them under stuff
* Change all rules tile colors to match the actual page art
* Fix all card color tints...they're *Grey*
* Level select for hunt/showdown doesn't fill up the whole panel
* Simplify script rotations to onyl care about y axis or flip
* Terrain tiles/anything else using a grid snap to also snap on spawn/take out of container...currently can draw directly from container and drop on board, will not snap. seems to be bypassing onDrop()
* Watcher retinue tokens
* Precomppile the tries/other indexes
* Requiring only once, and using dependency injection
* Settable attr validation in palyer/char/showdown board
* all script names underscores
* fix LK girl foot geometry

* redo rules: probably 2048 each
* better battle UI close button
* spatial indexes that support local coordinates
* ruyles ui out of global
* simplify rules search code
* rules ui button highlighting
* rules should have names as keys
* brown cursors for all text
* rename grid to snap, move to utils
* rules = { "Dragon King Rules", 4 },
* dk char sheets
* move gigalion to its own white box
    * same w/green knight
guid object caching
    also checking that != nil
battleui to use xmlui

separate UIs?

showdown and hunt should be their own things
* space for set locs/set events
    meantime move slocs to below sevents
auto keyword tokenization..silly otherwise
custom milestones (edged tonometry)

remove unused innos from decks (campaign-specific, destiny, etc)

principle labels on spots
inconsistent "SettlementLocation_" in location names
    same with sb grid
oo/modularity pass: location/locationdata
rulebook/rules ambiguity

battleui to use xmlui

hunt event deck needs tooltip

rename setup.position to setup.location

rotation should probably be renamed rotation

inits on each thing


assert(x, str) str less needed with stack traces

checkgroup = selected vs checked?

init -> load


assert vec3 shouldn't supprot numbered indexes

consistenfify locations_ and locations.
also localify
* hot keys for menus (b for battle)

get rid of terrain reset button, no need
rename iunvisible button
disable button for custom event
battle reference tooltip
setup popup confirmation: this will overwrite blah blah


addHotkey(label, method_name, trigger_on_key_up = false) - Add a bindable control. User may assign a key to it in Options->Game Keys.
showHotkeyConfig() - Shows the config window described above.
clearHotkeys() - Remove all controls created by above.

https://www.tabletopsimulator.com/news/patch-notes/v12-2-0-theme-editor-chat-filter-picture-in-picture-and-more


Gear Abilities
Currently using 1.3 version of the Whisker Harp (Catarium)
Leather Helm > Should be +2 insanity
Screaming Helm - I think the normal version is using the CE text, but it’s a very minor change.
Typos
Cat Gut Bow > “mayreduce” missing space

* potstars char sheet

battle reference title
* figure out what to do with "forest gate" spot

* real hybrid armor
promo gear expansion object

dropzone refactor

dropzones/spatial indexes should support "relative to"
    fuck that, *location* should support relative objects

cache objects instead of using guids
guids should check for deleted objects

2d/rect point primitive
location primitive

location primitive should have a find/cast that takes a tag/name and finds a dude

locl refs when they hit the ground by spawning them very low then locking on spawn or after a few frames

"nemesis encounter" text wraps weird

slenderman/potstars
editing events? should right click just edit?

25 year timeline for stars


add "game over" milestones
optional expansion timeline updates
