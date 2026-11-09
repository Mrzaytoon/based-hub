# BASED Hub

A script hub for Roblox: one window, a set of tools that works in any game, and room for
per-game modules.

## Run it

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mrzaytoon/based-hub/main/loader.lua"))()
```

The first run downloads the hub, the fonts, icons and sounds it uses, and its films (the intros,
and the one on the Home tab) into your executor's workspace, and shows how far along it is: about
520 MB on a 1080p or larger screen, 220 MB on a smaller one, nearly all of it the films (the
intro you start on comes first). After that there is no download and no download screen; it starts
straight away and only fetches what has changed, a new film included. With no network it starts
the build you already have.

The intro is the BASED lotion ad (11 seconds). **Space** skips it, and Settings › Intro picks
another (the BASED brand film, Neverlose vs BASED, Cinematic, Shuffle), a quick one, or none.
The first time, you then pick which interface to use: **BASED** (glass and a sidebar),
**Novoline** (a dock at the bottom, a panel that rises from it) or **Unnamed** (compact and
classic). Settings › Menu style changes it any time.

| Key | Does |
| --- | --- |
| **V** | opens and closes the hub |
| **H** | switches flight on and off |

Flight starts switched on: hold **Space** on the ground to charge, let go to launch. Every key
can be changed in the hub (Keys tab, or right-click a toggle).

## What is in it

- **Combat**: aim assist with its own field of view, smoothing, lead and target rules; a triggerbot.
- **Visuals**: player ESP (boxes, names, health, distance, skeletons, off-screen arrows) out to
  any range, locked on the body at any speed (deep in the void too) and never switching itself off, with looks of its own (Clean, Pro,
  Neon, Minimal, Classic), a font and boxes that fade out; a crosshair; lighting, an ambient colour,
  exposure, a fog colour, no shadows, and a plain world for more frames.
- **Movement**: animated flight from a charged launch up through the sound barrier, speed, jump,
  noclip, click teleport, anti trip, no player collisions (nobody can push or fling you), and a void
  that cannot kill you.
- **Players**: watch, teleport to, and mark players as friends, targets or hidden.
- **Server**: rejoin, hop, FPS cap.
- **Music**: search SoundCloud and Audius, play your own files or a link; queue, likes, playlists,
  history, sound shaping. Lyrics in time, word by word; a player on screen (tap the cover: big or
  small) in the colours of each cover, and an island at the top with the line being sung. Skip to any
  part and it plays from exactly there. **Mute the game**: only the music and the menu are heard (or
  turn the game down to any level). **Music on this PC**: see and control Spotify, Apple Music or a
  browser from the game (Music › Set up, then Win+R, paste, Enter).
- **You**: headless, a Korblox leg, a body material, a body colour or a rainbow, see-through, hats and
  clothes off, a trail, a glow outline, an aura, footstep effects; picture looks (Cinematic, Warm, Cold,
  Noir, Vapor, Vivid), bloom, colour grade, sun rays, blur, motion blur and depth of field. Only you see
  them.
- **Da Hood**: a ragebot (the Destroyer preset does it all at once: head shots, a trap at the armour
  pads, and a sky sniper that hits a bot hiding in the sky where it goes next; and Press, which goes
  after a bot hiding in the void at the spot it keeps coming back to, however seldom, or round your
  own trail when it follows you, and backs off the moment it is hurt; a bot that comes out onto you is
  knocked as it arrives, one buying from under the floor is shot from beside it, and one whose double tap
  hits you is struck back at before its second shot lands; with a bot about that hunts you, trips to the
  shop wait until it is down; a ring lure for a bot that follows you from a set way off; a view locked
  on its target however fast it goes, into the void too, and your own body lit while it hunts so you always see where you
  are; every resolver number on a Resolver tab; and Beat BASED bots, traps for a bot that runs this hub
  itself: its own pounce, its lures and your spawn shield turned against it; Anti rep root, which finds a
  body glued to yours and shoots it point-blank; Unmask, for one drawn away from where its shots come
  from; and a resolver that learns how far ahead to aim, off as it ships), a Sigil on your body (styles,
  symbols and palettes to pick) and damage numbers that tick up where you hit, supplies, bounty
  hunting, Bring, a combat tab (one tap with shotguns, bullet manipulation that lands your shots on
  whoever the aim help has, through walls, Double tap, a triggerbot, sticky aim with a lasso, a shot
  guard that never wastes a bullet, rapid fire at the server's full rate with fake tracers between
  (the AUG at 20 a second), and fake spam that sends real bullets when you are in reach), Speed
  (carried along as you walk, up to 400 studs a second), a target strafe that hops round them while you
  see a clone stand still, Desync (your body gone, you play its clone), an auto block nobody sees, a
  skin changer for every gun and the knife with each skin's own shot, swing and equip sounds, cash,
  scores for every player, and more, in tabs of their own.
- **Keys** and **Settings**: every key on a keyboard you can click, themes, scale, configs, and share
  codes that give someone else your whole setup.

Rest the mouse on any control and it says what it does.

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
