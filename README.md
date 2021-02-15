# LenksRLSS
**Tested on Steam Rocket League, but it should work for Epic Games as well.**

Extends the Rocket League game resolution for two monitors.


I didn't write proper documentation, so I'll have to update this later.


### Instructions
1. After downloading this project, run the executable and a message box should appear for auto-installation. Click 'yes' and it will begin setting up files inside of:
> Documents/My Games/Rocket League/TAGame/Config

>   If you don't receive an auto-installation prompt, then the program failed to find the path above or the *TASystemSettings.ini* file does not exist in said path.
>  In this case, try launching Rocket League— which will recreate a *TASystemSettings.ini* file— and exiting the game after entering the lobby. After that, relaunch > this program and the auto-installation prompt should appear.
>
>  If that fails, you will need to locate the directory which houses the *TASystemSettings.ini* file.

2. During your first startup, or if resolution changes have been made to the secondary monitor, a window should appear that asks you to drag it to the second monitor.
Simply drag it to another monitor and it will update itself to compare resolutions to your primary monitor. If the two resolutions match, an orange checkmark should appear. Click that and the main window should appear.

>   If the resolutions are different, open the windows search bar and type *Display Settings*, there should be an item that has *System Settings* as a descriptor, click that. Use the Display Setting window to match the two monitor resolutions. 

3. All that's left is to click the controller icon to swap between single monitor to double monitor, then launch Rocket League.


### Controls
- **Controller Icon**: Swap between single monitor to dual monitor.
- **Update Mode Settings**: Replaces the current mode's file with **TASystemSettings.ini**. (Use this to save changes made in Options>Video)
- **Configuration**: Click to expand program and show setup options.
  - **Set Rocket League Folder**: Opens a folder dialog. If auto-install fails, use this to navigate to the: <br>`Rocket League/TAGame/Config`.
  - **Set Screen Files**: After finding the Config folder, click this to create the required files for changing modes.
  - **Try Auto Install**: This will try to locate the directory for **TASystemSettings.ini** and create the necessary files to use this program.
  
