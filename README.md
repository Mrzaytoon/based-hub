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
The interface is **BASED**: glass and a sidebar. A second one, **Unnamed** (the dark two-column
menu), has the same tabs and settings: Settings › Menu style, or the menu at the window's top.

| Key | Does |
| --- | --- |
| **V** | opens and closes the hub |
| **H** | switches flight on and off |

Flight starts switched on: hold **Space** on the ground to charge, let go to launch. Every key
can be changed in the hub (Keys tab, or right-click a toggle).

## What is in it

- **Combat**: aim assist with its own field of view, smoothing, lead and target rules; a triggerbot.
- **Visuals**: player ESP (boxes, names, health, distance, skeletons, off-screen arrows) out to
  any range, locked on the body at any speed (deep in the void too) and never switching itself off. It is
  drawn the Unnamed way as it comes (a thin box with a dark edge, gradients across the box, the fill and the
  words, a health bar that eases, flags, chams, a body's own look changed) or the hub's own way, with looks
  in one click (Unnamed, Unnamed glow, Clean, Pro, Neon, Minimal, Classic); a box never blows up when a body
  is knocked or broken apart. A crosshair; lighting, an atmosphere, an ambient colour, exposure, a fog
  colour, no shadows, and a plain world for more frames.
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
  skin changer for every gun and the knife with each skin's own animations and its shot, swing and equip sounds (a knife is
  held the way the game holds it, and the butterfly knives flip open every time you pull them out), a
  whitelist nothing of yours can hurt (fists, knife, throwables, blasts and stomps are all held back),
  Noclip, anti stomp and an auto stomp that keeps stomping, cash, scores for every player, and more, in
  tabs of their own.
- **GloryBound**: an auto farm, in tabs of its own. It lifts at a free barbell at the pace the game
  itself counts, is reborn at the shrine when Strength is capped, queues Survival runs (with a team or
  alone) and fights them (swings at whatever is in reach, shield up as each blow lands, out of the arrow
  storm, a boon picked by what you want from it), opens the chests it wins, wears the better blade and
  piece, claims the daily gift, quests and free spins, and comes back by itself after every match. In a
  fight it answers only the blows aimed at it, keeps each kit at its best distance, dashes out of a boss's
  leap the moment its landing is set (and keeps a dash for it while a champion is out, away from the
  champion's side, then waits outside until it lands), keeps its spear out of a champion's reach, steps out of a
  breath while it burns, never dodges into the wall, puts its own life before the round when it is low,
  and walks round anything in its way; it pushes the chariot while it
  fights off the mobs, grabs the treasure purses before the thieves, holds the Emperor's eye, goes for its
  rival and the champion, skips the breaks and the boss's entrance, answers the nightmare gate after round 60
  for you (Descend, Claim, or leave it to you), retries straight into the next run, and
  stays minimised after every teleport. One button switches the whole farm on and one switches it off;
  nothing that spends cash, skill points or Robux is ever switched on for you.
- **Attack on Titan Revolution**: an auto farm, in four tabs of its own (Farm, Blade, Titans, Missions).
  It puts you behind each titan at once and cuts the nape with the game's own swing at full damage: a
  whole Easy mission of 18 titans was cleared in 17 seconds, hands off. It never works the same spot
  twice (a cut that is not heard comes from another side next, on another titan first), keeps the blade
  supplied (a new set before the last segment, a gas tank when the sets are gone), breaks out of grabs
  for you, and asks for the next mission when one ends. Every few missions it goes home, buys gear
  upgrades with the gold it earned and takes the hardest mission that unlocked: from a new account it
  went from Easy to Hard by itself in under an hour. Boxes on every nape if you want them, and it starts
  itself again, minimised, after every teleport. It needs an executor with `run_on_actor`. One button
  for the whole farm, one to stop; gold is spent on gear upgrades only, and nothing is ever bought with
  Robux.
- **Blox Fruits**: an auto farm in tabs of its own, a first release. Auto level takes the quest worth
  most from the game's own tables, fights its mobs from above (it never goes down among them), hands
  the quest in and flies to the next island when a better one opens, through the game's own whirlpool
  where there is one: one account went from level 1 to 490, hands off. Stat points by a plan of your
  own, haki kept on, abilities bought as Beli allows, fruits fetched and stored (you choose which ones
  it goes for), chests between fights,
  the Saber quest done from start to end, and an Autopilot that runs all of it with one switch. A watch
  over every job puts a stalled one right by itself. More is built and not yet proven on the live game:
  bosses, raids, the sea, races, the fruit dealers and the trip to the Second Sea. In this game only
  Visuals is kept from the tools above. Every switch is off by default, and nothing is ever bought with
  Robux.
- **Throw Food For Animals**: an auto farm in tabs of its own. Every throw is a perfect one, with none
  of the cinematic, and it trains at your bar in between, choosing which by what the next throw is
  likely to bring and by how close the next area is. A better catch takes the place of your weakest
  animal by itself, and the rest are sold (you say which mutations and rarities to keep). Food, bars
  and the fence are bought cheapest first, food only when it helps where you land, with a reserve if
  you want one. It can aim short at the animals your index is missing, claims the free animal, offline
  earnings and index rewards, wears your best trail, and keeps you in the server past the game's own
  18-minute idle move. One account went from level 13 to 260 in about 80 minutes. Every switch is off
  by default, and nothing is ever bought with Robux.
- **BloxStrike**: an ESP and aim help in tabs of their own. Boxes sit on each body in the frame the game
  draws it, through walls and at any range, red in the open and violet behind cover, with health, armour,
  money, kit and the gun in hand; once the game hides an enemy, a dim box stays where it was last seen;
  arrows point to enemies off screen; an enemy panel and the bomb's timer. A triggerbot that fires the way
  the gun in your hand fires (held for automatics, tapped at the gun's own rate for pistols, snipers and
  shotguns, only within the weapon's range, never with a grenade or the bomb), and an aim assist with an
  FOV circle. Every switch is off by default.
- **Keys** and **Settings**: every key on a keyboard you can click, themes, scale, configs, and share
  codes that give someone else your whole setup exactly as it runs (a code that was cut short or damaged
  in a paste says so).

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
