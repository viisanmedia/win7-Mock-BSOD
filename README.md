# win7-Mock-BSOD
Want to prank your colleague or class mate that they've blue screened? Then check this!
The prank is most believable on Windows 7 and Vista machines. Windows 10 version coming in the future.

## Preview of prank

Yes, this is a Mac running Windows 7.. Blame the college not me.
![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/preview.jpg "Yes, this is a mac running Win7")

## How to set up the prank

If you don't know how to save the code to a .hta file, you can download it from here: https://i.memenet.org/ibvmjo.hta

**Pre-requisites:**

	A computer running windows 7
	A friend or colleague stupid enough to leave their PC unlocked
	A copy of the code saved as a .hta or downloaded from the link above

1. First of all, decide which icon your victim uses the most. My buddy uses the 'My Documents' folder on his desktop the most, so I will demonstrate with that. The following instructions work with all icons minus the 'My Computer' and 'Recycle Bin' icons.

2. So for now, remove his shortcut for his documents on the desktop by right clicking and pressing delete.

3. Now we right click the desktop and then go to new > shortcut. We then need to locate the file you downloaded (I've named it folder to reduce suspicions) from above and select that as our shortcut.

*See images below for help*

![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/fig%202.png "new shortcut")
![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/fig%203.png "select mock bsod code")

4. Now hit the next button and call the shortcut whatever shortcut you have replaced, in my case I'm calling it 'My Documents' and now your shortcut has been created. 

5. But you may have noticed, the shortcut's icon is not a folder icon. To correct this simply hold shift and right click the shortcut you have just created and click properties. Now press 'change icon' and select the folder icon, if you cannot find it, where it says "Look for icons in this file:" copy and paste this path: *%SystemRoot%\System32\shell32.dll* and it should be there. Now hit apply and your shortcut is complete.

*See images below for help*

![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/fig%204.png "editing shortcut")
![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/fig%205.png "changing shortcut icon")
![preview](https://github.com/viisanmedia/win7-Mock-BSOD/blob/master/images/fig%206.png "shortcut complete")

6. Time to wait for your victim to unsuspectingly access their shortcut and to their surprise, the computer instantly blue screens.

## How to reverse the prank's effects

The only way to reverse the prank is to do a hardware restart or shutdown. In future updates I may add a safe key to reverse the effects of the prank.

# Caution!

I **do not** take responsibility if this breaks your system. Although it has been tested to only disable right click, end the explorer.exe and taskmanager tasks, things can go wrong dependant on your system. 

Make sure that your victim wasn't doing anything important or hasn't saved their work beforehand.
