# Disney-Dreamlight-Valley-VR
VR Mod for Disney Dreamlight Valley (tested offline)

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />


DISNEY DREAMLIGHT VALLEY VR  -  VR mod (Unity 6, IL2CPP, URP, BepInEx 6)
=======================================================================

VIRTUAL GAMEPAD (needed for title screen / pause / menus / dialogue with the VR controllers)
  1. Download the ViGEmBus installer from https://github.com/nefarius/ViGEmBus/releases
     (latest release, file ViGEmBus_..._x64_x86_arm64.exe) and run it. Reboot if it asks.
  2. Start the game as usual.
  Switch it off with [Input] VirtualGamepad = false. ViGEmClient.dll (MIT licence, Nefarius) is included.

INSTALL
1. You already have BepInEx 6 (be.788) in the game folder - good.
2. Unzip this into the game folder, 
3. Start your OpenXR runtime (SteamVR / Oculus / Virtual Desktop), put the headset on, start the game.

THE VIEWS
* Normal (default): you are where the game's camera is, looking at your avatar in 3D. The right stick
  turns the game's camera as usual (your view turns with it).
* First person: you are your avatar (view at its head). The left stick walks where you look, the
  right stick snap-turns. Switch: hold the right grip + right stick click for 1.7 s (or in the settings menu).
* Recentre: click both sticks together.

CONTROLS (the VR controllers are an Xbox pad, button for button)
-
Start (menu): left grip + Y.

Back (quest): left grip + X.
  
  Left stick = left stick (walk)
  
  Right stick = right stick (camera)
  
   D-pad = hold the left grip + push the right stick that way
   
  In menus: right stick = d-pad too, the left stick moves one item at a time.
  
The game is told a gamepad is in use, so it shows its gamepad controls and button pictures.

Every button can be changed in BepInEx\config\ddv.vr.cfg [Controls] (live: save while playing).

B and X is swap can change in VR SETTINGS MENU 

VR SETTINGS MENU: hold Y + click the left stick for 1.7 s.

HUD / MENUS are shown on a floating screen in front of you ([UI] Distance, Width, HeightOffset).
