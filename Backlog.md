* roadmap
* fix sur tok loc
* onobjectdestroyed for survivor sheets in player: manually unlink and spit message
* pack should work for unlinked sheets
* consolidate SurvivorBox.ALLOWED_CARD_TYPES
* fixed display order on pop for fa/disorder/etc
* location tostring
* remember figurine
* new survivor bonues
* next turn should auto-move the monster controller
spawn check if survivor box exists, if so highlight
else create box and pack cards
delete: check if on player board or survivor box exists

* if user changes a survivor field to a hidden filter, then should we refresh the page?
* Figure out survivor box and add instructions
* Set population row tile to be correct length

* confirmation box should be per-player
* fix survivla/marker placement
* icon for retired
* spacing for reroll checkboxes
* all ui should use the same "object" instead of separate elem and object
* reroll token
* shield mastery should apply to everyone
* constellations sheet color
* spawning rulebooks through nav board shouldn't re-center
* fix "clear skip next hunt" button
* fix silhouettes
* replace all events with constants
* tutorial tips
    pack survivor: not deleted

unlock



UIs
setup
hunt
showdown
timeline
battle
search

Boards
deck
settlement
player
survivor
rules nav
terrain
deck
monster
population

fix silhouettes
* warm virus can't be added to timeline
move new survivor to far-right
add filegree
fix height to support 20 survivors
* lock rulebook after spawning
* fix "x" bg in search bar
* cap luck to 10
* fix broken token stacks
refactor upper/lower stats into a single function
should we show modified stats on pop?
all boxcast/cleans should not use interactable, but rather namedobject's special list
remove space between survivor ui player panels (just use one big panel)
bigger "milestone" checkboxes

* fix black card backs
* binge eating hagve
* get rid of survivor sheets entirely...just have static/two-state ones on the palyer boards
* when highlighting a single item, always pan the camera to it (make it part of Util.highlight)
* align the new archives
* tips
* fix vespertine bow
* entering 's' into the search bar produces a long list

* misc combat stuff: twilight sword
* spiderlings/lonely fruit/shades are not snapping

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

* Spawn severe injuries
* Quick camera nav locations on the bottom (hotkeyed?)
* Video tutorial
* Add a Settlement Phase Board:
    * Endeavor tokens
    * Phase guide
    * Settlement Event Deck / reshuffle/reset
    * Drawn Settlement Event
* Scan all gear
* Limit all deck grids to 4k
* Test scripting
* UI only visible to player who clicked?
* Improve search to "find/spawn anything"
* Once population sheet is gone, re-add the "show"/"layout" buttons for gear that will lay them out above the settlement board
* Hunt guide


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
* Organ grinder back central filigree is a lighter color than the others...not terrible but slightly noticable.

# Possibly Will Do
* Battle UI work with weird shit like slenderman katana
* Battle UI remove duplicates for paired
* Battle UI better border
* Scan all my own models
* Rescan DK to get rid of black
* Mineral gathering/herb gathering/sky fishing buttons
* Hunt event roller and rules spawner
* Cards have inconsistent sizes: disorders, backs. check everything
* Rescan monster rules
* Rulebooks board frills
* Dice rollers?
* Add additional rules indexes: legendary monsters, life
* Error logging?
* Rescan terrain tiles
* Expand settlement board to have the settlement flow and placeholders for endeavor tokens and settlement locations
* Rescan tokens
* Flip "innovation deck" text horizontally
* Move all reset buttons to the sides, so you can see them under stuff
* Change all rules tile colors to match the actual page art
* Fix all card color tints...they're *Grey*
* Terrain tiles/anything else using a grid snap to also snap on spawn/take out of container...currently can draw directly from container and drop on board, will not snap. seems to be bypassing onDrop()
* Watcher retinue tokens

* redo rules: probably 2048 each
* rules = { "Dragon King Rules", 4 },

auto keyword tokenization..silly otherwise

rulebook/rules ambiguity

rename setup.position to setup.location

* hot keys for menus (b for battle)

get rid of terrain reset button, no need
rename iunvisible button
disable button for custom event
setup popup confirmation: this will overwrite blah blah


addHotkey(label, method_name, trigger_on_key_up = false) - Add a bindable control. User may assign a key to it in Options->Game Keys.
showHotkeyConfig() - Shows the config window described above.
clearHotkeys() - Remove all controls created by above.

https://www.tabletopsimulator.com/news/patch-notes/v12-2-0-theme-editor-chat-filter-picture-in-picture-and-more


* potstars char sheet

battle reference title
* figure out what to do with "forest gate" spot

* real hybrid armor
promo gear expansion object

fixed terrain locking

optional expansion timeline updates

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

* Ringtail vixen card

* tolowercase all lookups (weaps, gear, toks)
* no good way to find stuff like single gorm resources
* prevent negative counters?
* don't save stuff in periodic save
redo sizes
onSubmit

* merge monsterSizes into setups, and rename setups -> monseters


lowerleft by default for all ui
* settlement -> timeline for module


* UI to use attributes.id for parents instead of .id
* Setup to do survival actions

* Move "Unused HL" to side column, put image in between
* Grey "enter survivor name" text color
* Show vs hide

* Spawn Anything

* flter -> tryObjectEnterContainer
* manually creating survivor boxes and such by coping/etc should produce a warning message
* reminder to pack survivors and complete encounter before exporting
* cleanup ui classes/addcreatefunctions
* handle deleting survivor sheets: unlink player, clear all
* interact highlight objs
* sort help cmds
* clean up ui to use classes properly
