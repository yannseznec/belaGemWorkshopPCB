# belaGemWorkshopPCB

## A PCB designed for the Bela Gem

This board is meant to be a general-purpose PCB, specifically suited to how I use the Bela Gem. In practice, this is essentially a breakout board for all of the analog and digital pins. Each of these is accessible using individual Molex (or generic 2.54") connectors. So you can use as many or as few as you need for any given project.

The Bela Gem has built-in 1/8" input and output connectors. This PCB also has Molex pins for unbalanced stereo inputs and balanced stereo outputs. The headphone output is also available as a three pin molex.

If you want to power the board via a power supply (rather than USB), there is a pin pair that is +/-. The power runs through a pair of pins labeled "Power Switch". If you don't want to use a switch, bridge these pins. If you use USB power the switch pins do nothing at all.

To-do:

- test this! I still haven't soldered one up.
- add silkscreen labels for the power pins (to show which side is power)
- add silkscreen labels for one analog molex (to show which pins are what)
- add silkscreen labels for one digital molex (to show which pins are what)
- add silkscreen labels for audio inputs and outputs (starting to see a theme here)