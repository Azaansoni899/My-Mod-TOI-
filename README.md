# My-Mod-TOI-
### Installation
If you are updating your Town Of Impostors version, please hop to this section here.

Before installing, verify your Among Us version by launching the game and checking the version displayed in the top left of the main menu.

As of the Among Us v2021.3.31.3s update, you must sign in to your account and set your player name now to avoid issues later such as setting your name or typing in the chat in the modded game.

Download the Mod for your specific game version from the table below or check all releases here. ENSURE THAT YOUR AMONG US VERSION MATCHES EXACTLY - EVERY DIGIT, LETTER, DOT & ALL.

Make a copy of your clean, unmodded game’s root directory Steam/steamapps/common/Among Us and rename the copied directory to whatever you want e.g. Steam/steamapps/common/Among Us Town Of Impostors. This copied directory is what will be modded. You can get to your root directory by right-clicking Among Us in Steam -> Properties -> Local Files -> Browse. RECOMMENDED STEP TO KEEP SEPARATE COPIES IN CASE YOUR MODDED GAME BREAKS & TO AVOID AN AUTO-UPDATE BREAKING THE MOD.

Extract the contents TownOfImpostors.zip into the copied folder you created.

Ensure the copied directory that is being modded now contains at least the following:


.
├── Among Us_Data
├── BepInEx <---
├── mono <---
├── Among Us.exe
├── baselib.dll
├── doorstop_config.ini <---
├── GameAssembly.dll
├── steam_appid.txt <---
├── UnityCrashHandler32.exe
├── UnityPlayer.dll
└── winhttp.dll <---

Still unsure? Click this for an image of what it should look like if you have hidden file name extensions
Make sure to launch the game via the Among Us.exe from this directory. Please note that the first time launching the game with this mod may take a while - give it one minute before worrying that nothing is appearing.
# Verifying installation success

Launching the game via Among Us.exe
In the top-left corner of the main menu, below the Among Us version, you should see Town Of Impostors vX.X.X Mod by AJMix to indicate the mod is running and has been successfully installed.
If you don't see this message or have any other issues, please take a look at the troubleshooting section.

# Version Mismatch Checker:

Starting from v1.8.1 onwards, there is now a version mismatch checker that'll make sure that all users in the lobby are using the same game version. If a red message appears on the top right stating "Warning: Player Version Mismatch", then there's a potential that someone in the lobby is not using the correct version.
Sometimes this warning message can appear when something strange occurs, even if all users in the lobby are using the same version. If you're 100% sure all users in the lobby are using the same mod version, simply have players rejoin the lobby.
Before raising an issue, please double check that you have accurately followed the installation instructions and you are not using any mod manager or other mods.

Starting from v1.5.0 onwards, there is a new reset custom settings button in the lobby. Please use it if your settings are bugged. Settings can bug when you update from version to version, it's best practice to reset settings.

Starting from v1.6.0 onwards, this mod should now be compatible with Mod Manager by MatuxGG. Please note that using the Mod Manager to install the mod still does not guarantee that the mod will work as intended.

### Saving and Loading
Starting from v1.8.1, you can now save and load your settings. This is to help lower the issue of settings completely messing up between versions. You should find a new TownOfImpostorsSettings.txt in the Among Us folder where the mod is installed. This can also be passed onto others so they can play with your settings!

From v1.8.6 onwards, there are now 5 Save & Load slots. You can use these to save multiple settings. You will be able to find them as TownOfImpostorsSettings_1.txt, TownOfImpostorsSettings_2.txt etc. inside of the TownOfImpostors_Data folder. Please launch the game or create the folder yourself if you don't see it. These settings can be passed onto others. If you were using the previous TownOfImpostorsSettings.txt before, please move this into the folder and rename it to TownOfImpostorsSettings_1.txt.

### Uninstalling the Mod
If you copied the Among Us folder as instructed by the Installation Steps, simply delete the copied folder.
If you did not, and you unzipped the mod into your main Among Us folder, then you have to delete the following folders & files:
BepInEx folder, mono folder, doorstop_config.ini, winhttp.dll
Releases and Compatibility

