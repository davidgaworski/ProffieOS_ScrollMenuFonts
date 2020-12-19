# How to Use

This font library is for using with my fork of the ProffieOS for an opensource ligthsaber build.

## Installation

You will need to load all of these fonts in the SD card in a newly created /voiceovers folder.
```bash
/voiceovers/
```

## Usage

This is currently hardcoded to work with my fork and any new changes will not be processed under the new build. In the future the OS will scan this folder to add them from scans.

## Structure

The structure of the voiceover files go as such:

In the base voiceover folder you will need to add the character name and all of the requried subfolders and files.

#### Adding New Menu Voices:
```bash
/voiceovers/{voiceoverCharacterName}
```


###  Adding Annoucements:
These are separated into two file folders and one base .wav for the self annoucements.

#### Self:
```bash
/voiceovers/{voiceoverCharacterName}/self.wav
```
#### Characters:

Base characters for all of my fonts include:
* Luke Skywalker
* Obi Wan Kenobi
* Mace Windu
* Yoda
* Darth Maul
* Qui-Gon Jinn
* Ahsoka Tano
* Kylo Ren
* Rey
* Emperor Palpatine
* Count Dooku
* Ben Solo
* Anakin Skywalker
* General Grievous

```bash
/voiceovers/{voiceoverCharacterName}/characters
```
#### Menu:
Base menu voices for all of my fonts include:
###### *Note: All are no implemented at this time, but should be present for future improvements.

* Main Menu
  * mainmenu.wav
* Menu Voice Change
  * menuvoicechange.wav
* Font Change
  * fontchange.wav
* Saber Change
  * saberchange.wav
* Color Change
  * colorchange.wav
* Music Change
  * musichange.wav
* Volume Change
  * volumechange.wav
* Max Volume
  * maxvolume.wav
* Muted
  * muted.wav
* Low
  * low.wav
* Medium
  * medium.wav
* High
  * high.wav
* Battery
  * battery.wav
* My power is high, High Battery
  * highbattery.wav
* My power is stable, Medium Battery
  * mediumbattery.wav
* My power is fading, Low Battery
  * lowbattery.wav
```bash
/voiceovers/{voiceoverCharacterName}/menu
```



```
