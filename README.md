This is still a work in progress conversion to UDON. Things are broken right now.

Version 3.0:
Fix for UDON




# Vrchat-Dance-Pad
An InStation pad that relys on Final IK to disable Fullbody tracking for dance animations

# Things to have imported before using

Required | Link
------------ | -------------
VRC SDK3 Worlds | https://vrchat.com/home/download
CyanTriggers | https://cyanlaser.booth.pm/items/3194594
FINAL IK | https://assetstore.unity.com/packages/tools/animation/final-ik-14290

# How to Use
1. Extract the Prefab Folder and Meta file into the ASSETS folder
2. Go to the tools folder and follow the steps on how to add the The IK Disabling to your dance
3. Select your new Dance and check the following in the Inspector
	- Loop Time 		(UNCHECKED unless you want it endless)
	- Bake into Pose 	(ALL CHECKED)
	- Based Upon 		(Original...and maybe feet on Y in some cases)
2. Drop _DancePad Prefab into scene
3. Add your dance animation to the 'CustomDance' Override Controller
4. Bam! You're done, have a cupcake.

# Credits

- jebuzjack: Setting up the DancePad for UDON
- Splinks: For making the original version forked from Github https://github.com/splinks/Vrchat-Dance-Pad
- CyanBlue: For making the animation merger script located in the tools folder
- ★Megumin★: For adding viseme fixes
