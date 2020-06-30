* Added version printed at the start of game
* Fixed hunt not spawning monster resources
* Shrunk size of quarry text so longer names will fit (Screaming Antelope / DBK were getting truncated)
* Fixed "The Lonely Tree" terrain model not snapping
* Fixed custom showdown timeline events overwriting the name with "Nemesis Encounter"
* Manhunter expansion no longer preemptively adds special showdowns to the timeline.
* Fixed evasion not clearing on showdown cleanup
* Add lifetime reroll:
    * Option: checkbox on the char sheet
    * Option: token, similar to survival token
    * Option: ability card
* Redo of the main boards:
    * Move "reset" buttons for decks to the side and give more space
    * large showdown board
    * Token board off to the side
    * More terrain and trait slots
    * Clearly labelled ai/hl and discard decks
    * player boards tighter
    * player boards closer to showdown board
* Better battle reference
    * Full survivor stats
    * Ability to show/hide F&T and founding stone, or any piece
    * Show/hiude buttons with tooltips and "show all"
*
-------------------------------------------------------------------------


* misc combat stuff: monster claw, twilight sword, weapon profs
* don't save stuff in periodic save
* re-enable non-nemesis monsters in showdown event search
* Add suirvival actions to settlement sheet
redo sizes

* Constellation Tracker

* Config menu
    * Lock/unlock boards
    * Player movement overlays
    * Monster movement overlays
    * Auto token stats
    * Auto armor
    * Auto deck reset
    * Auto settlement location gear
    * Auto setup timeline
    * Auto setup expansion timeline
    * Auto setup innovations
    * Monster Grid Snapping
    * Terrain Grid Snapping

* Large notes field on back of char sheet
* Menus should be mutually exclusive: clicking on one should close the others
* Fix broken multi-line notes        
* two armor sets keep one forever


* Shrink "Permanent Token" sizes
* Video tutorial
* Export/Import saves
* Swap Innovations and Resources on Settlement Board
    * Indicators for principles
    * Automatic consequence drawing
* Add a Settlement Phase Board:
    * Endeavor tokens
    * Phase guide
    * Settlement Event Deck / reshuffle/reset
    * Drawn Settlement Event
* Move player board closer to main board
    * Move tokens to the side
* Redo deck board:
    * Reset buttons on the side
    * Archives closer to the actual decks
* Scan all gear
* Limit all deck grids to 4k
* Test scripting
* Hunt/showdown camera movement
* UI only visible to player who clicked?
* Population UI
* Test Script
* Add "right click to delete" somewhere on the settlement timeline
* Improve search to "find/spawn anything"
* Once population sheet is gone, re-add the "show"/"layout" buttons for gear that will lay them out above the settlement board
* Monster board token support


# High Priority
* dice tray?
* battle die rollers / end of turn / reset turn?
* sharp/devastating?
* Spidicules
* reset infinity bag for char sheets  in tut
* Spiderling/Shade fixed movement -> "Minion" type
* "lay out cards"
* append (CE) to rest of CE cards

# Medium Priority (will do, but not next release)
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
* Custom life counter
* Gigalion vignette
* Strains
* Support for "Enter" to select first item in search
* Dice infinites
* Organ grinder back central filigree is a lighter color than the others...not terrible but slightly noticable.
* Slot for terrain bag
* Move resets for promo/rare/starting gear to the other side...to hard to click next to big slocs
* Move "pack button" to below surv action so it's clearer what it affects

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
* Flip "innovation deck" text horizontally
* Move all reset buttons to the sides, so you can see them under stuff
* Change all rules tile colors to match the actual page art
* Fix all card color tints...they're *Grey*
* Terrain tiles/anything else using a grid snap to also snap on spawn/take out of container...currently can draw directly from container and drop on board, will not snap. seems to be bypassing onDrop()
* Watcher retinue tokens
* Precomppile the tries/other indexes
* Requiring only once, and using dependency injection
* Settable attr validation in palyer/char/showdown board

* redo rules: probably 2048 each
* better battle UI close button
* spatial indexes that support local coordinates
* rules ui button highlighting
* rename grid to snap, move to utils
* rules = { "Dragon King Rules", 4 },
guid object caching
    also checking that != nil
battleui to use Ui

auto keyword tokenization..silly otherwise

remove unused innos/slocs from decks (campaign-specific, destiny, etc)

inconsistent "SettlementLocation_" in location names
    same with sb grid
rulebook/rules ambiguity

rename setup.position to setup.location

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


faq:
    3d terrain
    custom cards
    delete an event
    packing















    Upcoming Feature Brainstorm (post suggestions in comments/PM me!):
    * A video tutorial
    * Spidicules model
    * Spiderling model
    * Lonely Fruit Model
    * Dragon King texture cleanup
    * Custom "Life" counter with a UI counter.
    * *Either*: 100-card Hunt deck with the hunt events on the card *OR* auto-spawning the hunt even rules when you flip a card.
    * More showdown automation: resetting survival actions
    * Automatic locking terrain after starting a showdown.
    * More survivor models! I plan on scanning in many of my 50+ survivor minis...I have this idea where you can drop a survivor model on your player board and it will then become the "designated" model for that player. It's base would turn the appropriate color and the previous mini for that player would have a black base. This way you can 'assign' survivors to players arbitrarily.
    * Bette resin dung ball scan. Currently it's just a sphere.
    * Custom bases with stone faces and such.
    * Better infinite containers for dice. The blue bags just suck!
    * Rescans galore: I've done all the cards, but need to rescan terrain tiles and expansion rulebooks.
    * An extended survivor system for more functionality between the individual survivor sheets and the big survivor sheet.
    * A clean way to automatically do innovation consequences.
    * Gigalion vignette
    * Strains and milestones!

zone wait for initial objects is a hack
