# OBS
Setup documentation for the OBS-Live teams of ICSE 2020

## Import OBS Scenes
After cloning the repository you have to replace the absolute paths in `obs/ICSE_Scenes.json` to match the location of this repository on your computer.
Replace every
```
/Users/caro/Documents/Conferences/ICSE2020/icse2020-live
```
with
```
/absolute/path/to/this/folder
```
(The absolute path will probably end with icse2020-live).

After correcting the paths you can import the scene colletion in OBS under "Scene Collections" → "Import" → "Collection Path": select the file `obs/ICSE_Scenes.json`.

For more information about how to setup the scenes with your computer & capturing the correct zoom windows please check the OBS'ers checklist :)

## OBS Sound Setup
Only sound from the Zoom session should be rerouted to OBS.
We have identified several possibilities to realize this:

### Second Audio Device 
First of all, you absolutely need to turn off the volume of "Desktop audio" (the default where all sounds go) because of all the computer sounds that may happen (notifications, etc.). Then you need to map the sound coming from Zoom to another audio output, and then in OBS we need to pick that one up in Desktop Audio 2. In other words:

- turn down the "default" desktop audio in OBS
- use a non-default speaker for Zoom sound (in Zoom)
- pick that non-default speaker in OBS as Desktop Audio 2

In order for this to work, you need two speakers, which can be 1) the external speakers; and 2) the headset.
Whichever your computer picks as default, use the other non-default one for passing sound between Zoom and OBS.
Also, in OBS, remember to turn down the volume of the audio input (microphone) all the way down to mute.

### Loopback or Soundflower
On Mac [Loopback](https://rogueamoeba.com/loopback/) can be used as an audio virtual device.
It is very easy to setup:
Install, add Zoom as input device, the Zoom sound is automatically connected to the Loopback output, set Loopback as input sound in OBS
However, the free version overlays noise after 20 minutes.

Loopback is based on the open source tool **Soundflower** (Installation for Mac: https://github.com/mattingalls/Soundflower/releases/tag/2.0b2)
After installing set Soundflower as audio output device in Zoom & as audio input device in OBS.