| Version:  |Release:   |
| ------------ | ---------|
|v2021.4.12s & v2021.4.14s| v1.8.6.1 |
v2021.4.12s & v2021.4.14s	| v1.8.6 |	
v2021.4.12s & v2021.4.14s	| v1.8.2.1 |	
v2021.3.31.3s	| v1.8.1 |	
v2021.3.31.3s	| v1.7.0 |	
v2021.3.5s	| v1.6.1 |	
v2021.3.5s	| v1.6.0 |	
v2021.3.5s	| v1.5.0 |	
v2021.3.5s	| v1.4.0 |	
v2021.3.5s	| v1.3.0 |	
v2020.12.9s	| v1.2.0 |	
v2020.12.9s	| v1.1.0 |
v2020.12.9s	| v1.0. |

Changelog
## Updating the Mod
It is recommended to keep separate folders for each version of Town Of Impostors instead of overwriting. Even if the Among Us version between them is the same and it appears that the bundled files are the same in each release. But if you're intent updating an existing version of the mod with a new version that is compatible to that version of Among Us:

Please ensure you extract and overwrite all that has been asked. Do not pick and mix, or extract only the TownOfImpostors.dll for updating. Each release was crafted for the BepInEx it is bundled with, so there will be errors if the wrong version of BepInEx is used.

Inside your \Among Us Modded\BepInEx\, please delete the \cache\ folder.

You may have to sign in again to your account. If it does not work inside the modded game, please launch the unmodded version and sign in through there first before returning to the modded game. This is why we recommend copying and working with a copied directory of Among Us that is not auto-updated by Steam but also a backup for any issues involving modding.

In the lobby, please click Reset Settings on the bottom left when playing a new version of Town Of Impostors. See Known Issues for why. If you're running v1.8.1 or higher, you may use the Save Settings before the update, then Load Settings after the update to restore your Town Of Impostors configuration.

Now hope all is good! If there are errors, you can always resort to a fresh installation of the mod with another copy of the unmodded Among Us folder!

Curseforge
You can download the mod on Curseforge here.
Custom Hats
Only for versions v1.7.1 onwards

## How do I add my own Custom Hat?
Download the template used to make the Custom Hat for Town Of Impostors (Big Thanks to Con No 1 for the template):

Download .psd template here
Download .png template here
Draw your hat on the template and save in PNG format, with a unique name (make sure to also hide the crewmate and shadow). Preserve the resolution.

IMPORTANT: Please follow this naming convention <HatName>_<Credits>_<Modifiers> for your PNG. See below for list of modifiers. If you want spaces in your names, use - to represent spaces. For example, Bouncy-Hat will be processed into Bouncy Hat inside the game.

Example Names: Wing_Spaced-AJMix_back.png, Bouncy-Hat_AJMix_bounce.png, BouncyWings_AJMix_back_bounce.png, Simple-Hat_AJMix.png, Advanced-Hat_AJMix_bounce_anycolor_-1.1f_+2.3f.png

Place the custom hat png into the TownOfImpostors_CustomHats which can be found inside of the Among Us directory you have the mod installed (launch the game once and start a lobby with the mod or create the folder yourself if it does not exist)

Your custom hat should now appear in the hats tab locally. If you want everyone to see the same thing make sure everyone has the same hats in the custom hats folder.

Modifiers
All hat modifiers are case sensitive!

_back

If you want your hat to be behind the crewmate (i.e. wings).

_bounce

If you want it to bounce while the crewmate walks.

_anycolor

From v1.8.2 onwards, you'll be able to also add this as an additional modifier to have your hat match the colour of your crewmate. You'll need to use Red (Hex: FF0000) for the base colour, and Blue (Hex: 0000FF) for the shading. See example of how this is done here:

ExampleByDark

Advanced Modifiers
All hat modifiers are case sensitive!

_0.0f_0.0f

From v1.8.6 onwards, you can now add X and Y offsets to the name to position the hat more accurately in the menu i.e. Simple-Hat_AJMix_-0.5f_+0.3f. You need to specify both an X and a Y offset. Placing a + or - in front will indicate whether it should be positive or negative. Placing no symbols will default it to positive. The offsets must follow the exact example as shown, with a decimal number followed by an "f".

