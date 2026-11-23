# WolfAccess: player guide

WolfAccess makes The Wolf Among Us Remastered (Steam) playable with a screen reader. It reads the menus, the subtitles and the dialogue choices, lists the things around Bigby, walks him to them, guides you through the fights and describes the scenes while they play.

It works with NVDA, JAWS and Windows Narrator, with the keyboard or an Xbox-style controller.

Download the latest version: https://github.com/jeremdo95/WolfAmongUsAccess/releases/latest

## Contents

- What you need
- Installing
- Starting the game
- Language
- Settings keys
- Menus
- Dialogue and choices
- Exploring: the scanner
- Walking to a thing
- Zones you walk into
- New things and changing actions
- Close-ups
- Choosing where to go
- Fights and quick-time events
- Mashing
- Sounds
- Audio description
- Bonus menu
- Reporting a problem
- Uninstalling
- Credits and license

## What you need

- The Wolf Among Us Remastered on Steam, on Windows, 64-bit.
- A screen reader: NVDA, JAWS or Narrator.
- Nothing else to install.

## Installing

1. Close the game.
2. Unzip WolfAccess-1.1.zip somewhere other than the game folder, for example on the Desktop. Windows' "Extract All" puts its content in a new folder, WolfAccess-1.1: do not extract it into the game folder, or the mod ends up one folder too deep and does not load.
3. Open the extracted folder. Select its two folders, Archives and WolfAccess, and copy them (Ctrl+C).
4. Open the game folder. In Steam: right-click the game, Manage, Browse local files. It is usually C:\Program Files (x86)\Steam\steamapps\common\The Wolf Among Us Remastered.
5. Paste (Ctrl+V). Windows asks whether to merge the Archives folder with the game's own: say yes. No game file is replaced.

Updating from an older version: follow the same steps. When Windows says the files already exist, choose to replace them. Your settings (F2 to F5) are kept.

## Starting the game

- Start the game from Steam as usual. Nothing else to launch: the mod starts its companion program, WolfAccess.exe, by itself, and closes it when the game closes.
- After a few seconds you hear "WolfAccess loaded." Then the title screen is read: press Enter or Start.
- If you hear nothing, check that the two folders are in the game folder, then see Reporting a problem.

## Language

- The mod speaks French when the game is set to French, and English for every other language.
- Change the game's language in its settings menu: the mod follows at once.

## Settings keys

These keys work everywhere, in menus and in the game. Each choice is remembered for the next time.

- F2: speaker names on or off. When on, each subtitle starts with the name of the character who speaks.
- F3: audio description on or off.
- F4: quick-time event sounds on or off.
- F5: fight slow motion on or off. When off, fights run at the game's own speed.
- Shift+F8: report a problem (see Reporting a problem).

## Menus

- Every menu is read: title screen, main menu, settings with their values, save slots, the chapter list, the pause menu, pop-ups and the death screen.
- Keyboard: arrows to move, Enter to choose, Escape to go back. With a controller: the game's own buttons (d-pad, A, B, Start).
- Save list: Delete erases the selected save. With a controller: Y. The game asks you to confirm.
- At the start of an episode, the episode's intro text is read.
- Statistics at the end of an episode (what other players chose): Up and Down arrows go through them.

## Dialogue and choices

- Subtitles are read as they appear, whole lines, with the speaker's name if F2 is on.
- Lines the game shows no subtitle for are not read, as in the game.
- When choices appear, they are read in a list.
  - Keyboard: each choice starts with its number ("1, ..."). Press 1 to 4 to answer at once, or browse with Up and Down arrows and answer with Enter.
  - Controller: each choice starts with its button ("X, ...", "B, ...", "Y, ...", "A, ..."). Browse with d-pad up and down, answer with that button.
- As in the game, choices have a time limit. Silence is one of the answers.

## Exploring: the scanner

When you control Bigby, the scanner lists the things and characters around him, nearest first.

- Keyboard:
  - Page Down: next thing.
  - Page Up: previous thing.
  - Home: say the chosen thing again.
  - Enter: use its first action.
  - 1 to 4: use action 1 to 4.
  - Backspace: walk to it.
  - Arrows or W, A, S, D: walk Bigby yourself.
- Controller:
  - D-pad down: next thing.
  - D-pad up: previous thing.
  - D-pad left: say the chosen thing again.
  - D-pad right: walk to it.
  - The button named with each action uses it (A, B, X, Y, LB, RB).
  - Left stick: walk Bigby yourself.
- Each thing is said with its name, its distance and its place in the list, then its actions. Example: "Matchbook, 4 meters, 1 of 4. Pick Up".
  - Keyboard: when a thing has several actions, each is said with its number, 1 to 4.
  - Controller: each action is said with its button, for example "A: Pick Up".
- If the thing is too far to use, Enter (or its button) walks Bigby there first, then uses it.
- The scanner keys do nothing while Bigby is not under your control: during scenes, dialogue, actions and quick-time events. A sound tells you when control comes back (see Sounds).

## Walking to a thing

