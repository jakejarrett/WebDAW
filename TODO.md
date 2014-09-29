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
