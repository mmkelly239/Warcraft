# Changes

<p align="justify">This file describes all the changes made to the Yeti-Bots Warcraft software. As of right now, this includes Vision, Sonar and Wild-Catch. These changes are separated by version number and sorted from the most recent changes to the oldest. Please note that minor changes might not show up in this list.</p>

***

### Version 0.4.0
**Oct 17, 2014 - BETA**

#### GLOBAL
* Updated Top-Most behavior to fix some issues.
* New grayscale icons when no game is selected.
* Clicking on game selection message now cancels game selection.

#### SONAR
* New command line to disable all overlays "-nooverlays".
* Internal name cache is now cleared upon stopping Sonar.
* Advanced filters can now be separated using pike ("|").
	* Example: "worg|cow" or "77795|77828|82486".
* Added new filters for Warlords of Draenor entities.
* Updated filters to reflect new properties.
	* Previous filters will be auto-updated.
* New tracer feature in advanced filtering system.
	* Draws a line from your character to the entity.
* Dynamic neutral and friendly players are now blue.
	* To reduce confusion and to match nameplates.

#### WILD-CATCH
* Added an option to disable auto anti-afk jumping.
* Anti-afk jumping now occurs within a random range.
* F12 now only stops Wild-Catch when the game is in focus.
* Added a human characteristics mode for more variety.
	* Occasionally ignores bites every now and then.
	* Occasionally recasts the rod once or twice.
	* Occasionally takes a break every now and then.

***

### Version 0.3.0
**Jul 17, 2014 - BETA**

#### GLOBAL
* Main windows are no longer Top-Most by default.
	* Use the "-topmost" command-line argument to revert this.
* Added executable icons and resource information.
* Multiple instances no longer share taskbar space.
* Added an opt-out feature for keyboard hooking.
	* Done using the "-nohook" command-line argument.
* Slightly improved the game selection algorithms.

#### SONAR
* Plus and minus now zoom when the radar is in focus.
* Added a sound alert feature in advanced filtering.
	* Added seven new awesome sound effects!
* Updated filters to reflect new properties.
	* Previous filters will be auto-updated.
* Resetting search field now auto focuses search field.

#### WILD-CATCH
* Out of limited release and publicly launched!

***

### Version 0.2.2
**Jun 10, 2014 - BETA**

#### GLOBAL
* Added privilege checking when selecting the game.

#### SONAR
* Minor user interface improvements and bug fixes.
* Select All will now apply to selected filters.
	* Only if more than two filters are selected.
* Out of limited release and publicly launched!

***

### Version 0.2.0
**May 04, 2014 - ALPHA**

#### GLOBAL
* User is now notified if the game version is not supported.
* Message box dialog now properly stands out when reactivated.
* Application stops when the game window is no longer valid.
* Progress Bars now reflect whether or not they are disabled.

#### SONAR
* Highlighting of enemy players when using the dynamic filter.
* Fixed most of the radar and overlay issues while in a vehicle.
* Removed the ability to toggle name visibility in the radar.
* Added the ability to hide pet entities (advanced filter only).
* Added the ability to hide dead entities.
* Added multi-selection editing to the advanced filter.
* Updated filters to reflect new properties.
	* Previous filters will be auto-updated.
* Added support for special keywords in the dynamic filter.
	* Enter "lootable"  or "loot" to display lootable  NPCs.
	* Enter "skinnable" or "skin" to display skinnable NPCs.
	* Enter "ally"  or "allies"  to display ally  Players.
	* Enter "enemy" or "enemies" to display enemy Players.
* Dynamic filters can now be separated using pike ("|").
	* Example: "wolf|rat|wild*cat" or "lootable|skinnable".

#### WILD-CATCH
* Temporarily removed Pushover notification features.

***

### Version 0.1.0
**Feb 11, 2014 - ALPHA**

#### GLOBAL
* Initial release
