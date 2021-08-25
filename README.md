![Logo](https://i.imgur.com/CGEEugR.png)

# Streamlined Skyrim

- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Graphical Settings](#graphical-settings)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
    - [Getting an ENB](#getting-an-enb)
    - [Profiles](#Profiles)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Performance stuff](#Performance-stuff)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

Streamlined Skyrim offers modernized combat, new quests, roleplay mechanics, fully voiced followers, straightforward gameplay, overhauled locations all while staying performance friendly. Most of the gameplay changes are vanilla plus and minimalistic (except for the combat) keeping things nice and simple. Skyrim's combat has been brought up to 2021 standards making it exciting and challenging. Once you learn the basics of the list you are able to play the game without needing to micromanage. The modlist makes Skyrim, well, streamlined.

Streamlined Skyrim is a fork of the fantastic SME/FT list which I highly recommend to those who want to create their own modlist for Skyrim Special Edition.

If you want to take a look at the full modlist here is the link: https://modwat.ch/u/TerribleBrad/plugins

**Please read the ReadMe in Full. The installation process is not completed once you have finished the Wabbajack installation.**

Wabbajack Link: https://drive.google.com/file/d/1yWriviHTeducFEP-7TNCU16efVCWkoad/view?usp=sharing

# Noteworthy Mods and what gameplay to expect.

An entire document has been made to give you as much information as I could without going too deep in analysis of mods. This document is called **[Modified Gameplay.md](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md)** and acts as a second readme for the core gameplay and questions about what to expect. So go read [it](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md)! 

# Installation
### Prerequisites
#### PC Specifications
Aldrnari is meant to use every single inch of my computer, and here are my specs:
  - I7-7700k
  - 1080Ti Zotac - 11GB of VRAM
  - 32GB of 3200mhz DDR4 RAM

Full PC Part Picker setup is [here](https://fr.pcpartpicker.com/list/ZHQQgt). I would recommend atleast 8GB of VRAM for 1080p, and for 1440p you will need a minimum of 10GB of VRAM, although more is highly recommended. I do not have stable 60FPS on 1440p everywhere with my setup because, frankly, I do not care about framerate if combat is fluid and I can take sexy screenshots. The average is 60FPS with dips in 50FPS in very few areas at 1080p because my screen is a 3840x1080p (no I don't play in ultrawide, that's pointless and no support will be offered for that either).

No performance options are available for now as this is a Beta; however, this may change at some point. If your PC does not meet the specifications required for this list, my other list, [QWEST!](https://github.com/SovnSkyrim/QWEST), will probably work for you. It's made so that everyone can play it.

Disclaimer: Any questions regarding the specs and performance of the list will be redirected to here if you're asking me. I cannot stress how much I will not change the performance of the list. It is primarily made for screen-archery with innovative gameplay. You are free to modify the list once you have it to fit your frames dream, but I will not support you in doing so.
#### Size on Drive
Aldrnari is a big list, it requires:
  - Over 135GB for the Downloads folder
  - Over 200GB for the Installation folder
  - an additional 25GB for the temporary files during Installation

So 360GB **minimum** is required. I cannot stress how much a SSD is needed for **at least** the game and the list. You can put your downloads in an HDD and it will only slow your installation process.

### Pre-Installation

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be ``C:\SteamLibrary`` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

#### Change Steam's Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133).

If you ever used Vortex to mod Skyrim SE, using the Shredder becomes a critically important step, as Vortex will conflict heavily with any Wabbajack installation, so backup your stuff or shred it.

If the Shredder is unavailable at the time you read this, manually uninstall Vortex and manually delete the `Skyrim Special Edition` folder located in your `SteamLibrary\steamapps\common`, where your SteamLibrary is.

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after shredding or cleaning it manually.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

## Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

Wabbajack will not work with Windows 7, I will not offer any kind of support for users of that operating system.

You will also need those files that tend to not download themselves; so I'd recommend you download them manually, and simply drop them in your WJ downloads folder. This is the folder you set in the next step when starting the install. Do NOT unzip the files, just download the zip, and drop it in the folder as is. WJ will then realize the files are present and move on with the rest of the download.
 
- https://mega.nz/file/xUc0zRLY#NYwbmmHOZhpSF2hpV7hMRYejgZsL_MAIVv_DfjK9JRM - Elwaps Speedtree
- https://mega.nz/#!x0QWjKKL!B9xkI29Dg0YoBPAo1fyXa_PxtBoma_f4UmSMOiwnv2A - HG Hairdos
- https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg - xLODGEN.83
- https://mega.nz/file/qVhVFKKL#s1Zl20rqkJ8JWwmXWjm-2PRT9xC0_PwGqVnH9ktisvg - Book Of The Dead Trees (1)
- https://drive.google.com/uc?id=1WOviY3mC7Zc9Nx408BTAMXK9DIdiwzeK&export=download - [Dint999] HairPack02 SSE (v0.09)
- https://drive.google.com/uc?id=1k6i0-iqZf8ErqoCV1dX4DnwmjBKwQ5pL&export=download - Mordhau Pack by Team TAL
- https://drive.google.com/uc?id=1BsgFAq7t1aDEjl2i8h4OHLgcYU8g_4gv&export=download - Mordhau Weapon Pack by Team TAL

## Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open the Wabbajack.exe and select "Browse Modlists".
2. Scroll until you find Aldrnari, you can make it easier using the filter at the top for Games, in it select Skyrim Special Edition.
3. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Aldrnari".
4. Select the created folder in 3. as your installation folder.
5. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish.
6. Put the files downloaded in the prior step into this folder AS IS. Do **not** extract the archives.
7. Select the created folder in 5. as your downloads folder.
8. Click the Go/Begin button.
9. Wait for Wabbajack to finish.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

Some files are known to be problematic, it is likely those are the ones that failed. You can download them here and place the archives **AS IS** in the downloads folder.

- https://mega.nz/file/xUc0zRLY#NYwbmmHOZhpSF2hpV7hMRYejgZsL_MAIVv_DfjK9JRM - Elwaps Speedtree
- https://mega.nz/#!x0QWjKKL!B9xkI29Dg0YoBPAo1fyXa_PxtBoma_f4UmSMOiwnv2A - HG Hairdos
- https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg - xLODGEN.83
- https://mega.nz/file/qVhVFKKL#s1Zl20rqkJ8JWwmXWjm-2PRT9xC0_PwGqVnH9ktisvg - Book Of The Dead Trees (1)
- https://drive.google.com/uc?id=1WOviY3mC7Zc9Nx408BTAMXK9DIdiwzeK&export=download - [Dint999] HairPack02 SSE (v0.09)
- https://drive.google.com/uc?id=1k6i0-iqZf8ErqoCV1dX4DnwmjBKwQ5pL&export=download - Mordhau Pack by Team TAL
- https://drive.google.com/uc?id=1BsgFAq7t1aDEjl2i8h4OHLgcYU8g_4gv&export=download - Mordhau Weapon Pack by Team TAL

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

## Copy Game Folder Files

When the installation is complete, copy the files in the `Aldrnari\Game Folder Files` folder and paste them into your Skyrim folder (with the SkyrimSE.exe and the data folder). [HERE](http://prntscr.com/124984m).

## Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.
A pagefile is a file on your disk Windows will use when there is not enough RAM available.
Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:
1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

## Getting an ENB

Aldrnari comes with 3 ENBs tweaked for the list's Setup:
- fnenb by Foxnne
- Pacific Blue by FOSSTEN
- Apex Somber by Digital Dreams

Info on them is in [Modified Gameplay.md](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md) so I highly suggest reading it. (use control + F key combo to search for ENB).

How to install them? Simple, in the **installation folder** there will be a folder named **ENBs**, in there the three ENBs are located. Simply **copy the contents of the folder named after the preset you want to use to the Skyrim Special Edition folder**, same way as the "Copy Game Folder Files" step.

## How to start up Aldrnari

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

Upon pressing New Game, you will spawn on the walls of Helgen burning down. Once all the messages on the top left corner of the screen are gone, set the MCMs as instructed below.

If you press enter, you will be teleported to a location where you will be able to personalize your character.
After confirming your character, please note that you should not use the 'showracemenu' console command to change sex or race, it will break a lot more than you think. If you want to customize the MCMs or need some more time to setup Skyrim Unbound, you can use the "Stay there" option.

Do NOT Select a NON DRAGONBORN OPTION within Skyrim Unbound! Doing so will result in broken questlines! You cannot escape your destiny!

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible.  Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
Once the game has loaded, wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

MCMs are not automated due to a personal choice: There are many important tweaks, a mountain of informations, and useful stuff in them that can solve problems or make your experience better. Those are my own and what I recommend for the least amount of problems and a balanced experience.

Do NOT Select a **NON DRAGONBORN OPTION** within Skyrim Unbound! Doing so will result in broken questlines! You cannot escape your destiny!

#### Game Difficulty
- The difficulty in this Modlist is quite harder (more info on that in [Modified Gameplay.md](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md)) so I highly suggest not using Legendary. I personally play on Expert. Adept is also fine.

#### A Matter of Time

- Presets :
  - Load User Settings

#### All Geared up Derivative
- Weapons - Player
    - Shield Stay on arm while Equipped: Enable
    - Toggle un/equipping Torso Armor: Enable 
- Misc. Player :
  - Require Torso Armor : Enabled
  - (you can tweak stuff showing on you whenever you want, if something bothers you)
- NPC :
  - Enable Weapons : Enabled

#### Better Vampire NPCs
- Not an MCM   
    - In your inventory there's an item called "Vampire's Bloodgem" allowing to tweak stuff by clicking on it while crouched. 
        - I leave it as default. You can tweak it all you want. Experimental stuff may cause issues as expected. When done drop the bloodgem.

#### Campfire
- Gameplay
  - Hotkeys
    - Set your Hotkeys however you want
    - I go by :
    - Create item : N
    - Build Campfire : B
    - Harvest wood : H
    - Instincts : Nothing

#### Cold Region Behavior
- General Settings
	- Main Settings
		- Enable Mod Features

#### Engarde: 
- Keybutton
    - Defensive Actions
        - Modifier is by default Shift
        - Swap stuff around depending on what you want, leave as default if you're new to Engarde. Keep in mind off-hand action requires shift to be pressed
        - Defensive Action key: C

#### Follower Framework
- System :
- Settings
  - Load From File

#### Forgotten Magic - **Important**
- Settings
    - Spellbooks Drop Chance: 0.0
    - Jewelry Drop Chance: 0.1
- The Tabs above Settings is where you'll level up your spells once you acquire them.
- [You will acquire them despite the drop chance, do not worry!!](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md#gameplay---main-overhauls--perks-races-standing-stones-magic-religion-and-alchemy)
- 
#### Heartbreaker (Optional) 
- Main Settings
    - Learn Spell Power: Enabled
    - It gives you a power to put npcs in stagger once per IRL hour so you can rip out their hearts; you can also bind it so you can do it anytime.
  
#### Less Intrusive HUD: 
- General Settings
    - FileAccess Interface
        - Load Personal Preset

#### MoreHUD:
- Presets
    - Load User Settings?: GO

#### OBIS - Bandits
- Leave as is
    - Why? Enabling in the MCMs is only for the additional spawns option, but that is not the aim of the encounter mods chosen in Aldrnari. I'm buffing everyone instead of giving you hordes of enemies.

#### OBIS - Patrols
- Settings
    - Enable: Enabled

#### Optimal Potion Hotkey
- Set one keybind (mine is "<" for Health only, I don't use the other ones)

#### Radiant Requirements
- Settings
  - Dragon lair: 10
  - Draugr Crypt: 5
  - Forsworn Camp: 10
  - Hagraven Nest: 20
  - Vampire Lair: 25
  - Werewolf Lair: 25
  - Dragon Priest Lair: 25
  - Falmer Hive: 20
  - Giant Camp: 20
  - Spriggan Grove: 10
  - Warlock Lair: 1

#### Real Names
- Basic Options:
	- Settings
		- Strangers Mode: Enabled
		- Title Preference:Title and/or Surname>Epithet
	- Special Exclusions:
		- Exclude Dragon Priests?: Enabled
		- Excluse Corpses?: Enabled

#### SkyUI
- Advanced → SWF Version Checking : 
  - Map Menu : Disabled
  - Favorites Menu : Disabled
  - Inventory Menu : Disabled
  - Barter Menu : Disabled
  - Container Menu : Disabled
  - Crafting Menu : Disabled

#### SmoothCam  -for 3rd person players-
- Presets
  - Load Preset
    There are two presets available for you to use. I personally prefer the Modern one but some prefer Souls Like, try both and see which you like!
- Make sure only the Alternate Conversation Camera Patch is ticked in Compatibility.

#### Thieves Guild Requirements
- Misc Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)
  
#### Timing is Everything
- Extra Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)

#### VioLens
- Load Preset

#### Widget Mod: 
- Maintenance
    - Load User Settings? : Do it!

# How to start playing

After you finish customizing all the MCMs, the last thing to check is the Skyrim Unbound MCM. You can safely experiment with all the options in there, **EXCEPT choosing a Non-Dragonborn character.**
Anything else in that menu can be customized to your liking. When you're ready, simply press the Start Adventure button in the Unbound MCM. You will then be prompted to create your character as usual.

Please Note: Do NOT change sex or race with showracemenu after first confirming your character.

## FAQ

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

### Ultrawide Options

I have an ultra-wide, but it's just not worth the hassle of setting Skyrim up for it, in my opinion. Skyrim isn't made for it; if you disagree, check [this guide](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing) by my friend Mantis for compatibility with such screens.

### I have a question

Ask it in my Discord, link [here](https://discord.gg/ZgjVrXp) or Wabbajack's Discord, [link here](https://discord.com/invite/wabbajack). But make sure you're using the right support channel and not a general channel!

### A face part is crashing me! | Some hair/facial hair clips!

The 5th Facepart is a lie. Known and unsolvable. | Make sure to have selected a High Poly Head under Face Part, some hairstyle will remain bugged but it is known and I do not know how to fix them. The mod they're from doesn't only offer those bugged hairstyles so it remains for the rest of what it proposes.

Some NPCs have a neck seam, that's known, I'm waiting for an update of [EasyNPC](https://www.nexusmods.com/skyrimspecialedition/mods/52313?tab=description) to solve them, I talk to the author so don't worry, it'll come. Play with them for now.

### What perk does the new weapons use?
- Rapiers get sword perks
- Pikes get greatsword perks
- Halberds get two-handed axe perks
- Quarter Staffs get war hammer perks
- Claws get dagger perks
- Whips get mace perks

### My character T-Poses!

Cap your framerate, either with BethINI, SSE Display Tweaks, or ENB.

### "I am bothered by the way NPCs look in the game!" and "How do NPCs look?? Are they rugged? Are they supermodels? Are they vanilla?"

I really do not care and won't take your opinion into account. I've scoured a lot of NPC overhauls (from Eeekies', Northbourne, to Bijin, Pandorable or the Re-imagined Series) and handpicked them for the list so it fits ***MY*** tastes.

If you wonder how they look, [here's a document which lists what overhauls who (for vanilla NPCs)](https://github.com/SovnSkyrim/QWEST/blob/main/NPC%20Merge%20Notes.md). 

If you do not find someone, they're either from [Pride of Skyrim AIO](https://www.nexusmods.com/skyrimspecialedition/mods/48904) if a male, or [Courageous Women of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/50812) if female. If neither of those have an overhaul, it'll be from [High Poly NPC Overhaul - Skyrim Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/44155). 

Any criticism on that is NOT welcome, and it is, in fact, the only aspect of the game I do not take ANY criticism from. Hearing complaints about this stuff gives me an instant headache. I cannot please everybody, so I decided to please myself.

### Creation Club (CC Content) Support?

No, I don't like them.

CC Content isn't considered like DLCs (Dawnguard/Dragonborn/Hearthfire) and will never be treated as such.

Using them with Aldrnari would be like installing your own mods: Support is forfeited and they will NOT work without patching.

### Why don't you wanna use Inigo/Legacy of the Dragonborn (LOTD)????? They're the best mods ever!!!!
[Modified Gameplay.md](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md) has the answer, use Ctrl+F in there. Refusing to hear my opinion and accept it is a warnable behavior in my Discord.

### Some sounds are missing, for example weapon swings/footsteps

This can happen on rare occassions if your game and modlist are not both installed on your C:/ Drive. To fix it, please follow the instructions below, this does not void support:

1. First download and install Link Shell Extension which can be found here: http://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html.
2. Navigate to your Skyrim/Data folder and look for a file named Skyrim - Sounds.bsa. Copy this file and paste it somewhere on your main drive.
3. Delete Skyrim - Sounds.bsa from the Data folder.
4. Go back to where you copied Skyrim - Sounds.bsa on your main drive. Right click on it and you should see an option that says "Pink Link Source". Click that.
5. Go back to your Skyrim/Data folder. Right click anywhere and choose "Drop As" and then "Symbolic Link". You will see your sounds file with a shortcut symbol. You know it works when you do."
6. Repeat this process for the file Skyrim - Voices_en0.bsa
This would be enough for vanilla skyrim, but since this list uses a ton of different sound and audio mods, we are not quite done.

In your Aldrnari MO2 instance, you will locate 2 seperators, one called "Audio", and one called "Music". You will need to repeat the process described above for every single mod in these two categories to make sure you have every single sound working properly. I know its tedious, but this is the only fix for this rather rare issue.

However, instead of only taking the BSA files from each mod, i suggest taking the entire Mod folder, because it will help keep things organized.

So, as an example:
I made a folder called "Aldrnari Sound Fix" on my C:/ Drive. This folder now contains the two vanilla BSAs, plus every single Audio or Music mod. These are all sym linked back to the original mod folder. Im aware this is not optimal for people with seriously tiny C Drives, but its as good as it gets. For any questions regarding this specific issue, please @ Chanka on Sovns discord or the Wabbajack discord.

### Please give us more fps... / A more performance friendly profile??

It's a beta, it's a WIP, and I can't please everyone by now, but I can give you some info.

I have 2 tips that voids you support as per Rule 11 of both Wabbajack and my Discords.
- Regenerate DynDOLOD with other settings, not High
     - Current DynDOLOD uses High and Ultra Trees, those are known to be FPS Heavy
- Follow this set of instructions to put your ENB in a more performance mode:
     - In Enbseries.ini; change those values:
     - [EFFECT]
	- EnableDepthOfField=false
	- EnableNormalMappingShadows=false
     - [SSAO_GAME]
	- AOAmount=0.0
	- AOAmountInterior=0.0
     - [SSAO_SSIL]
	- UseSelfIntersecting=false
	- SourceTexturesScale=0.25
	- SamplingQuality=1
	- If you put intersecting to false, I strongly you to change SamplingRange=0.24 to SamplingRange=0.40 for balance the AO on face NPC in exterior
     - [COMPLEXFIRELIGHTS]
	- EnableShadow=false
     - [COMPLEXPARTICLELIGHTS]
	- EnableShadow=false
	- EnableNormalMappingShadows=false
     - [REFLECTION]
	- Quality=-1
     - [UNDERWATER]
	- HighQualityCaustics=false
     - [WATER]
	- EnableTessellation=false

Those are the easiest tweaks you can do.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Althro for the creation of the base, managing and curating the discord and being a very resourceful person. None of my work would simply exist without you. 
- KFC for all the mental support, help during development, and volunteering to help. 
- Chri3i for all the help during development, you are and keep being, a never ending help which is loved.
- TheSpaniard and Chanka for all the support you're doing.
- Crithion aka m.vlad for the art; trully amazing, I never spent my money so well.
- Every each of my Patreons for supporting me, and with the Special Folks of my discord, for helping with the development.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the Discord. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Changelog

See [Changelog](https://github.com/SovnSkyrim/Aldrnari/blob/main/Changelog.md).
