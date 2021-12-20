# My Musescore Settings

This repo contains the settings I use for [MuseScore](https://musescore.org/en).  

I switched from [Finale](https://www.finalemusic.com) to MuseScore in 2019 and haven't looked back.And yes, I tried both [Sibelius](https://www.avid.com/sibelius), [Dorico](https://www.steinberg.net/dorico/) and even [Guitar Pro](https://www.guitar-pro.com) and none of them were a great fit for how I work.  YMMV.

MuseScore is also [open source](https://musescore.org/en/development) so if one has the will and the skill, perfection is just a matter of semicolons and curly braces away. 

## Custom Instruments

My [instruments.xml](instruments.xml) file adds one new group to the instruments list (**Strings - Alternate Tuning**) that includes both [New Standard Tuning](https://en.wikipedia.org/wiki/New_standard_tuning) Guitar as well as [Chapman Stick](https://en.wikipedia.org/wiki/Chapman_Stick) configurations.

Musescore allows you to augment the default instruments.xml file with a custom one that adds new instruments.  This file is meant to be used for the latter.

To configure Musescore to pick up this file, download it from your browser (or simply use `git clone` like me) and follow the instructions [here](https://musescore.org/en/handbook/developers-handbook/references/instrumentsxml-documentation#instruments.xml_files) to have MuseScore pick it up.

Here's the list of supported instruments:
- **Acoustic Guitar (NST)** - A 21-fret acoustic guitar tuned in new standard tuning. Note that many guitars only have 20 frets, however, some of the repertoire includes a high E, which is sometimes played by using the extra fingerboard sans fret.
- **Chapman Stick Bottom** - The "bass side" of a Chapman Stick tuned in [10-string Classic](http://stick.com/instruments/tunings/10/classic/) tuning. 
- **Chapman Stick Top** - The "treble side" of a Chapman Stick tuned in [10-string Classic](http://stick.com/instruments/tunings/10/classic/) tuning.

### Stick Tablature Notes
Fret zero corresponds to the "X" fret in Stick tuning. On a classic 34 inch stick, this is the nut (with damper) and is unusable using standard tapping. On a newer 36 inch scale stick, this correspnds to the first usable fret for tapping. 

It is common for Stick tablature to invert the string order for the bottom/bass side of the instrument. You can do this as follows:
1. Select the staff you want to invert.
1. Right-click on it and choose **Staff/Part Properties...**
1. Click the **Advanced Style Properties...** button.
1. Click the **Upside down** check box.
1. Click **OK** to dismiss the dialogs and Bob's your uncle.

