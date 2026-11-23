# Changelog

Numbers follow MAJOR.MINOR.PATCH.

- **Major**: changes what kind of game this is, or replaces a core system.
- **Minor**: adds or remakes gameplay. A release with new features and fixes is a minor.
- **Patch**: fixes, tuning and housekeeping only, with no new gameplay.

Versions 1.0.0 to 3.5.0 were assigned afterwards, one for each round of work.

## 3.8.0
Fewer words, a guide for new players, and one campfire in the middle.
- First-time guide: the first time something appears in a run, the game pauses, zooms in and names it in one line. It covers the campfire, frozen villagers, gold ice, ice spikes, wolves, torches, the rainbow power and the cold. Each tip shows once.
- The campfire stays in the middle of the board instead of moving after each bank. Runs are a little easier, and old friend codes from 3.7 no longer match.
- Every mini-game's instructions cut to one short line.
- Village troubles, raid warnings, protection notes, run-end tips and village screens rewritten shorter.
- Fixed: outdated tips that said a run relights the hearth. It is relit by stoking.

## 3.7.3
- Infirmary remedy game: "Watch" and "Your turn" now appear as big words over a dimmed screen and fade away, like the instructions. Taps while "Your turn" is fading are ignored, not counted as mistakes. The timer is 7 seconds longer to make up for the pauses.

## 3.7.2
Fixes.
- Stoking the hearth: the pile scrolls so the moving log stays at 40% of the screen on any phone. Before, short screens lost it under the top bar after about 9 logs.
- Raids open with a large "Raid X" banner (and "Big raid!" or "Warband!") that fades as the fight starts. The enemy count is now small, top right.
- Cutting ice: strain never eases within a block, so every rush or wobble adds up. Strain grows a little slower to keep it fair.

## 3.7.1
Fixes.
- Thought bubbles sit on the villager's head and follow their walk.
- A villager who walks behind a building hides their bubble too, instead of leaving it floating.
- Shivering is gentler, comes in short bursts, and each villager shivers in their own rhythm.
- Fixed: since 3.7.0, buildings could be drawn as black circles (a drawing helper was accidentally replaced). The build now refuses duplicate function names.

## 3.7.0
Villagers show how they feel.
- Thought bubbles over villagers: happy, love, cold, angry, sad, sick or hungry, depending on how the village is doing.
- With the hearth out, villagers turn icy blue, shiver, puff frosty breath, and most think cold, angry or sad thoughts.
- Sick villagers look green and slow down.
- "Get upgrades first" during a raid opens a "Gear up" shop with only raid upgrades and the armoury.
- More space between the Play or Relight button and the Daily fire and Friend's code buttons, and the Relight label fits inside its button.

## 3.6.0
The hearth as lifeline, more village trouble, and raids that keep getting harder.
- With the hearth out, someone falls ill every 3 hours, leaves every 6 and dies every 12. Specialists start leaving after a day.
- While the hearth is out, Play, Daily fire, jobs and building all wait: every button relights it with the stoking game.
- Coming back to a cold village shows who fell ill, left or died, with "Relight the hearth" as the only button.
- Sickness: it spreads, sick people cannot work, and without an Infirmary some die. The Infirmary slows it, heals faster and treats.
- New trouble: "Sickness spreading". Troubles now come every 5 to 12 minutes of play instead of every 6 to 14 hours.
- Raids get tougher every time: more enemies, much more health, faster, with the raid number shown.
- New enemies as raids go on: brutes that smash the gate, and shamans that heal the enemies near them.
- The bow sometimes jams for 0.7 seconds.
- Fixed: arrows could hit enemies that were still above the screen.

## 3.5.1
Housekeeping and iPhone support. No gameplay changes.
- The version number is shown on the home screen and comes from package.json.
- The build stops if the version has no entry in this file.
- Added this changelog, with every earlier release numbered.
- Full-screen Add to Home Screen support for iPhone, with an app icon.
- Long presses no longer bring up the iPhone's text callout during play.

## 3.5.0
Raid upgrades and pressure.
- Six raid upgrades: Quick hands, Sharp heads, Fire pots, Long shots, Twin bows, Spike pits.
- Big raids and Warbands, with shielded enemies, runners and a chief. They pay more.
- "Get upgrades first" on the raid warning opens the Shop and returns to the fight.
- Enemy toughness now rises steeply, so gear matters later on.
- Fixed: winning a raid could still report that the raiders broke through.
- Fixed: logs cut off while stoking the hearth appeared near the top of the screen.
- Fixed: hammer game timing. Thin target line, every nail on a drum beat, smoother clock, and tapping along with the count tunes out sound delay.

## 3.4.0
Placement, success scenes and hungrier wolves.
- Decorations can be placed and moved anywhere sensible in the village.
- Each of the 17 mini-games ends with its own success scene.
- Raids show how many enemies are left and end clearly.
- New land is bought from the map; the Shop takes you there.
- Wolves go for villagers first and take one per second until you reach a campfire.
- Jobs need their building to exist.
- Fixed: building floors flickering when villagers walked behind buildings.

## 3.3.0
A bigger village economy.
- More buildings with jobs and mini-games, for 17 mini-games in all.
- Expand beyond the trees by exploring four new regions.
- Frequent raids, defended with weapons and armor.
- Shop with an armoury, decorations, village upgrades and trading.
- Wolves chase you, and reaching a campfire shakes them off.
- Quick jobs appear on the map far more often.
- Hammer game rebuilt on the audio clock, with a real hit and dancers.
- Fixed: villagers stuttering as they walked.

## 3.2.0
Mini-games that feel different.
- Each mini-game reworked to match its task.
- New rhythm hammering game.
- Ice cutting now needs a steady hand or the block cracks.
- Fixed: villagers teleporting and appearing from places other than cabins.

## 3.1.0
Trouble in the village.
- Events: snowstorms, wolf attacks, fires, landslides, disagreements and slackers.
- Injured villagers who need treatment.
- First mini-games for events and jobs: shovelling, fishing and hunting.
- The more people you lead, the slower you move.
- Fixed: new buildings not appearing until the screen refreshed.
- Paths only lead to buildings that exist, and chests are rarer.

## 3.0.0
The 2.5D village.
- Building upgrades replaced by a zoomable, interactive village with levels, timers and builders.
- Chests with cosmetics and upgrades.
- Golden Aurora power that smashes wolves and ice and pauses the cold.
- Wolves and ice appear faster as a run goes on; campfires and torches give less time.
- Fixed: avatar tiles changing when only the preview should.

## 2.0.0
From arcade game to a village to look after.
- Daily and weekly missions with rewards.
- Rescued villagers become your population, with food, water and shelter needs.
- Specialists: fisherman, hunter, carpenter and more. Neglected villagers die or leave.
- Customisable avatar: hat, clothing and eyes.
- Save format upgraded, keeping players' earlier progress.

## 1.0.0
First playable.
- Lead a growing line of frozen villagers to the fire, with instant replay, daily runs and friend codes.
- Runs on entry-level phones, with saves on the device.
