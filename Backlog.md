# Major Features
* Population UI Screen
    * New screen replaces the old population sheet.
    * UI is automatically updated when you change survivor sheet stats or add/remove fighting arts/disorders/abilities/injuries.
    * Similarly, the survivor sheet is automatically updated when you make changes in the Population screen.
    * Got rid of the old "packing" mechanism where it spawned a bag. Instead creates a small "survivor box".
    * You can add/remove cards from a packed survivor box and the UI will correctly update the population screen
    * You can delete a survivor box completely and later respawn the box (with all cards) from the Population screen.
        * NOTE: This currently doesn't capture gear! If you have a Twilight Sword or Lovelorn Rock, don't put it in your survivor box then delete the box, expecting it to respawn. Only cards like FAs/disorders/etc will be respawned. Basically everything you see in the Population screen.
    * You create new survivors in the UI, *not* by dragging a new survivor sheet.
    * You can delete survivors in the UI as well.
    * You can change the order of survivors in the UI.

* Import/Export of campaigns
    * Inside the "Setup" button menu
    * Go to the "Export" tab to export your game to a text string.
    * Go to the "Import" tab of the latest mod version and paste your old save. The mod will setup your campaign: timeline, survivors (including FAs, disorders, etc), player board gear, innovations, resources, settlement board gear, and settlement locations

    * IMPORTANT: This feature only exports items in their "labelled" slots. For example if you have a Monster Bone and it's not on one of the "Resource" spaces on the settlement board, it won't get exported.
    * CHECK YOUR CAMPAIGN BEFORE AND AFTER IMPORTING!

* Redo of the main boards:
    * Move "reset" buttons for decks to the side and give more space
    * Larger showdown board and models
    * Token board off to the side instead of below
    * Player boards closer together and to the main board
    * More terrain and trait slots
    * Clearly labelled ai/hl and discard decks
    * Survival action token reposition: now in front of the player boards
    * Swapped Innovations and Resources on Settlement Board
    * Indicators for principles

* Battle Reference / UI Improvements
    * Click the "ZZZ" button to mark a survivor as turn done
    * Click the "Next Turn" button on the left side of the screen to reset all survivors turns and automatically flip all survival tokens
    * Ability to show / hide individual gear. Click the "eye" button next to a weapon to hide it. Click the "eye" button on the top-left of the battle UI to show all hidden weapons.

* Monster token auto calculation
    * (Finally)

# Minor Features / Bugfixes
* Slightly increased color contrast on UIs by lightening the "light brown" color
* Fixed hunt not spawning monster resources
* Shrunk size of quarry text so longer names will fit (Screaming Antelope / DBK were getting truncated)
* Fixed "The Lonely Tree" terrain model not snapping
* Fixed custom showdown timeline events overwriting the name with "Nemesis Encounter"
* Manhunter expansion no longer preemptively adds special showdowns to the timeline.
* Fixed evasion not clearing on showdown cleanup
* Tokens now work on weapons: if you want to give +1 accuracy to Fist & Tooth only, just drop the token on the gear.
* Fixed settlement notes
* Fixed Hollowpoint Arrow/Beast Knuckle weapon stats
* fixed CE gear not showing up at start of game in sloc slots
* Fixed big/small state 2 cards: Final Lantern and Butcher Cleaver
* Watcher showdown starts with Retinue survivor statuses in play in front of player board
* Renamed "Unused Basic/Advanced/Legendary/Special AI" slots to just "Basic/Advanced/Legendary/Special AI"
* Made copies of 2-state Calcified gear in each bag
* Year added to timeline
* Fixed/added gear images:
    Oxidized Lantern Helm
    Screaming Horns
    Catgut Bow
    Hours Ring
    Whisker Harp
    Leather Helm
    Oxidized Ring Whip
* Updated Shield Proficiency to add +1 all armor
* Re-enabled non-nemesis monsters in showdown event search
    * changed hunt vs showdown
* Fixed a bug with terrain spawning with wrong rotation
* Main menu repositioned and collapsible/expandable
* Fixed monster evasion calculation: was flipping +1/-1
* Added version printed at the start of game

-------------------------------------------------------------------------


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
