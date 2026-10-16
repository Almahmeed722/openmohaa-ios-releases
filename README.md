# OpenMoHAA for iPhone (unofficial)

An iOS port of [OpenMoHAA](https://github.com/openmoh/openmohaa) with touch controls
(stick, fire/aim/jump/crouch/reload/use/weapon buttons, chat, scoreboard, layout editor).
Free software under the GPL; the full source for this build is attached to each release
(`openmohaa-ios-source.zip`).

**The game data is not included.** You need your own copy of Medal of Honor: Allied Assault
(and optionally Spearhead / Breakthrough). Never share game files.

## Install (free, no PC needed for the app itself)

1. Install **AltStore** or **SideStore** on your iPhone.
2. In the app, add this source: `https://raw.githubusercontent.com/Almahmeed722/openmohaa-ios-releases/main/altstore.json`
3. Open the source and tap **Install** on OpenMoHAA (it signs with your own Apple ID; free
   accounts need a refresh every 7 days, which the app does automatically on Wi-Fi).

Or download `OpenMoHAA.ipa` from the Releases page and sideload it with AltStore, SideStore,
iloader or Sideloadly.

## Copy your game data
Connect the iPhone to a PC and copy your `main`, `mainta` and `maintt` folders into the app's
**Documents** folder (Files app, iTunes/Finder file sharing, or `pymobiledevice3`).
The sound/video are large; copying takes a while.

For the Spearhead / Breakthrough weapons (rifle bash, scopes) create `Documents/launch_args.txt`
containing `+set com_target_game 2`.

## Server map: Destroyed Village 2
The community server runs the custom map **Destroyed_Village_2** (by DangerousDougy, redistributable
with its readme). Download `zzzzzz_destroyed_village_2.zip` from the Releases page, unzip it, and copy
`zzzzzz_destroyed_Village_2.pk3` into the app's `Documents/main` folder, then fully close and reopen the
app. Without this file you cannot join the server.

To join: Multiplayer -> Join Internet Game -> Connect to IP Address, and enter the server address
given by the server host.
