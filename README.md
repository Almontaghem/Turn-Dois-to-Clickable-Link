If youre using Mendeley Desktop V. 1.19.8, use this Macro in VBA Environment to convert any bibliographies URL to clickable links!

Open your manuscrript file, press Alt+F11 to open VBA, then click on Insert and then Module.
In the Blank space past the code and the click on Run (also shows as a play button) 
It will change all of your URLs starting with https:// to clickable links.

you can also save this macro and then assign a shortcut for it:

Step 1:
On the left side, look at the Project Explorer (if you don't see it, press Ctrl + R).
You will see Project (Document1) and Normal.
Press Ctrl + S to save. You can now close the VBA editor.

Step 2: Create a One-Click Button
Now you can add a button to your Quick Access Toolbar (the little icons at the very top left of the Word window) so you can run it instantly.

In Word, go to File > Options.
Click Quick Access Toolbar on the left menu.
In the Choose commands from dropdown menu, select Macros.
Find Normal.Module1.TurnDOILinks_Final (or similar) in the list.
Select it and click the Add >> button in the middle.
Click OK.

to assign a shortcut for it, In Word, go to File > Options.
Select Customize Ribbon from the left-hand menu.
Look at the bottom of the window next to Keyboard shortcuts and click the Customize... button.
In the new window that pops up:
Categories (Left side): Scroll all the way down and select Macros.
Macros (Right side): Find and select your macro, likely named Normal.NewMacros.FixDOILinks_Final (or similar).
Click inside the Press new shortcut key box.
Press the key combination you want to use on your keyboard (I recommend Alt + W or Alt + L).
