---
title: Mew - General
permalink: /mew/general.html
---

# General
This tab contains all the miscellaneous settings.

## Mew Key
***Key*** : Put here the key. Make sure to not have a space at the end.

## Waiting Aetheryte :
Enable/Disable the use of the waiting Aetheryte (list below).

### Aetheryte list :
Where do you want it to wait.

### Use Aetheryte to go out :
Enable/Disable the use of Idyllshire/Rhalgr's Reach Aetheryte to go in the Hinterlands/The Fringes/The Peaks, if disable it'll move to the exit by its own.

### Use House Codechunk:
Enable/Disable the use of custom teleport codechunck, usefull if you have a private house and an apartment/friend's house in the same zone.
To get the three parameters (Zone ID, Aetheryte Id and Index) you need to run this code below using RebornConsole (in your plugins list) : 
```csharp
foreach(WorldManager.TeleportLocation location in WorldManager.AvailableLocations){
Log("Name : {0} | Zone ID : {1} | Aetheryte ID : {2} | Index : {3}",location.Name, location.ZoneId,location.AetheryteId, WorldManager.AvailableLocations.IndexOf(location));
}```

## Gear Set
### Miner :
You Miner gear set number.

### Botanist :
You Botanist gear set number.

### Fisher :
You Fisher gear set number.

### Combatant :
You Combatant gear set number.

## Items Settings

### Discover unknows:
If Enable it'll override the rotation if there is an unknow material when you're gathering any node.

### Food List :
Wich Food you want to use, if you want to use one.

### Manual List :
Wich Manual you want to use, if you want to use one.

### Map List :
Wich Map you want Mew to gather if available.

## Buttons
### Import Settings :
Use this button to import previous settings (JSON file), you can also import settings from others but make sure to check your gear set.

### Export Settings :
Use this button to export your current settings (JSON file).

### Start :
Use this button to start Mew, it'll generate a xml profile based on what's set in the UI, switch to orderbot, (try to) load the profile and start it.

If you have any issue when Starting Mew, please send me the log in Discord. Most of the time, if it doesn't start it's because you don't have my own ExBuddy's fork (properly) installed.

### Reset Mew :
Use this button to reset all Mew's settings but the ones in the General Tab.

### Reset General :
Use this button to reset the General tab's settings.

[Return](/mew.html)