# VRCInventorySystem

This is an inventory system originally created by Weong, Error, and Nepsy, and modified by Xiexe to be easier to use and more user friendly.

## Before you start

1. Make sure you have your items that you would like to be in your inventory on your avtar, in the correct spots. 
2. Make sure the items are visible
3. Make sure the items have reasonable **unique** names.


## Creating the Inventory

Find "VRC Inventory" at the top of the Unity Toolbar, go to "Tools" and then hit "Inventory Remapper"

To use the tool, drag your avatar into the avatar slot.

You will now see some options for the inventory. Adjust the slider to however many slots you want (7 is the max).

Now, drop your items into the slots that are shown, and choose wether you want 
them to be enabled by default or not using the checkbox on the right side.

Then, hit generate. 

The script will generate the corresponding animations in the "Animations" folder under "YOURAVATARNAME"

Take these animations, and assign them to your animation override controller, as you would any other gesture or emote.

You should now be good to go, and have a functioning inventory ready to go when you upload your avatar!

PLEASE NOTE: There is a small bug that can happen sometimes where the animations will get generated improperly. If you avatar sinks into the ground, just regenerate the animations. I'm working on a way to fix this, however it's super inconsistent when it happens, and I haven't found the cause yet. 
If you know the cause, please let me know. 