Want to add your hat as part of the mod so everyone can use it?
Simply follow the same steps above to create a Custom Hat, please join the discord server and post your hat in the custom hat channel there so it can be ready to add in the next release. Please also follow the naming convention so I know the hat name, credits and whether you'd like it to be added to the back of the crewmate and whether you'd like it to bounce.
The Hat Name and Credits will be grabbed from the file name, as long as you have followed the naming convention. When someone wears your hat, credits will appear underneath the mod credits! (i.e. AJ Scarf by AJMix, Dark Scarf by Darkbrussel)
I'll try my best to get your Custom Hat into the next release of Town Of Impostors!
How about the hat angles for animations such as the ladder climb in Airship?
That currently won't be supported yet for custom hats. But, I plan to add support for those in a future version!

Where can I download more custom hats from the community?
Here: https://drive.google.com/drive/u/2/folders/1urae5ivZ3qkXCXAm2VHeR6j9bLWEDoyS

Custom Colors
From v1.8.6 onwards, you will be able to add your own custom colors.

Add your custom colors to the file TownOfImpostors_CustomColors.txt which can be found in the TownOfImpostors_Data folder. Please launch the game and create a lobby once if you don't see the folder or file, or manually create them yourselves.

Follow this example to add a color:

255,255,255,255 220,220,220,255 Pure_White PWH

Each part of the entry stands for this:

MainColor ShadingColor LongName ShortName

For the colors the format is: R,G,B,A (values between 0-255)

Separate each part with a space, use _ to represent spaces in the long name.

In multiplayer, everyone must have the same TownOfImpostors_CustomColors.txt to see and use the same custom colors!

Streamer Mode
From v1.7.1 onwards, there is a new streamer mode that can be toggled on.

This makes it easier for streamers as they won't have to manually hide the code anymore on stream, it will be hidden automatically.

How do I get the room code?
When you create a room, the room code will be copied to your clipboard. Simply paste it somewhere and pass it onto others.

If you accidentally copied something else before pasting the room code somewhere, you can get your copy/clipboard history by using Windows Key + V. Or you can just make another room.

Roles, Abilities, Modifiers & Custom Options
Keybindings
From 1.6.0 onwards, you can now use keys 1, 2, 3, 4, Z, X to activate abilities.

Gamemodes
Map Randomise Mode: When toggled on, map will be randomised upon starting the game
General Custom Options
Custom Role Eject Confirmation: Enables ejects to show the special role of the player being ejected, assuming "Confirm Ejects" option is on
Same Roles Know Each Other: Allows players of the same role to see each other (via highlighted names)
Comms Sabotage Causes Anonymity: Improves the Comms Sabotage to turn everyone anonymous
Ghosts Use Crewmate Vision: Ghosts will no longer have ghost vision (where they can see everything), they will now instead use normal crewmate vision. Impostors are unaffected. This option is recommended if there is a Doctor in the game
Impostors Can Kill Each Other: Allows Impostors to target and kill each other
Game Continues With Arsonist: Toggles whether the game should continue as long as Arsonist is alive
Disable Body Report: Toggles on/off body reporting (to get a different kind of gameplay)
Dead Player See All Roles: Toggles whether dead players should see all roles (after a meeting only)
Impostors Do Not Know Each Other: Toggles whether Impostors know each other
Impostors Can Kill Inside Vents: Toggles whether Impostors can kill any other players inside of vents (if they are in the vent too)
Vents Hold Multiple Bodies: Toggles whether multiple bodies can be disposed in one vent (default is 1 body maximum if toggled off)
Can Vent With Body: Toggle whether players can vent with bodies
Crewmate Team
The special roles in the Crewmate Team. The goal of the Crewmate Team is to combine their abilities and knowledge to find the Impostors. The Crewmate Team will win if all Impostors are ejected or killed.

Sheriff
The Sheriff is a role that has the ability to kill Impostors. However, if they attempt to kill a fellow crewmate, they will lose their own life instead as a punishment.

Custom Options
Doctor
The Doctor is a role that has the ability to revive dead players. However, this means they are also able to revive Impostors that have been killed by the Sheriff.

Custom Options
Agent
The Agent is a powerful role that has abilities allowing them to access map intel from anywhere. This includes the admin table map, security cameras, door logs and vitals if any are accessible. This gives them much more information on what is going on around the map, but they shouldn't neglect their tasks either.

