# DND_Master_Release
Releases of DND Master program

1. Download, go to code and download the zip file
2. Unzip the file anywhere you like
3. Enter the extracted folder and unzip the libcef file. Make sure the resulting .dll file is in the same place as DND_HP.exe
5. Only Windows Scaling 100% is supported. Change it in Desktop->Right Click->Display Settings->Scale and Layout before you run the program* (Don't know why but it sucks for me too)
6. Run DND_HP.exe and load dnd_stat when prompted
7. Follow the instructions on the Data-Notepad tab in DND_HP to modify my character sheet into yours
8. Enjoy!

# Big Panel Tabs OwlBear, Discord, Data-Notepad
1. Online VTT platform owlbear is integrated. If you have a working owlbear room link in the dnd_stat.txt file, you can interact with owlbear freely. (but requires sign in every time)
2. Discord can be launched from the program, allowing access with no need for alt-tab. This instance of discord is from your computer, and it is just launching it then placing it into the program (therefore it is safe)
3. Data-Notepad has instructions on how to modify dnd_stat.txt. You can freely make as many copies as required and save them under any name. You can have one stat file open at a time, and can load the current opened stat file data into the program. Any changes made to the notepad can also be saved as usual (this notepad is just an instance of notepad opened from your computer, then placed into the program)

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
3. Gold tracker allows you to enter DnD gold values as a line of text such as 100cp 200sp 340 gp 2pp and have it recorded. You can split the gold by having the number of people to split to in the small box next to split, then click on split.
4. Mol button is an easter egg, it splits the gold in a way such that you will lose out, but everyone else gets a little bit more.
5. Equipment page lists the name of your stuff. You can click on the boxes to view the equipment, edit/remove as you wish.

# Attributes
1. You DND statblocks are listed here with an extra textbox in each to allow for modification to the entire attribute
2. White boxes next to skills are normal, black is proficient and yellow is expert.
3. You can left click/right click on the stat label such as STR, as well as skill labels such as Athletics, to change its colour to keep track of advantages/disadvantages. (these wont be saved, WIP)

# Spell page
1. You list of spells listed in a similar way as the Equipment page
2. Clicking on one brings up the spellcard, which you can edit/remove, or cast
3. Casting automatically consumes the spell slot of the level you are casting in
4. You can also upcast the spell and the corresponding spell slot will be consumed

# Action-Bonus Action-Reaction-Feature
1. These pages hold you character features and options, and you are relatively free to customise them however you want
2. The melee hit and range hit modifier allows you to track to attack modifier bonuses outside of your +weapons
3. The extra textbox for notes and these modifier tracker are shared across all pages

# Notes
1. Allows user to create sticky notes that can be placed around the screen.
2. WIP no method of deleting them yet other than manually from the dnd_stat.txt They can be closed off and stored

* If the program still looks odd, check the following
1. You are using the windows 100% scaling, not the custom one that you can access under Scale and Layout->Advanced scaling settings
2. In the Advanced scaling settings, make sure "Fix scaling for apps" is turned on
3. Right click DND_HP.exe->Properties->Compatibility->Change High DPI setting, ensure everything is not ticked
