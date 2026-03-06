Myshort works by first reading the contents of the config.txt file then parsing it into usable C++ code.

Important notes and instructions:
-config.txt MUST remain in the same directory as the exe
-config.txt CANNOT be renamed
-the exe runs in the background with no visible GUI
-for commands requiring elevated privileges must run as admin


Inside the Config file ONLY write the shortcut statements.

The format for the shortcut statements is as follows
new Controlkeys+HotKey
Terminal command to be executed

-There must be a space between new and the control keys
-You can add multiple control keys the available keys are listed bellow
     -CTRL
     -SHIFT
     -ALT
-Only one instance of a control key can be used at a time inside a single shortcut statements
For example
   - (new CTRL+CTRL+H) is wrong 
   - (new CTRL+SHIFT+ALT+H) is valid

 How to Add to Startup:
1. Press `Win + R`, type `shell:startup`, and press Enter.
2. Copy `MyApp.exe` into the folder that opens.

 How to Remove from Startup:
1. Open the same `shell:startup` folder.
2. Delete `MyApp.exe` from it.

There is a built in shortcut to immediately terminate the program
- To end the process press CTRL+SHIFT+BACKSPACE
  
