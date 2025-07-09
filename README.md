# Synthi-D
Virtual implementation of the Synthi AKS in Pure Data







Synthi D

This puredata patch is an attempt to recreate the modus operandi of the VCS3/Synthi AKS, especially the pin matrix
interface, that allows to interconnect synthetizer blocks in a conveniant and modular way. Digital by nature, the
produced sounds are not intended to reproduce the genuine analog ones. However, like the Synthi E (Education model)
this virtual instrument can give an opportunity to experiment, learn synth basis, to create, and the most important,
to have fun.

Usage:

Open the patch “Synthi_D.pd” with Pd 0.55.2
Click on the Pd main window on the DSP box if not already done.

At the bottom line, slide on “Ch1 Level Out” and “Ch2 Level Out” to an acceptable level.
To produce a sound, tap a pin on the pin matrix at A3 and C3 for the first Oscillator (OSC1), and A4 and C4 for 
the second (OSC2).
Eventually, an Oscilloscope output could be useful, tapping on B1 (Channel 1 output) and B2 (Channel 2 output).

You can set the waveform, the frequency and the volume amount of each Oscillator, OSC1 and OSC2, by varying the 
Waveform selection 1, the Waveform selection 2, OSC1 and OSC2 frequencies, and respective volumes. There are 2 
waveforms selectables and editable by hand for Oscillator 1 ans 2, and one waveform for each LFOa and LFOb. 
Hand edit can give some unexpected character to the sound. 

See _fig1 to _fig3 for a quick overview.
_fig4 to _fig8 are more intended to remote interactivity with custom patches.

Some combination of synthetiser blocks could generate hazardous sounds, so be gentle with your ears and set the
volume on comfortable levels.

Tested on Pd 0.55.2.
link to download:
https://puredata.info/downloads/pure-data

Enjoy!


Horia Cosmin Samoïla





