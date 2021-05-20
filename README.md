# kdm-tts
Source for my Kingdom Death: Monster mod for Tabletop Simulator (https://steamcommunity.com/sharedfiles/filedetails/?id=2112101994)

# Version 1.0
If you're experiencing search/preview issues, try clearing out your mod data directory and see if it continues.
* Replaced Population UI with Survivor Board
    * 3d board instead of 2d UI. This allows the board to be as large as needed since we're not constrained by screen size.
    * Shows 20 survivors per page instead of 5.
    * Shows full survivor sheets, along with cards: FAs/Disorders/Abilities/Injuries.
    * Added filters to hide dead survivors, retired survivors, skip next hunt, and several others.
    * Added "Move to End" and "Move to Beginning" buttons to more easily sort your survivors.
* Added "Markers" to survivor sheets: you can now mark survivors with one of 5 different abstract icons:
    * Yellow Star
    * Green Triangle
    * Blue Square
    * Red Circle
    * Purple Diamond
    * (Blank, no marker)
    * Use these markers to designate classes of survivors, for instance I might designate my main hunters with Yellow Star, and all my injured survivors with the Red Circle.
    * Added filters for each marker on the Survivor Board, so you can, for example, hide all of your injured survivors.
    * Left click to cycle forward through markers. Right click to cycle in reverse.
* Added notes to all survivor sheets.
* Removed milestone reminders from survivor sheets (age, bold, insight, etc)
* Added milestone board with shortcut buttons to milestones (age, bold, insight, etc). This takes you to the appropriate event for different campaigns (insight for PotLantern, awake for PotStars)
* "Pack Survivor" button replaced with "Back to Settlement": no longer creates the intermediate survivor box.
* Added instructions on Survivor Boxes and Survivor Board for how to modify cards without having to spawn the survivor on a player board.
* Added two more ability slots on player boards
* Player boards now support stacking cards (Fighting Arts/Disorders/Abilities/Injuries) in the same slot. You can use this if a survivor has more cards than available slots.
* Rules now lock when spawned.
* Hunt/Showdown buttons in the timeline now goes directly to showdown/hunt (with a confirmation popup), instead of taking you to the hunt/showdown setup screen.
* Fixed blank space when searching for a term with more than 5 results.
* Spiderlings, lonely fruit, and sunstalker shades now snap to terrain.
* Spiderlings, lonely fruit, and sunstalker shades now show movement overlays.
* Ability to change player colors: right click your player marker and "set color tint" to the color of your choice. Your Battle UI marker and player figurine will automatically be updated with the same color after a few seconds.
* Starting a new campaign now spawns Allister/Ezra/Lucy/Zachary figurines on player 1/2/3/4 markers.
* "First Day" settlement event card now spawns face up next to the settlement events deck when starting a new campaign.
* Removed blank space between Battle UI player sections, so it takes up a bit less space.
* The Flower Knight "A Warm Virus" event can now be added to timeline.
* "Next Turn" button now automatically moves Monster Controller card to next player with a living survivor.
* Moved survival tokens and player marker/circle to player boards. This frees up more space above the player board for resource cards, status cards, etc.
* Export now supports card stacks: no more having to separate one card per slot
* Import now automatically creates survival tokens.
* Improved console commands overall
* Fixed lots of broken gear (thanks Mei for the fixed images!):
    * Vespertine Bow: 4 -> 6 strength
    * Lantern Glaive: added missing "Reach 2"
    * Bone Dagger: added missing "Paired"
    * Final Lantern: fixed incorrect wording
    * King Spear: added missing "Bone" keyword
    * Dragon Gloves: 5 -> 4 armor
    * Griswaldo: fixed misspelled "Finesse" keyword
    * Replica Flower Sword: added missing "Devastating 2" and "you cannot dodge" rule
    * Prism Mace: added missing strength token rule
    * Sunspot Lantern: fixed misspelled "away"
    * Calcified Zanbato: fixed swapped affinities
    * Scrap Dagger: fixed red affinity: left -> down
    * Whistling Mace: added missing "Whip" keyword
    * Hunter Whip: added missing up-blue affinity
* Fixed "Vespertine Foil" not showing up in Battle UI
* Fixed constellations not being respawned in survivor box.
* Fixed Lonely Tree showdown positioning.
* Fixed Gorm showdown positioning.
* Fixed terrain bag giving errors when you pickup/drop it.
* Minor fixes to token stacking bugs.

# Roadmap
* Documentation / video tutorial.
* Speed up load times. 1.0 slowed things down due to using XML UI for everything.
* White box content and setup in campaign UI.
* Strains. Need UI to incorporate which strain FAs at the start of a new campaign. Need to think how to best do this.
* Get rid of unused terrain reset button.
* Battle UI button tooltips
* Hunt event buttons: random hunt event (show roll), forest gate, overwhelming darkness, sky fishing, herb gathering, mineral gathering.
* Monster-specific quotes.
* Lock terrain after setting up showdown.
* Fixed Binge eating hagve misspelling.
* Add reroll token and a slot on the token board.
* Constellation and import/export boards have slightly different colors than the rest of the boards.
* Rescan all gear.
* Rescan terrain tiles.
* Rescan tokens.
* Rescan rules, especially expansions.
* Scan Spidicules.
* Scan Resin Dung Ball.
* Scan Spiderling.
* Scan Lonely Fruit.
* Scan more survivors: goal is to do at least one new armor set per version.
* Add tooltips before loading.
* Move search, battle UI, and next turn into a single unified and consistent main menu, hideable by the existing button.
* Evasion on Battle UI.
* Dice roll buttons on Battle UI?
* Custom severe injury board with buttons to spawn cards/tokens for each table entry.
* Support for PotStars constellations on survivor sheets
* "Spawn Anything": similar to the existing search for rules, but search for any item.
* Timeline custom hunt event.
* Add more decorations: Rules Nav, Survivor Board
* Add all glossary terms to rules search.
* Add all rules subsections to rules search.
* Remember player figurine when packed.
* Dedicated board for new survivor bonuses instead of the free-form text, so it's automatically applied.
* Icon for retired.
* "Has Reroll" filter.
* "Lay out gear" button for settlement locations, similar to how the Gloomhaven mod does it.
* Custom "life" counter.
* Ability to add expansions to existing campaign.
* Redo hunt/showdown UI to only show available quarries.
* Add "Priority Target" tile into the showdown board.
* Watcher retinue tokens.
* Scan stone face bases.
* Move "Unused HL" to side column, put image in between
* Deprecated: filter -> tryObjectEnterContainer
* Manually creating survivor boxes and such by coping/etc should produce a warning message for new players.
* Reminder to pack survivors and complete encounter before exporting
* Bigger font for export/import campaign board.
* Code: Always validate Archive.Take and Container.Take...get rid of "allowMissing" and add actual validation.
* Board background color. Had a few requests to make it easier to see against the black background.
* Slots for survival token stacks on token board.
* White Lion prologue "known" cards face up
* 5/6th player. Will be very difficult and time consuming to make this work cleanly.
* Add ability card for Gigaslayer (from Gigalion).
* Export/import should record permanent tokens.
* Packing/unpacking a survivor should include cursed gear.

# Console Commands
You can access console commands by entrying a chat message starting with '>' (no quotes).
It must be in game chat, not the TTS system console.
To see a list of commands and their descriptions, type:
```
>help
```
