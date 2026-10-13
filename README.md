# Crispy-Master-Menu V1.3 for Crispy Doom (Iwads, custom wads, Master Levels, Maximum Doom).


![crispy v1.3 1.jpg](https://github.com/nicoku007/Crispy-Master-Menu-v1.2/blob/main/crispy%20v1.3%201.jpg?raw=true )
![crispy v1.3 2.jpg](https://github.com/nicoku007/Crispy-Master-Menu-v1.2/blob/main/crispy%20v1.3%202.jpg?raw=true )


Description: Crispy-Master-Menu is derived from my other project called "Choco-Master-Menu". It features the same functions as Choco-Master-Menu: a menu for Master Levels, Maximum Doom, Iwads, custom wads, Multiplayer, recording demos, viewing the master server, local server, etc.
                       
Launcher features:

Iwads: the possibility of choosing the Iwad to play without the need to enter crispy-doom.setup to configure a specific Iwad or to have 4 folders with their respective Iwad.

Custom wads: The possibility of playing with custom WADs from the community or your own, you can also combine different WADs if the game requires it, for example: Back to  SaturnX "btsx_e1a.wad + btsx_e1b.wad", mix MIDI or MUS files with a WAD if a WAD has it, Hell Revealed: "HR.WAD + HRMUS.WAD" or also you can use DEH files for a WAD that uses special textures, "1k3v1a.wad +   1k3v1a.deh".
 
Master Levels Menu: The launcher has a menu for playing the Master Levels for Doom 2, eliminating the need to enter cumbersome parameters in the command line to select each map. The   menu also includes the Master MIDI Pack to add musical variety to the levels. (Thanks to Peter Lawrence for allowing me to use the MIDI Pack for the menu.).

Campaign mode for Master Levels: Integrated an automated virtual campaign data streamer for the Master Levels that generates temporary engine scripts natively in Windows Temp. This completely insulates and safeguards original game files against modifications, deploying an automated garbage collector to erase all temporary virtual files instantly on process exit. The second part of the campaign features a new sky with dark green clouds to match the launcher's default color (Muted Military Green).

Maximum Doom: The launcher has a session for Maximum Doom, the wads are separated into "maximum Doom 1" and "Maximum Doom 2" and are programmed to work only with their own  Iwad "DOOM.WAD" or "DOOM2.WAD".

Multiplayer: The menu includes options for multiplayer, cooperative deathmatch, deathmatch 2.0, private server, setting your server name, UDP port, auto join, as well as using server   address. Each menu session has multiplayer options that only work for that session to prevent errors.

Player name: The launcher can detect the crispy-doom.cfg file, allowing you to change the player name from the menu without needing to use crispy-doom.setup.
 
The need to use quotation marks has been eliminated: Quotation marks (" ") are configured within the launcher's code, so there is no longer any need to use them when entering the server or player name.

Parameters: Each menu session has parameters to modify the game if you wish. These include: No monsters, Fast monsters, Respawn monsters, and Turbo.

Extra parameters option: a text box allows you to enter and use parameters that are not found in the launcher.

Demo: Each session has the option to record and view demos of your games; the "Demo File" button is used to search for the lmp files you have created.

Master Server and Locar Search: the possibility of viewing the Chocolate Doom master server or searching for a server in the local area.

Added a dedicated "Color" layout tab featuring 2 independent 16-color MS-DOS CGA/EGA/VGA style selection ListBoxes to adjust backgrounds and fonts natively.

Note: MS-DOS colors were too bright for modern screens, so the colors were softened to avoid eye strain

Border Customization: Added a third color ListBox, allowing you to choose from 16 different colors to customize your launcher's borders

A brightness selector for both background and font colors was added as an extra measure to prevent eye strain.

Exclusive Feature: Integrated native map selection support for John Romero's SIGIL and SIGIL II directly within the 'Level Select' ComboBox. This implementation explicitly exploits Crispy Doom's expanded engine limits to comfortably warp and handle these extended map slots and episodes (latest versions of Crispy Doom are highly recommended).

INSTRUCTIONS:                                                                 
  
 1: All you have to do is put Crispy-Master-Menu.exe in the same directory where you have crispy-doom.exe. 
 
 2: You need the Master Levels wads, Put the Master Levels wads inside the folder called "master-wads", the folder is included in the zip file.

 3: Put the maximum doom wads corresponding to DOOM 1 inside the folder called "maximum1" and the wads  corresponding to DOOM 2 inside "maximum2". The folders are included in the  zip file.
 
 4: Put the iwads in the same directory: "DOOM.WAD, DOOM2.WAD, TNT.WAD, and PLUTONIA.WAD". This way you can select them from the menu without having to go into crispy-doom.setup and if you have plutmidi.wad in the same directory, the menu will detect it automatically.

 Crispy-Master-Menu by Nicokugame007.
 
 Credit for the Master Midi pack goes to Peter Lawrence.
