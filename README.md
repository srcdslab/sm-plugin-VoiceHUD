# VoiceHUD
I made this plugin for managing CS:GO servers. In CS:GO a player can only view the first 3 speakers at a time. Additionally it can sometimes be difficult to target them if they have strange names ~or~ you aren't sure who is saying what.

## Features
Displays the most recent mic users in order (last 5)
Also displays their User ID & Steam ID for easy reporting / banning
Prints additional text in console in case you miss it
Hud will display for 15 seconds after the last user stops talking
Individual player toggle that saves using client prefs
Formatted as User ID | In Game Name | Steam ID
Note: The game engine MUST support https://developer.valvesoftware.com/wiki/Game_text, this was recently added to CS:GO
Note: Requires VoiceannounceEX (VoiceHook) & DHooks

Based on / inspired by: Franc1sco's SVoice plugin

![Screenshot](https://i.imgur.com/FRjOEk7.png)

## Commands / Cvars
sm_voicehud ~ Toggle the hud (per player) (use admin overrides to restrict)
sm_voicehud_excludeadmins ~ Set this to "1" to exclude admins from display, "0" to disable

## Changelog:
```
Version 1.0:
Initial Release
sm_voicehud is now public command, use overrides to restrict (1.1)
Added sm_voicehud_excludeadmins convar, see description (1.1)
Undo change 1.2, fixed admin check priority (1.3)
Code cleanup (1.4)
Reworked plugin, removed all timers (optimization) (1.5)
Remove Hud text immediately when you toggle the Hud off (1.6)
Change max lines to 5 instead of 4 as intended (1.6.1)
Muted players will no longer show up or refresh the Hud (1.7)
Muted players will be notified they are muted (1.7)
```

## Download Latest Version
- VoiceannounceEX
- DHooks
