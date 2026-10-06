# Paintball Wars

A browser prototype inspired by boomerangwar.io, using paintball guns instead of boomerangs.

Open `index.html` in a browser. Nothing needs to be installed.

**Play online:** https://johnjoo1.github.io/jesse_game/ (once GitHub Pages is turned on, see below)

## Power-ups

Half of all splats drop a power-up where the player went down. Walk over it to grab it.
It lasts until you get splatted, and bots grab them too. Unclaimed drops fade after 20 seconds.

| Power-up | Chance | What it does |
|---|---|---|
| ♥ Extra Heart | 30% | +1 max health (up to +3) and a full heal |
| ⚡ Rapid Fire | 20% | Shoot twice as fast |
| » Speed Boots | 15% | Run 30% faster |
| ▤ Big Hopper | 15% | 24 paintballs and faster reloads |
| ⁂ Triple Shot | 10% | Every shot fires 3 paintballs |
| ◯ Bubble Shield | 7% | Blocks the next 3 hits |
| ★ Golden Gun | 3% | Every hit counts double |

Chances are per drop. With half of splats dropping something, a Golden Gun turns up about once every 67 splats.

## Playing with friends

1. One person taps **Host a game**. A 4-letter room code shows at the top of their screen.
2. Friends open the same page, type the code and tap **Join**.
3. Everyone shares one arena with the bots. Bots are removed as more friends join (up to 8 players).

This is peer-to-peer: the host's device runs the game and friends connect straight to it,
using the free PeerJS service to find each other. Nobody needs an account. If the host
leaves, the game ends for everyone. Some school or work networks block these direct
connections. Multiplayer doesn't work in the Claude artifact version, so use the GitHub Pages link.

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
- Computer: WASD/arrows move · mouse aim · click shoot · R reload · Shift sprint
- Phone/tablet: left thumb moves, right thumb aims and shoots (with a little aim assist), ⟳ reloads, » toggles sprint

The game switches controls based on what you use: touching the screen shows the joysticks, and using a mouse or keyboard hides them. On small screens the view zooms out and the on-screen info gets smaller.

**Features**
- Top-down arena with 9 bots and a kill leaderboard
- Obstacles: walls, bunkers, crates, and rocks block movement and paintballs. You can hide in bushes.
- You can take 5 hits and bots can take 3. You respawn after 3 seconds with a short spawn shield.
- When you splat someone you get a SPLAT! pop-up, a shockwave, screen shake, a banner and a sound. Your hits show a marker on the crosshair.
- 12-ball magazine with a reload, plus a sprint stamina bar
- Paint splats stay on the ground, along with a kill feed and a minimap
