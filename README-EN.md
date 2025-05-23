⛔️ DEPRECATED
-------------
This project will not be updated and will be removed completely.
Use https://github.com/ShubbeLeontij/sightgenerator/releases/

Installation
---------

There are two installation methods, the first is simpler, and the second gives more freedom of customization (if GUI offers not enough, you can try editing the defaults.py file or other program files), but requires the user to have basic terminal skills for installation.
1) Folder with exe file\
Download zip https://github.com/ShubbeLeontij/sightgenerator-exe/archive/refs/heads/master.zip \
You do not need to download anything additionally, however, at the first start, the antivirus may react - allow it to run the file.

2) Python project\
Clone the project https://github.com/ShubbeLeontij/sightgenerator, download and install python3 (if not already installed) https://www.python.org/downloads/, make sure "ADD Python to PATH" and "td/tk and IDLE" are checked.
Install the required libraries (pip install -r requirements.txt).
In the project folder, you need to run GUI.py.

Settings
---------

There are many options in the settings menu, most of which are explained by tooltips.
If it is still not clear what this setting is responsible for, there is PREVIEW, roughly showing what the changes will lead to.

The left side of the menu is the global settings that apply to all sights.
The right part is separate for each sight type - they are switched using the menu in the upper right corner.
The name of each sight type begins with the mode for which it was created (AB, RB or sim) - the arcade one differs from the realistic one by default only in the presence of a rangefinder, while in the simulator ones parallax is taken into account.
In the case of the sim, the projectile type is next (AP, HEAT, APDS or HE), and there is also sim_LASER for tanks with a laser rangefinder.
Postfix can follow - _s for slow (<500m/s) shells and _f for fast (>1100m/s) shells.
There is also a CLEAN type - an empty sight, which is convenient to use on ATGM carriers and AA.

For simulator sights or if you just want to use circles instead of the standard markers, there is the EDIT SIM CIRCLES menu - in it each line creates a distance marker using a circle.

After changing the settings, remember to press SAVE SETTINGS AND EXIT TO MAIN MENU, simply closing the window will cancel all changes.

If you want to know what sight types the tank uses, you can open data.xlsx - a table based on which sights are built. Each line is a separate sight. For convenience, the data is divided into pages.
Columns from left to right: tank name, convergence in meters, muzzle velocity in m/s, gunner's sight zoom (minimum), sight type, then data from AssetViewer related to the location of the sight relative to the barrel (zeros in case of no parallax).

Launch
------

In the main menu, there is a choice between three options for logging details, a field for entering the path to the game (don't forget to save) and columns for selecting sight types (pages from data.xlsx) in case you don't want to litter with unnecessary ones. Clicking on the top label will remove or add a tick to the entire column.

Next, to create sights, press RUN or Enter button on the keyboard.
If everything went well (if you did not set the path to the game, do not forget to transfer the folder), press Alt + F9 in the game to update the sights and select the desired sight in the settings (the name contains a prefix depending on the presence of sight enlightenment, then the sight type and the name of the tank).

Contacts
--------

For all questions Discord https://discord.gg/qjvECBPUxq or Leontij#8405

Support
---------

If you like what I did https://www.donationalerts.com/r/leontij
