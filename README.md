# Parallax_MaskKSC (buggy)
Simple mod to mask out the Kerbal Space Center from Parallax scatters using a custom black and white mask. This mod as is, is adapted to a 2.7x size "KSCEnhanced". You will have to mod it to fit it to your needs. For troubleshooting you can enable red / green debug colors in the config. 

Derived from the [Official Tutorial](https://github.com/Gameslinx/Parallax-Continued/wiki/Scatters-%E2%80%90-Stopping-Scatters-from-Growing-Inside-Buildings) for the ~~lazy~~ efficient people. ;P

# Installation

## Copy Files

Paste the downloaded folder into your GameData folder like so

> Kerbal Space Program\GameData\Parallax_MaskKSC\mask_ksc_MM.cfg

> Kerbal Space Program\GameData\Parallax_MaskKSC\PluginData\mask_ksc.dds

To create your own mask land on the VAB, in the center of the Helipads, zoom all the way in using Alt + Scroll, then zoom out using just scroll until you see the whole KSC. Create a screenshot. Paint the mask black on white background. Flip the mask vertically (mirror not rotate). Save as .dds file (DXT1 with mipmaps on). Exporting to dds can be done with for example Krita + DDS Export Python Plugin Script 

# Known Bug

The overwriteing of the config does not work properly and Parallax complains ingame about.
