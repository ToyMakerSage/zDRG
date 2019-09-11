# zDRG v0.73
Zen Dragoon - A Triggernometry Trigger Toolkit for Dragoons in FFXIV 5.X
[Video Demonstration](https://streamable.com/nm470)

## Disclaimer
zDRG is currently in pre-release state and active development.

While functional, it is not yet complete, has not been configured with user modification in mind, nor has comprehensive testing and debugging been done.

You use zDRG in it's pre-release form understanding that and knowing that versions prior to the 1.0 release, will require a good amount of modification and tweaking to be fit for use for other users.

The code base on this github while in pre-release is intended for people to be able to draw ideas from for their own projects, provide feedback and suggestions or to be forked for people to make their own things based off zDRG.

zDRG v1.0 will be built with a focus on for use by users other than myself, with easy configuring and modification.

## Feature List
zDRG's Features will be individually toggleable by version 1.0, but currently are all enabled when in use.
* Missed positional audio alerts
* Responsive single buttons for each combo (Debuff, Full Thrust and AoE combos)
* Jump and Mirage Dive merged
* Buff/Debuff Timer Tracking
* GCD Tracking

## Requirements
* Final Fantasy XIV (Duh)
* [Advanced Combat Tracker](https://advancedcombattracker.com/)
* [Triggernometry](https://github.com/paissaheavyindustries/Triggernometry)
* [Creation of in-game macros to facilitiate the button bloat reduction feature](https://github.com/ToyMakerSage/zDRG/blob/master/Docs/In-Game%20Macros.md)

## Installation
1. Open up ACT navigate to the Triggernometry tab
1. Click "Import"
1. Select "Load from file or URI"
1. Enter the following URI into the field: https://raw.githubusercontent.com/ToyMakerSage/zDRG/master/Triggers/zDRG.xml
1. Click Next
1. Click Import

## Known Issues
* The missed positional audio cue is incorrectly triggered on the 5th action of the debuff and full thrust combos
* Regex can be further refined to even further reduce backtracking in Regex processing

## Special Thanks
zDRG was inspired by [Fryte Avarise of Gilgamesh](https://www.twitch.tv/fryteavarise)'s [SMN Button Bloat Triggers](https://docs.google.com/document/d/1IR5O7kPxeTAb4qZaL4CVNyNCWBcAExkwtnyjYb5bItQ/edit?usp=sharing)
