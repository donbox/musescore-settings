# My Musescore Settings

This repo contains the settings I use for [MuseScore](https://musescore.org/en).

MuseScore is a much better fit for my needs than either [Finale](https://www.finalemusic.com) or [Sibelius](https://www.avid.com/sibelius). YMMV.

MuseScore is also [open source](https://musescore.org/en/development) so if one has the will and the skill, perfection is just a matter of semicolons and curly braces away. 

## My Custom Instruments

My [instruments.xml](instruments.xml) file adds one new group to the instruments list (**Strings - Alternate Tuning**). I'm doing a lot of work with [New Standard Tuning](https://en.wikipedia.org/wiki/New_standard_tuning) on the guitar, and I got tired of manually configuring staves to get the right tuning and tab positions.

Musescore allows you to augment the default instruments.xml file with a custom one that adds new instruments.  This file is meant to be used for the latter.

To configure Musescore to pick up this file, download it from your browser (or simply use `git clone` like me) and follow the instructions [here](https://musescore.org/en/handbook/developers-handbook/references/instrumentsxml-documentation#instruments.xml_files) to have MuseScore pick it up.

