# StatueOfPowerReplacer
A mod to replace the statue of power in palworld
Original mod can be found here https://www.nexusmods.com/palworld/mods/321?tab=description however it does not work for the latest version of Palworld.


# How to use
Clone https://github.com/RiotOreO/unrealpak  
Drag the Effigy_P folder into the file "UnrealPak-With-Compression.bat"it will then provide you with Effigy_P.pak  
Copy that pak file into steamapps\common\Palworld\Pal\Content\Paks  
Launch the game  

# This may break after newer updates of Palworld
A quick fix would be to clone this and delete the L10N folder, then pack it again, this will however remove the text changes that the mod adds.

The legit fix would be to follow this guide(https://pwmodding.wiki/docs/datatable-modding/uassetgui/UAssetGuide1) to rereplace the text while keeping the newly added text that the update brang.

Another reason the mod could break could be due to Palworld renaming their files or changing their folder structure, to fix it you would need to find the changes that were done in terms of folder structure/renaming and change the mods folder structure/naming to match it. I would recommend going into the palworld modding discord server to find information about changes to the latest updates, please check the reddit for the link to the discord https://www.reddit.com/r/PalworldMods/new/

here is a temporary link to it but it may be broken in the future  
https://discord.gg/bbeh44bBub

# How I fixed to work with 1.0
Install FModel, Unreal engine 5.1.1, UAssetGUI, WWise
configure everything according to the documentation on the palworld modding guide.
After exporting the text files in fmodel open it in UAssetGUI
the files i needed to edit includes:

DT_BuildObjectDescText_Common.uasset
DT_HelpGuideDescText.uasset
DT_ItemDescription Text_Common.uasset
DT_NpcTalkText_Common.uasset
DT_TechnologyDescText_Common.uasset
DT_TutorialMessage_Text.uasset
DT_UI_Common_Text_Common.uasset

you'll have to open them one by one and save each time you open another as doing it without saving will discard any changes. Search for terms such as "offer" or "statue of power" and replace it.
