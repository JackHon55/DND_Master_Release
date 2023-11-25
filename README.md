# DND_Master_Release
Releases of DND Master program - Version 1.5 updated 25/11/2023

1. Download, go to code and download the zip file
2. Unzip the file anywhere you like
3. Enter the extracted folder and unzip the libcef file. Make sure the resulting .dll file is in the same place as DND_HP.exe
4. Only Windows Scaling 100% is supported. Change it in Desktop->Right Click->Display Settings->Scale and Layout before you run the program* (Other Scaling may cause funky layout issues)
5. Run DND_HP.exe and when prompted, CLICK CANCEL OR CLOSE THE PROMPT
6. FOLLOW THE INSTRUCTIONS on the Instruction tab to start creating your character sheet
7. Save regularly into a different file, and from then on you can load that file when launching DND_HP.exe

8. For updates, you should re-download the whole thing again.
9. There has been large update in file format from version 1.4 to 1.5, old dnd_stat.txt are not compatible and will require manual tweaks. I suggest redoing the sheet.

# Big Panel Tabs OwlBear, Discord, Data-Notepad
1. Online VTT platform owlbear is integrated. If you have a working owlbear room link in the dnd_stat.txt file, you can interact with owlbear freely. (but requires sign in every time)
2. Discord can be embedded into the program, allowing access with no need for alt-tab. This instance of discord is from your computer, you launch it and then place it into the program (therefore it is safe)
3. Instructions page provides instructions on how to use the program. You can also view the current .txt file. You can freely make as many copies as required and save them under any name. You can have one stat file open at a time, and can load the current opened stat file data into the program. Any changes made to the notepad can also be saved as usual.
4. The Colour Button allows minor customisation of the resource button colour scheme.

# HP tracker
1. Tracking for Temporary HP, Max HP, Current HP, Max HP adjusting effects such as from the Aid spell
2. Tracking Healing and Damage with easy resistance and doubly halved values.
3. Simply enter your current HP status. Aid Hp must be written with a +, for example Max HP = 100, Aid HP = 20 is 100+20, same with Current HP
4. The Undo button here undoes the HP tracking only
5. The Save button saves for the entire program

# Combat Action and Movement Tracker
1. Simple 3-button system, that if you remember to click on them, reminds you if you have used your action, bonus action and reaction. The box with R resets these buttons.
2. The slider allows you to vague keep track of your remaining movement, also resets with the R button.

# Resource Tracking
1. Combat and Adventuring Resources pages allows user to keep track of the resources that they have. Left click to turn blue <> black, white <> purple, Right click for white <> black
2. Spell Slot tracker is similar, but is automated to deplete spell slots as you cast spells
3. Gold tracker allows you to enter DnD gold values as a line of text such as 100cp 200sp 340gp 2pp and have it recorded (no comma). You can split the gold by having the number of people to split to in the small box next to split, then click on split.
4. Mol button is an easter egg, it splits the gold in a way such that you will lose out, but everyone else gets a little bit more.
5. Equipment page lists the name of your stuff. You can click on the boxes to view the equipment, edit/remove as you wish. Empty slots will remain as Empty_x, and you can add/remove slots by right clicking. You can also reorder by right clicking

# Attributes
1. You DND statblocks are listed here
2. White boxes next to skills are normal, black is proficient and yellow is expert.
3. You can left click on the stat label such as STR, as well as skill labels such as Athletics, to change its colour to keep track of advantages/disadvantages.
4. Major edits can be done by by right clicking an empty spot in the respective coloured box

# Spell page
1. You list of spells listed in a similar way as the Equipment page
2. Clicking on one brings up the spellcard, which you can edit/remove, or cast
3. Empty slots will remain as Empty_x, and you can add/remove slots by right clicking. You can also reorder by right clicking
4. Casting automatically consumes the spell slot of the level you are casting in
5. You can also upcast the spell and the corresponding spell slot will be consumed

# Action-Bonus Action-Reaction-Feature
1. These pages hold you character features and options, and you are relatively free to customise them however you want
2. The melee hit and range hit modifier allows you to track to attack modifier bonuses outside of your +weapons
3. The extra textbox for notes and these modifier tracker are shared across all pages
4. You can click on the options of the weapon (such as Thrown 20/60) to create a temporary note with the details, allowing ease of information access

# Notes
1. Allows user to create sticky notes that can be placed around the screen.
2. WIP no method of deleting them yet other than manually from the dnd_stat.txt They can be closed off and stored

* If the program still looks odd, check the following
1. You are using the windows 100% scaling, not the custom one that you can access under Scale and Layout->Advanced scaling settings
2. In the Advanced scaling settings, make sure "Fix scaling for apps" is turned on
3. Right click DND_HP.exe->Properties->Compatibility->Change High DPI setting, ensure everything is not ticked