Custom Options
Detective
The Detective is a role that can see footprints and get extra information when reporting bodies (They will get a body report in chat only they can see, which shows time of death and if the body was moved or not). They should use this ability to track down Impostors, but they should also be careful not to frame the wrong person.

Custom Options
Plumber
The Plumber is a role that can use vents to travel around. They can also stay in vents to observe the room. But they should be careful not to be suspected as the Impostor or noticed by the Impostor.

Custom Options
Informant
The Informant is a role that can see other roles after they are finished with ALL their tasks. They will be "Informed" after finishing tasks, but should also be careful of Impostors that are notified about them. The Informant can only be informed or revealed after completing at least one task.

NOTE: Comms Anonymous Sabotage (if toggled on) will prevent Informant from seeing roles, even in meetings. This is the counterplay to Informant.

Custom Options
Trickster
The Trickster is a role that can create a decoy to trick the Impostor. If the Impostor kills the decoy, they will go into kill cooldown which will slow them down. However, the Sheriff is also able to kill decoys. The Trickster may also swap positions with their decoys to avoid danger or cover more ground quicker.

Custom Options
Operative
The Operative is a role that can place down gadgets that allow them to track other players. A sticky tracker can be placed down that'll stick to other players and reveal them for the duration. An AOE sensor can be placed down to reveal players in an area (revealed players will be anonymous) for a duration. All revealed players will be shown on the map. The Operative gadgets are only visible to the Operative.

Custom Options
Mayor
The Mayor is a role that gets additional votes they can use to influence the results of a meeting. They are able to store votes each meeting and can add votes to any player in the meeting (or skip vote) at any time, as long as they have not locked in their final vote. They should use this if they want to force someone to be voted out or force a skip vote. But they should be careful not to reveal themselves too early.

Custom Options
Other Teams
Jester
The Jester is a role with no abilities and no tasks to do (they get fake tasks like Impostors). They are in their own team, and their goal is to get themselves ejected from the ship and make sure not to get killed by the Impostors. They will win instantly if ejected from the ship. However, if they are killed, they will have no way to win and essentially lose. The have extra abilities to help them act suspicious, such as dragging bodies, leaving bloody footprints and using vents.

Custom Options
Arsonist
The Arsonist is a role that aims to douse everyone alive and igniting them all to win alone. They need to do this before the Crewmate Team wins by finding all the Impostors. They have no tasks (they get fake tasks like Impostors), but should be careful not to be suspected as they have to say close for the duration of time they are dousing. They should also be careful not to be killed by the Impostor.

Custom Options
Impostor
The Impostor has additional abilities they can make use of:

Drag & Drop Bodies: Impostors can drag around and drop dead bodies to reposition them. They may also drag bodies through vents.
Dispose Bodies: Impostors can dispose a body they are dragging if they are close to a vent or inside the vents. But when bodies are disposed, a bloodstain is left behind on the vent to give crewmates a clue.
Retrieve Bodies: Impostors can retrieve a disposed body from a vent
Disguise: Impostors can disguise as another player for set duration. They must first sample the DNA of a player by being nearby the player.
Decoy: Impostors can drop a decoy, much like the Trickster, to confuse players and trick the Sheriff. They can also drop a decoy of another player by first Disguising as that player
Swap: Impostors can swap positions with their decoy, much like the Trickster, to avoid danger or cover more ground quicker
Custom Options
If separate Impostor Roles are enabled:
Tier 1 Impostors:
Dragger has the drag/drop & dispose body abilities
Morphling has the sample & disguise abilities
Deceiver has the decoy & swap abilities
Tier 2 Impostors:
Hitman has the combined abilities of Dragger and Morphling
Joker has the combined abilities of Morphling and Deceiver
Any Impostor without a special Impostor role will be a normal vanilla Impostor

Impostor Role abilities are configured with the same options used to configure the normal Impostor

Modifiers
Lovers
This activates the Lovers modifier. Two players are selected as random to be lovers (if applicable). Impostors can also be selected as Lovers. Jesters & Arsonists cannot be selected as Lovers. There can not be more than 1 Impostor Lover.

Lovers can still get their own special roles, and can still win as normal with their respective teams.

