# Parallax_MaskKSC
Simple mod to mask out the Kerbal Space Center from Parallax scatters using a custom black and white mask. This mod as is, is adapted to a 2.7x size "Enhanced Kerbal Space Center". You will have to mod it to fit it to your needs.

# Installation (hacky)

## Step 1

Backup and replace following file with the one provided

> Kerbal Space Program\GameData\Parallax_StockTerrainTextures\_Configs\StockPlanetAdjustments.cfg

You can also replace the "MapDecalVertexRemoveScatter" section. That's all we need here. Just in case the rest of the file is different for you.

## Step 2

Add the provided mod directory to your GameData folder. 

> Kerbal Space Program\GameData\Parallax_MaskKSC\PluginData\mask_ksc.dds

To create your own land on the VAB, in the center of the Helipads, zoom all the way in using Alt + Scroll, then zoom out using just scroll until you see the whole KSC. Create a screenshot. Paint the mask black on white background. Flip the mask vertically (mirror not rotate). Save as .dds file (DXT1 with mipmaps on). Exporting to dds can be done with for example Krita + DDS Export Python Plugin Script 

# TODO

Add a custom config file so that the existing one does not need to be changed. (The proper way)
