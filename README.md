# Paintball Wars

A browser prototype inspired by boomerangwar.io, using paintball guns instead of boomerangs.

Open `index.html` in a browser. Nothing needs to be installed.

**Play online:** https://johnjoo1.github.io/jesse_game/ (once GitHub Pages is turned on, see below)

## Power-ups

Half of all splats drop something where the player went down. Walk over it to grab it.
Bots grab them too, and unclaimed drops fade after 20 seconds.

**Boosts** work right away and last until you get splatted:

| Power-up | Chance | What it does |
|---|---|---|
| ♥ Extra Heart | 15% | +1 max health (up to +3) and a full heal |
| ⚡ Rapid Fire | 15% | Shoot twice as fast |
| » Speed Boots | 12% | Run 30% faster |
| ▤ Big Hopper | 12% | 24 paintballs and faster reloads |
| ⁂ Triple Shot | 9% | Every shot fires 3 paintballs |
| ★ Golden Gun | 3% | Every hit counts double |

**Defenses** go into one of 3 carry slots, shown as numbered boxes above your ammo. Press **1**, **2** or **3**
to place that one, or **E** / right-click to place the highlighted one (move the highlight with the mouse
wheel or Tab). On a phone, each carried defense gets its own button. With all 3 slots full, defenses stay on
the ground for someone else. It stays where you put it. Defenses that can be shot down have no timer:
they last until enemies destroy them (bots go after enemy turrets). Each player can have up to 3 of
these standing; placing a 4th removes their oldest. The others run on a timer:

| Defense | Chance | What it does |
|---|---|---|
| ▮ Barricade | 12% | A wall across your line of fire. Blocks enemy paint, but yours flies through it. Stays until it takes 8 hits |
| ✚ Heal Station | 9% | Stand in it to heal 1 health every 1.5s. Lasts 20s |
| ◠ Shield Dome | 7% | Enemy paint can't get in; you can shoot out. Lasts 10s |
| ⊕ Sentry Turret | 6% | Shoots enemies within range; its splats count for you. Stays until it takes 5 hits |

Chances are per drop, so a Golden Gun turns up about once every 67 splats.

## Teams

In a multiplayer game, tap **👥 Teams** at the top (or press **T**) to see the other players.
Tap **Team up** next to someone; they get a pop-up to **Accept** (Y) or say **No thanks** (N).

Teammates:
- can't splat each other: their paint passes straight through
- can shoot through each other's barricades, and heal at each other's heal stations
- aren't targeted by each other's turrets, and show as green dots on each other's minimap
- have a green dashed ring and 🤝 by their name

Either player can **Leave team** from the same list. It takes 3 seconds (the ring turns orange)
so nobody can turn on a teammate without warning. You can team up with more than one person;
each pair agrees separately. Bots are never on a team.

## Updates without losing your game

The page checks every 90 seconds whether a newer version is online. If there is one, an
**Update ready** button appears at the top. Tapping it saves the game, reloads with the new
version, and puts everything back: positions, scores, boosts and paint on the ground.

- Playing solo: tap the button whenever you like.
- Hosting: tapping it updates everyone. Friends reload with you and rejoin the same room as the same player.
- Joined a friend's game: the button tells you the host can update everyone.

If a friend and the host end up on different versions, joining says so and asks both to refresh.

## Turning on GitHub Pages

1. Settings → General → Danger Zone → **Change visibility** → make the repo public
   (free GitHub Pages needs a public repo).
2. Settings → **Pages** → Source: **Deploy from a branch** → pick the branch with `index.html`
   and the `/ (root)` folder → **Save**.
3. After a minute or two the page is live at the address shown at the top of the Pages settings.

**Controls**
- Computer: WASD/arrows move · mouse aim · click shoot · R reload · Shift sprint · 1/2/3 or E place a defense · T teams
- Phone/tablet: left thumb moves, right thumb aims and shoots (with a little aim assist), ⟳ reloads, » toggles sprint, a defense's button places it

The game switches controls based on what you use: touching the screen shows the joysticks, and using a mouse or keyboard hides them. On small screens the view zooms out and the on-screen info gets smaller.

**Features**
- Top-down 4800×4800 arena with 16 bots and a kill leaderboard
- Obstacles: walls, bunkers, crates, and rocks block movement and paintballs. You can hide in bushes.
- You can take 5 hits and bots can take 3. You respawn after 3 seconds with a short spawn shield.
- When you splat someone you get a SPLAT! pop-up, a shockwave, screen shake, a banner and a sound. Your hits show a marker on the crosshair.
- 12-ball magazine with a reload, plus a sprint stamina bar
- Paint splats stay on the ground, along with a kill feed and a minimap
