# AutoOutline
Aseprite Auto-Outline script that maintains an outline in a new Layer

**TO USE:** Save as 'AutoOutline.lua' in your Aseprite Scripts folder 

_(Tip: From Aseprite, open 'File -> Scripts -> Open Scripts Folder')_

Then hit 'File -> Scripts -> Rescan Scripts Folder'

Then run by running 'File -> Scripts -> AutoOutline'

_(Tip: assign it a shortcut! I use Alt+O)_

![my_script](https://github.com/user-attachments/assets/a75d978d-7a8c-4f9d-a397-acacedfde1ea)


Based on a script by Aseprite user 'psychicteeth' found here https://community.aseprite.org/t/automatic-outline-generation/24423 
and then updated by Sean Flannigan (seanflannigan.com) to add:
- A dialog to start/stop the service and pick outline color 
- the outline layer is ONLY outlines so that they can be independently hidden, set transparent, etc 
- Removed console printing on undo 
- Move the outline layer to the bottom (if set to 'outside') and make it locked
- Able to ignore manually-placed outline-colored pixels (to manually place outline pixels to define sharp edges for example)
- allows AutoOutline to run on a group, creating outlines for every visible layer within that Group
- v1.01 bugfix: clear 'app.range' so that it doesn't break when selecting multiple cels/layers 