However, the Lovers can achieve a special "Lovers Win". The goal of the Lovers is to stay alive together and win together at the end. Lovers will achieve the special Lovers Win if they are both among the last 3 players standing. The only exception to this is if the custom option Game Continues With Arsonist is toggled on and the Arsonist is among the last 3. The game will continue as long as the Arsonist is alive.

Lovers are given the ability to chat with each other via a special Lovers Chat in-between meetings.

Custom Options
How does role assignment work?
The role selection works as follows: For each role, it will attempt to add that to the selection pool X number of times, where X is the maximum count. The chance of the role being added to the selection pool each time is based on the percentage chance set in the custom options for the specified role.

Once the selection pool is filled, the roles in there will then be randomly assigned to Crewmates (who are not already Impostors and don't already have a special role). As long as there are roles in the pool to assign and Crewmates to assign them to, they will be assigned out. If there are no more roles to be assigned out, the remaining players will just stay as normal Crewmates.

Example: Sheriffs - # Max Count: 3 | % Chance: 50

This means that the role selection will try to put 3 sheriffs into the pool, at 50% chance each time. So the pool can end up with 0, 1, 2 or even the maximum of 3 Sheriffs.

FAQ
Can you play Proximity Chat (Crewlink) with it?
Yes, Crewlink supports Among Us Modifications

Can this mod work with other mods?
I cannot guarantee that this mod will work with other mods. There will likely be conflicts. You will have to test yourself.

Do my friends need to install the mod to play it together?
Yes. Every player in the lobby must have the mod installed. Please don't use and play mods in unorganised public lobbies.

Can you get banned for playing on public servers?
At the current state of the game there is no perma ban system, though this may change depending on the stance of the Among Us developers. The mod is designed in a way that it does not send prohibited server requests. In a public lobby with randoms, with only you having the mod installed, you would either be kicked for strange behaviour or have a desync between you and other users that do not have the same mods, or both. In short, as long as this mod is played among friends in your own private lobby, you're safe.

If you are really worried, I recommend checking out Impostor to start your own custom, private server. (You may have to disable their AntiCheat implementation for it to work with mods like this). Still, a disclaimer that you use this mod at your own risk and I am not responsible for any account suspensions that may occur from the use of this mod.

How can I join servers of a custom region?
This functionality has been removed from 1.6.0 onwards. Please look into using Unify

Can this mod work with controllers?
This mod was not made to be compatible with controllers in mind; it was intended to be played with keyboard and mouse.

Troubleshooting
The mod isn't installed or game doesn't launch
Please make sure you're using the latest version of the mod and the correct version of Among Us for it
Please make sure you're using Windows, this mod is not compatible on Android, Mac or any other OS/devices
Please make sure you're using this with the Steam version of Among Us; this is not compatible with the itch.io version unfortunately
Please make sure you're not loading other mods along with this one
Make sure you have followed all the installation steps, especially launching the game via the Among Us.exe file
Try uninstalling the mod (see uninstalling the mod in the Installation Steps) and following the installation steps again
If you're using a Mod Manager to install the mod, it is not guaranteed to work
You might be missing some cpp libs (software libraries used by the mod); please install Visual C++ redistributable packages x86 & x64
The mod still doesn't work or found a bug?
You can raise an issue within GitHub documenting your issue. You will need to be logged into GitHub to do this. For any bugs, take a quick check if your bug has already been listed under the below Known Issues or if it has already been reported. Please give as much detail as possible regarding the issue, including steps to reproduce it if possible. If it exists, please also attach your LogOutput.log, generated in the Among Us\BepInEx\ folder.

Known Issues
When updating from version to version, settings can bug and cause unintended effects. This is due to how new custom settings are being added in each update. If you are getting strange bugs occurring with the settings, try manually settings everything again (to overwrite the saved settings on your computer) by manually toggling options on and off, setting timers and settings counts. You can also do a hard reset by running vanilla among us and creating a lobby, then reopening among us with this mod. In v1.5.0 onwards, there is a new reset settings button the host can make use of to do a hard reset on all custom settings to reset everything to default values

Disconnections in the middle of the game can cause bugs to occur, and the only way to fix them would be starting a new game or restarting the game. This mod was made with the assumption that no one would disconnect as disconnections are a whole other edgecase to fix. Future updates will hopefully fix this, but for now, just start another game or restart the client if a disconnection causes your game to bug