- Backspace (keyboard) or d-pad right (controller) walks Bigby to the chosen thing, using the game's own paths, at normal speed.
- On arrival you hear "Arrived:" with the thing and its actions.
- If the thing cannot be reached you hear how close Bigby got ("As close as possible: ... is out of reach, 5 meters away.") or "Stuck" with the distance.
- Moving Bigby yourself, with the keys or the left stick, stops the walk ("Walk interrupted").

## Zones you walk into

Some places start a scene or move Bigby only when he walks into a certain spot: a doorway, stairs, a corner of a room. The scanner lists these spots as "Zone" followed by a name, for example "Zone go down to Toad's living room".

- Walk to a zone with Backspace, Enter or d-pad right. Walking into it runs its scene or moves Bigby, as in the game.
- If Bigby arrives and nothing happens, the mod starts the zone for you.
- If the walk stops short, you hear "Press again to trigger the zone." Walk to it again within 30 seconds and the mod starts it.
- A zone whose scene was already played is not started again: you hear "This scene was already played: zone removed from the list." It comes back when another zone runs or Bigby changes place.
- If you feel stuck and the scanner lists only zones, try them: one of them is usually the way on.

## New things and changing actions

- When a new thing appears after an action (a clue, a character who walks in), you hear "New:" with its name and distance. The scanner's choice stays where it was until you have used the chosen thing.
- When the actions of the chosen thing change after you use it, its name and new actions are said again.

## Close-ups

- Some actions show a close-up (the head at the crime scene, a book). You hear "Close-up." The scanner then lists only what the close-up shows.
- Leave it with Backspace (keyboard) or B (controller), when the game allows it.
- In a book, the page number is said. Turn pages with Left and Right arrows, or with the left stick, LB or RB.

## Choosing where to go

When the game asks where Bigby goes next, you hear "Choose a place" and both places.

- Keyboard: Left or Right arrow to pick a side, then Enter to confirm.
- Controller: X for the left place, B for the right one.
- Some big choices have three sides: pick with the arrows, then Enter.

## Fights and quick-time events

- During a fight, each prompt is said as it appears. Fights run in slow motion to give you time to answer; F5 turns the slow motion off or back on. A direction sound plays with each prompt (see Sounds).
- Keyboard: every prompt is said as a direction ("left", "up"...). Press that arrow, or W, A, S, D.
- Controller: an attack prompt is said by its button (A, B, X or Y), a move prompt by its direction (d-pad or left stick).
- When the fight lets you pick a target, the scanner lists the targets: parts of your opponent, things to grab or throw. Choose with the scanner keys and use with Enter or the named button.
- In a chase, a quick decision may be said as "Choice:" followed by what lies on each side, for example "on the left" and "on the right". Press that direction within a few seconds.
- Some moments ask you to hold a direction to go forward: you hear "Hold the Up arrow or W to move forward." When Bigby already walks on his own, you hear "Hold the Up arrow or W to go faster."
- If Bigby dies, you hear "Bigby is dead." and the death screen is read. The game resumes at its last checkpoint.

## Mashing

- When you must hit a button fast, you hear "Press Q fast!" (keyboard) or "Press A fast!" (controller).
- Keyboard: Q, A or Space all work, on any keyboard layout. Controller: A, B, X or Y.
- A sound plays when the mashing is over. Some mashes last as long as the scene needs, however fast you press.

## Sounds

- Control lost: a short falling sound when Bigby leaves your control (a scene, a dialogue, an action begins).
- Control back: a short sound when you can move and use the scanner again.
- Quick-time event directions: left and right on their side of the stereo field, up high, down low. F4 turns them off.
- End of a mash: two rising notes.

## Audio description

- The mod describes what happens on screen: who comes in, what characters do, how places and new characters look. Descriptions are said between the lines of dialogue.
- The whole game is described, all five episodes, and the five deleted scenes of the Bonus menu.
- F3 turns the descriptions off and on.

## Bonus menu

All of it is read: Book of Fables (each tile opens its page), image galleries, deleted scenes, making-of videos and the Telltale account screen.

- Videos: Enter pauses and resumes, Left and Right arrows go back and forward, Escape leaves.
- Deleted scenes: choose one in the list and press Enter. Each is played with its subtitles and its audio description.

## Reporting a problem

If something is silent, wrong or stuck, press Shift+F8 at that moment.

1. You hear "Problem report." and the game pauses.
2. A window opens, and your screen reader reads its edit box: describe the problem in a few words. Say what you did and what you expected.
3. Press Enter to send. The information needed to understand the problem is joined to your message.
4. Escape, or the Cancel button, closes the window without sending anything. Either way you are back in the game, unpaused, after a second or two.

## Uninstalling

1. Close the game.
2. In the game folder, delete the WolfAccess folder.
3. In the game's Archives folder, delete the file _resdesc_50_WolfAccess.lua and the folder WolfAccess. Leave every other file there: they belong to the game.

## Credits and license

- WolfAccess is made by jeremdo95, under the MIT License (see LICENSE.txt).
- Its design follows TWDAccess, the screen reader mod for The Walking Dead: The Telltale Definitive Series, by Kongster90.
- Speech goes through the Prism library (Mozilla Public License 2.0). The companion program bundles the .NET runtime (MIT License). See THIRD-PARTY-NOTICES.txt.
- The Wolf Among Us Remastered and everything in it belong to their owners. The mod ships none of the game's files.
