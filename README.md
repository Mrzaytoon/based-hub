# BASED Hub

A script hub for Roblox: one window, a set of tools that works in any game, and room for
per-game modules.

## Run it

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mrzaytoon/based-hub/main/loader.lua"))()
```

The first run downloads the hub, the fonts, icons and sounds it uses, and its two films (the
intro, and the one on the Home tab) into your executor's workspace, and shows how far along it
is: about 159 MB on a 1080p or larger screen, 61 MB on a smaller one, nearly all of it the films.
After that there is no download and no download screen; it starts straight away and only fetches
what has changed. With no network it starts the build you already have.

The intro runs 19 seconds. **Space** skips it, and Settings can make it a quick one or switch it
off.

| Key | Does |
| --- | --- |
| **V** | opens and closes the hub |
| **H** | switches flight on and off |

Flight starts switched on: hold **Space** on the ground to charge, let go to launch. Every key
can be changed in the hub (Keys tab, or right-click a toggle).

## What is in it

- **Combat**: aim assist with its own field of view, smoothing, lead and target rules; a triggerbot.
- **Visuals**: player ESP (boxes, names, health, distance, skeletons, off-screen arrows) out to
  any range, a crosshair, lighting.
- **Movement**: animated flight from a charged launch up through the sound barrier, speed, jump,
  noclip, click teleport, and a void that cannot kill you.
- **Players**: watch, teleport to, and mark players as friends, targets or hidden.
- **Server**: rejoin, hop, FPS cap.
- **Keys** and **Settings**: every key on a keyboard you can click, themes, scale, configs.

## Settings

A fresh install starts with the author's own setup. Anything you change is saved on your
machine, in `BasedHub/prefs.json` and `BasedHub/config/`, and an update never touches those: what
you saved always wins.

## Files

The loader writes `BasedHub.lua` and the folder `BasedHub/` in the executor's workspace, and
nothing else. Delete both to remove it.

It needs an executor that can store files (`writefile`, `readfile`, `getcustomasset`). Without
that the hub still runs, in Roblox's own fonts and without its interface sounds.

## Use at your own risk

Running scripts in Roblox is against its terms of use, and a game can ban an account for it.
Nothing here promises otherwise.

## Credits

Fonts, icons and sounds are other people's work under open licences: see [CREDITS.md](CREDITS.md).
