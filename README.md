![image](screenshots/bonkers.jpg)

# Parallax_MaskKSC
Simple mod to mask out the Kerbal Space Center from Parallax scatters using a custom black and white mask. This mod as is, is adapted to a 2.7x size "KSCEnhanced" (Using a simple SigmaDimensions config tweak). You will have to mod it to fit it to your needs. For troubleshooting you can enable red / green debug colors in the config. 

Derived from the [Official Tutorial](https://github.com/Gameslinx/Parallax-Continued/wiki/Scatters-%E2%80%90-Stopping-Scatters-from-Growing-Inside-Buildings) for the ~~lazy~~ efficient people. ;P

# Installation

## Copy Files

Paste the downloaded folder into your GameData folder like so

> Kerbal Space Program\GameData\Parallax_MaskKSC\mask_ksc_MM.cfg

> Kerbal Space Program\GameData\Parallax_MaskKSC\PluginData\mask_ksc.dds

To create your own mask land on the VAB, in the center of the Helipads, zoom all the way in using Alt + Scroll, then zoom out using just scroll until you see the whole KSC. Create a screenshot. Paint the mask black on white background. Flip the mask vertically (mirror not rotate). Save as .dds file (DXT1 with mipmaps on). Exporting to dds can be done with for example Krita + DDS Export Python Plugin Script 

# Dependencies

- [Parallax-Continued](https://github.com/Gameslinx/Parallax-Continued) obviously

## Optional

For a true plug and play solution your KSC should have the same size as mine (2.7x). I provide my Sigma and Parallax settings files separately.

- [KSCEnhanced](https://forum.kerbalspaceprogram.com/topic/225356-ksc-enhanced/)
- [SigmaDimensions](https://github.com/Sigma88/Sigma-Dimensions) using my 2.7x settings.cfg
- [Sigma Replacements](https://github.com/Sigma88/Sigma-Replacements)

# TODO

- I have to tinker with Kronometer or other settings to make the daytime make a little more sense. It should be 12 hours but it isn't?

# My Mod List

Check every mod for dependencies (I will add them later here too)

- [Restock & Restock+](https://github.com/PorktoberRevolution/ReStocked) (Complete revamped of the stock parts plus stock-ish parts that Squad forgot)
- [RestockPBR](https://github.com/PorktoberRevolution/ReStockPBR) (New PBR materials + re-color for Restock parts)
- [Volumetric Cloud v3](https://www.patreon.com/posts/true-volumetric-87982960) (I use v5 but that one is paywalled)
- [ParallaxContinued](https://github.com/Gameslinx/Parallax-Continued/) (Greatly improved ground scatter and parallax effects for all planets)
- [Firefly](https://github.com/M1rageDev/Firefly/) (Revamped reentry effects)
- [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall) (Framework! All new engine effects that expand with atmospheric pressure)
  - [Stock Waterfall Effect](https://github.com/KnightofStJohn/StockWaterfallEffects) (Configs for stock engines)
  - [Waterfall Restock](https://github.com/post-kerbin-mining-corporation/WaterfallRestock) (Basic configs for Restock)
  - [Waterfall Expansion](https://spacedock.info/mod/3149/Restock%20Waterfall%20Expansion) (Closes the gab between Stock and Restock Effects)
  - [RSMP](https://github.com/dangaffa/RSMP) (Configs for SRBs)
- [VAB Organizer](https://github.com/post-kerbin-mining-corporation/VABOrganizer) (Organizes parts and gives them colored icons based on size similar to KSP2)
- [TUFX](https://github.com/KSPModStewards/TUFX/) (Post processing effects for KSP to make it look nicer)
- to be continued...

## Mod Dependencies

- TODO
  
![image](modlist.png)
