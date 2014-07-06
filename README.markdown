DOEPFER Pocket Dial as a native Control Surface in Ableton Live
===============================================================

Current version is 0.2 – released Sept 30, 2013.


What is it?
-------------------------------------------------------------

This MIDI Remote Script adds support for the DOEPFER Pocket Dial as a native Control Surface in Ableton Live – with a scrollable red-box, yay!

It currently supports:

*	Bank 1: Mixer – Volume/Pan
*	Bank 2: Mixer – Sends A/B
*	Bank 2: Mixer – Sends C/D
*	Bank 3: Device & Track Ctrl


More information can be found on the [project’s homepage.](http://pocketdial.wiffbi.com/)



Getting started
-------------------------------------------------------------

Download and install the MIDI Remote Script (see Installation).

On the Pocket Dial, select **Preset 85** (Reaktor 0-15 Mchn) by setting the DIP selector to 00101010. Make sure, the Pocket Dial sends on channel 1 – press the CHN-Button and turn encoder 1 to set the global MIDI channel to 1.






License
-------------------
This work is licensed under the "Simplified BSD License" / "FreeBSD License"
see License.txt



System Requirements
-------------------
Ableton Live 8 or 9




Installation
------------

Download from [http://pocketdial.wiffbi.com/](http://pocketdial.wiffbi.com/) and unzip.

1.	Stop Live if it is running.
2.	Add *Pocket_Dial* to Ableton Live's MIDI Remote Scripts

	The folder `Pocket_Dial` contains the MIDI Remote Script. To install, open Finder and locate the Ableton Live-application, right click on Live and choose *show package contents*. In there go to the folder `Contents/App-Resources/MIDI Remote Scripts/` and move the folder `Pocket_Dial` in there.

3.	Start Live.
4.	Enable **Pocket_Dial** as a Control Surface in Live

	In Live’s Preferences go to the *MIDI Sync* tab and select *Pocket Dial* in the dropdown list of available Control Surfaces. As MIDI Input select the MIDI interface the Pocket Dial is connected to. A MIDI Output is not needed.
	






Changelog
---------

### Version 0.2 (released Sep 30, 2013) ###

Updated for Live 9
Changed layout
Changed PocketDial preset from 111 to 85, because of CC 123 not working in Live 

### Version 0.1 (released Dec 22, 2011) ###

First public release.
