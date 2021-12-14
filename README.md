# TR2 Gold Installation Guide
The intent in distributing this guide and patch is to streamline the process of setting up a working, speedrun-legal version of TR2 Gold.

> Acronyms Used:
> * TR2 = Tomb Raider II, the original game released in 1997.
> * TR2G = Tomb Raider II Gold / Tomb Raider II: Golden Mask, referring to the separate adventure released in 1999.
> * EXE = Executable file

## Table of Contents
1. [Installing TR2 Gold](#Installing-TR2G)
2. [Patching TR2 Gold](#Patching-TR2G)
3. [Some Explanation](#Some-Explanation)

### Installing TR2G
#### Downloading the Game
* Download TR2G using [this link](https://tombraiders.net/stella/files/gamefiles/TR2files/tr2gfus.zip) from Stella's website.
#### Installing the Game
##### Unblock the ZIP:
* Right-click the downloaded ZIP
* Click Properties
* Near the bottom beside "Security", check the box that says "Unblock"
##### Extract the ZIP:
* Right-click the unblocked ZIP, select "Extract All..."
* Choose a location you will remember (this is not the final installation of the game, so this location can be temporary)
##### Run TR2G's installer:
* Inside of the extracted folder, run  `Setup.exe` (if file extensions are hidden, you will only see `Setup`)
* Follow the installation wizard, being sure to install the game in a location you will remember
  * For the rest of this guide, this location will be referred to as the "TR2G installation folder"

### Patching TR2G
#### Downloading the Patch
Visit [the latest release](https://github.com/TombRunners/tr2-gold-installation/releases/latest) and download the ZIP file (not the source code) in a place where you can easily locate it.
#### Installing the Patch
* Optional: backup TR2G's original EXE file
##### Unblock the ZIP:
* Right-click the downloaded ZIP
* Click Properties
* Near the bottom beside "Security", check the box that says "Unblock"
##### Extracting the ZIP:
* Extract the contents of the unblocked ZIP into the TR2G installation folder
  * Right-click the unblocked ZIP, select "Extract All..."
  * Browse and select your TR2G's installation folder
  * If you didn't rename/move TR2G's original EXE file, confirm you want to overwrite it
  * You should also see a new TXT file with the same name as the EXE (this file is just documentation and could optionally be removed)

### Some Explanation
Previously, the Tomb Raider speedrunning community had minimal to no regulation regarding which versions and modifications were allowed when speedrunning TR2G.
Generally, it was advised to install the version available from Stella's website.
One problem that the Stella's website version has, however, is that it expects a CD to be available; in order to play, one must either use their TR2 game CD or circumvent the issue.
The most common circumvention was to replace TR2G's EXE with an EXE from TR2.
But doing so causes "new" enemies' AIs to break (namely, the wolves and the bears).
The community agreed that this was undesirable, and should be fixed.


A resident expert was contacted to patch the original EXE such that it no longer checks for a CD.
The precedent for this action already existed: similar "No-CD cracks" had been created and were (and still are) considered legal for TR2 speedrunning
In the Release ZIP file, there is a `t2gold.txt` which explains more exactly the modification made.
No additional modifications are permitted; this also matches the rules precedents of TR2.
