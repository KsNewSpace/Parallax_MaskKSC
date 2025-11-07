Parallax Mask KSC + 2.7x Resize *(optional)*
==========================================
***for Kerbal Space Program*** *by Lukas K. aka KsNewSpace*

![image](screenshots/header.png)

*<div align="center">this is how a correct mask should look like in debug colors -> see config file to enable it</div>*

Simple mod to mask out the Kerbal Space Center from Parallax scatters using a custom black and white mask. This mod as is, is adapted to a 2.7x size "KSCEnhanced" (Using a simple SigmaDimensions config tweak). You will have to mod it to fit it to your needs. For troubleshooting you can enable red / green debug colors in the config. 

Derived from the [Official Tutorial](https://github.com/Gameslinx/Parallax-Continued/wiki/Scatters-%E2%80%90-Stopping-Scatters-from-Growing-Inside-Buildings) for the ~~lazy~~ efficient people. ;P

### Motivation

My goal is to bring KSP to 2025 without changing the core gameplay loop too much. The 2.7x rescale makes it a bit more difficult to get around but it works perfectly fine with stock parts. In fact, I think the stock parts are designed for this particular size. They are just OP on 1x, especially the bigger tanks and engines. For the number people: Getting to orbit around Kerbin requires just shy of 4000 m/s DeltaV. Mostly payloads will become smaller and more realistic looking. If you want giant rovers and colonies better prepare for some orbital construction and fuel depots :)

### Official Channels

- Tip Jar: [KsNewSpace.shop](https://ksnewspace.shop/) <3
- YouTube: [@KsNewSpace](https://www.youtube.com/@KsNewSpace) (KSP, Coding, Space Stuff)
- Twi..X: [@KsNewSpace](https://x.com/KsNewSpace) (I'm not a Nazi)
- Twitch: [KsNewSpace](https://www.twitch.tv/ksnewspace) (placeholder, I don't really stream but who knows..)
- Business Contact: KsN■wSp■ce@outl■ok.com (replace ■ with sensical vowels)
  - Mails with attachments are sorted out. I will forward your mail to the authorities if it contains illegal or disturbing things.

# Installation

## Download

Github Mirror: [Parallax_MaskKSC/releases](https://github.com/KsNewSpace/Parallax_MaskKSC/releases) (v1.2 latest zip file)

## Copy Files

Paste the downloaded folder into your GameData folder like so

> Kerbal Space Program\GameData\Parallax_MaskKSC\mask_ksc_MM.cfg

> Kerbal Space Program\GameData\Parallax_MaskKSC\PluginData\mask_ksc.dds

To create your own mask land on the VAB, in the center of the Helipads, zoom all the way in using Alt + Scroll, then zoom out using just scroll until you see the whole KSC. Create a screenshot. Paint the mask black on white background. Flip the mask vertically (mirror not rotate). Save as .dds file (DXT1 with mipmaps on). Exporting to dds can be done with for example [Krita](https://krita.org/) + [DDS Export](https://github.com/esuriddick/Programming/tree/main/Python/Krita/DDS_File_Exporter) Python Plugin Script 

## Minimum Dependencies

- [Parallax-Continued](https://github.com/Gameslinx/Parallax-Continued) obviously

## Optional

For a true plug and play solution your KSC should have the same size as mine (2.7x). I provide my Sigma and Parallax settings files separately.

- [KSCEnhanced](https://forum.kerbalspaceprogram.com/topic/225356-ksc-enhanced/)
- [SigmaDimensions](https://github.com/Sigma88/Sigma-Dimensions) using my 2.7x settings.cfg
- [Sigma Replacements](https://github.com/Sigma88/Sigma-Replacements)

Copy the content of the optional GameData folder into your GameData folder. Make backups of the settings files this will overwrite if you want to keep them. (Working on a better way than this)

## Known Issues

- I have to tinker with Kronometer or other settings to make the daytime make a little more sense. It should be ~12 hours on 2.7x scale but it isn't?

My Complete Mod List: [KSP Stockalike Overhaul](https://github.com/KsNewSpace/KSP_Stockalike_Overhaul)
====================

![image](screenshots/bonkers.jpg)

*<div align="center">This could be your KSP</div>*
