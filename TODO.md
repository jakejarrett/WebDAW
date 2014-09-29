TODO
====

What to finish off before starting work on implementing instruments & functionality



#### UI

* UI Needs to finalised (Sidebar for Instruments, Effects, Library & Sidebar for Channels)
* Needs panel that comes up only when you select Channel/Instrument
* Need to finish off Headerbar with all icons & then prepare them for functionality
* Themes (Default, Flat & more) & allow custom themes
* Settings (And a bunch of other things, maybe controlling Instruments could have a Modal?) Popup

#### JS / Performance

* Minimize JS, only do what is 100% necessary, anything else that isn't part of the core will be moved into plugins / opt-in
* Need to improve performance (Slow even when initializing)
* Only load things when called? (EG/ don't need all the instruments loaded if you're not using any yet)
* Improve how themes change (If local, doesn't matter as much, but can be demanding on resources if changing constantly for multiple users)

#### Themes

* ~~Restructure CSS~~
* Plan to support Instrument Theming too
* Create Flat Theme, Light & Dark Themes.
* Re-write SCSS for code to allow users to make their own style in SCSS or CSS (Maybe add LESS later)

What to do before a BETA is released?
===

#### Code

* Prepare code for packaging in CEF to test as a Desktop Application
* Minimize outside frameworks (jQuery, Modernizr etc) to lower Resource
* Have stable & Modular code.

#### UI

* Allow native windows for things that are handled via Modals in Bootstrap for Desktop Application (EG/ Closing could be an actual SAVE/CANCEL/DONT SAVE dialog)
* The Theme engine should choose what theme defaults on first run for what OS (EG/ OS X could have default, Windows has Modern/Flat and Linux has GTK style theme)

#### Projects
* Enable external saving & instruments (Could potentially bring this to the web version too, depending on how it is implemented)
* Research other project types & try to convert things like Ardour, Non-Timeline, FLP etc