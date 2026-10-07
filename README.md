# Paintball Wars

A browser game inspired by boomerangwar.io, using paintball guns instead of boomerangs.

**Play online:** https://johnjoo1.github.io/jesse_game/

You can also open `index.html` in a browser. Nothing needs to be installed.

## Controls

- **Computer:** WASD/arrows move · mouse aims · click shoots · R reloads · Shift sprints ·
  1/2/3 or E (or right-click) place a defense · T opens Teams
- **Phone/tablet:** left thumb moves, right thumb aims and shoots (with a little aim assist),
  ⟳ reloads, » toggles sprint, a defense's button places it

The game switches controls based on what you use: touching the screen shows the joysticks, and using
a mouse or keyboard hides them. On small screens the view zooms out and the on-screen info gets smaller.

## The game

- A top-down 4800×4800 arena with bots (16 in a solo game) and a leaderboard
- Walls, bunkers, crates and rocks block movement and paintballs; you can hide in bushes
- You can take 5 hits and bots can take 3. You respawn after 3 seconds with a short spawn shield.
- Splatting someone gives a SPLAT! pop-up, a shockwave, screen shake, a banner and a sound;
  your hits show a marker on the crosshair
- 12-ball hopper with a reload, a sprint stamina bar, paint that stays on the ground, a kill feed and a minimap

## Brain Boost (learning)

Pick **Learning** on the start screen (Off, Math, Spanish or Mix) and an **Age** (7, 8, 9 or 10).
Both are saved on each device, so each kid can have their own. With learning on, getting splatted
shows a question at that age's level, with 3 big answer buttons (or press 1, 2, 3).

- **No rush:** the respawn countdown waits while the question is up.
- **Right answer:** a reward screen shows the prize you won and what it does; tap **Let's go!**
  (or press Enter) to jump back in with it.
- **Wrong answer:** no penalty. The card shows the right answer; tap **OK, back in!** to keep playing.
- **⭐ Challenge questions:** about 1 in 4 questions is one grade harder, on a purple card. Get it
  right to pick a **super prize**: Golden Gun, Sentry Turret, Triple Shot, Shield Dome or Paint Mine. Missing a
  challenge doesn't count against you.
- **3 in a row:** pick your own prize, a boost or a defense.
- **Two misses in a row:** the next few questions are a grade easier.
- Your score shows as 🧠 right/total in the corner, and on the win screen with your ⭐ challenges.

| Level | Math | Spanish |
|---|---|---|
| 7 | Adding within 20, taking away within 20, missing numbers (5 + ? = 9), counting pictures, biggest number | Picture → word (animals, food, things), colors, numbers 0–10, hola / gracias / por favor |
| 8 | Adding and taking away within 100, ×2 ×5 ×10, counting by 2s, 5s, 10s, halves, biggest 3-digit number | Numbers 11–20, days of the week, family, body parts, weather |
| 9 | Times tables, division facts, adding within 1,000, rounding to the nearest ten, ? × 4 = 28 | Counting by tens (veinte, treinta…), months, school things, action words, opposites |
| 10 | 2-digit × 1-digit, dividing 2- and 3-digit numbers, fractions of a number, adding fractions, place value | Everyday phrases (Tengo hambre), clothing, numbers 21–99 |
| 11 (challenges at age 10) | Decimals, fractions and percentages of a number, order of operations, 2-digit × 2-digit | Short sentences, question words (¿Dónde?), yo como / tú comes |

A 🔊 button reads Spanish aloud, and the right word is spoken after each answer.

## Power-ups

Half of all splats drop something where the player went down. Walk over it to grab it.
Bots grab them too, and unclaimed drops fade after 20 seconds.

**Boosts** work right away and last until you get splatted:

| Power-up | Chance | What it does |
|---|---|---|
| ♥ Extra Heart | 13% | +1 max health (up to +3) and a full heal |
| ⚡ Rapid Fire | 13% | Shoot twice as fast |
| » Speed Boots | 11% | Run 30% faster |
| ▤ Big Hopper | 11% | 24 paintballs and faster reloads |
| ⁂ Triple Shot | 8% | Every shot fires 3 paintballs |
| ★ Golden Gun | 3% | Every hit counts double |

**Defenses** go into one of 3 carry slots, shown as numbered boxes above your ammo. Press **1**, **2**
or **3** to place that one, or **E** / right-click to place the highlighted one (move the highlight with
the mouse wheel or Tab). On a phone, each carried defense gets its own button. With all 3 slots full,
defenses stay on the ground for someone else. You lose carried defenses when you're splatted.

A placed defense stays where you put it. Barricades, turrets and mines have no timer: they last until
destroyed or set off (bots go after enemy turrets), and each player can have up to 3 of them standing;
placing a 4th removes their oldest. The others run on a timer.

| Defense | Chance | What it does |
|---|---|---|
| ▮ Barricade | 11% | A wall across your line of fire that anyone can hide behind: it blocks everyone's paint, yours included. Stays until it takes 8 hits |
| ✚ Heal Station | 8% | Heals anyone standing in it (friend, foe or bot) 1 health every 1.5s. Lasts 20s |
| ◠ Shield Dome | 6% | Enemy paint can't get in; you can shoot out. Lasts 10s |
| ⊕ Sentry Turret | 5% | Shoots enemies within range; its splats count for you. Stays until it takes 5 hits |
| 🌳 Bush | 7% | A hiding spot placed right where you stand. Bots can't see you inside unless they're right next to it, and other players see you faded. Lasts 90s |
| 💣 Paint Mine | 5% | A hidden trap at your feet. Only you and your teammates can see it. It arms after 1 second; the first enemy to step on it sets it off, and everyone nearby (except your side) takes 2 hits, counted as your splats. Stays until it goes off |

Chances are per drop, so a Golden Gun turns up about once every 75 splats.

## Playing with friends

1. One person taps **Host a game**. That opens the lobby with a 4-letter room code.
2. Friends open the same page, type the code and tap **Join**. They wait in the lobby and see it update live.
3. The host picks:
   - **Teams:** None (everyone for themselves), 2, 3 or 4
   - **Players:** the total, people plus bots (2–30). Bots fill whatever spots people don't.
   - **Who's on which team:** tap a team color next to each person, or **Shuffle teams**.
     New arrivals go to the smallest team.
4. The host taps **Start game**.

**Team games:** everyone wears their team's color and always spawns at their team's base (2 teams
face off left and right, 3 sit in a triangle, 4 on all sides). Teammates can't splat each other, and
the leaderboard shows each team's size and splats.

**Capturing bases:** get more of your team inside an enemy base than they have defending it and a
capture ring fills up in your color (about 8 seconds, faster with a bigger edge). More defenders than
attackers drains it; a tie holds it. When the ring fills, that base is gone and its whole team switches
to yours. The game ends when only one team is left; the host can then take everyone back to the lobby
for another round. Bots play the objective too: most attack the nearest enemy base, some guard home,
and they all rush back when their base is under attack.

A friend who joins mid-game goes to the team with the fewest people and takes a bot's spot.

**Bad connection?** If a friend's connection drops, the host keeps their player (team and score) for
90 seconds, and their game reconnects by itself. Joining the same room again within that time, from the
same device or with the same name, also brings them back as themselves. In team games the host can tap
**👥 Teams** (or press **T**) to move anyone to another team mid-game.
Up to 8 people can play at once (the rest of the 30 spots are bots), since the host's device sends
the game to every friend.

This is peer-to-peer: the host's device runs the game and friends connect straight to it, using the
free PeerJS service to find each other. Nobody needs an account. If the host leaves, the game ends for
everyone. Some school or work networks block these direct connections. Multiplayer doesn't work in the
Claude artifact version, so use the GitHub Pages link.

## Teaming up during a game

In games without set teams (solo, or a hosted game with Teams: None), tap **👥 Teams** at the top
(or press **T**) to see everyone, people and bots. Tap **Team up** next to someone; a person gets a
pop-up to **Accept** (Y) or say **No thanks** (N), and a bot decides after a moment.

Teammates:
- can't splat each other: their paint passes straight through
- aren't targeted by each other's turrets, and show as green dots on each other's minimap
- have a green dashed ring and 🤝 by their name

Either player can **Leave team** from the same list. It takes 3 seconds (the ring turns orange)
so nobody can turn on a teammate without warning. A person can team up with several others;
each pair agrees separately.

**Bots and teams:** bots pair up with each other now and then, and sometimes ask you. A bot has
at most one teammate, usually says yes when asked, but says no if you splatted it in the last
30 seconds. Bot teams last a few minutes, then the bot moves on (with the same 3-second warning).
Bots stick near their teammate when there's nobody to fight.

## Updates without losing your game

The page checks every 90 seconds whether a newer version is online. If there is one, an
**Update ready** button appears at the top. Tapping it saves the game, reloads with the new
version, and puts everything back: positions, scores, boosts, teams and paint on the ground.

- Playing solo: tap the button whenever you like.
- Hosting: tapping it updates everyone. Friends reload with you and rejoin the same room as the same player.
- Joined a friend's game: the button tells you the host can update everyone.

If a friend and the host end up on different versions, joining says so and asks both to refresh.

## Turning on GitHub Pages

1. Settings → General → Danger Zone → **Change visibility** → make the repo public
   (free GitHub Pages needs a public repo).
2. Settings → **Pages** → Source: **Deploy from a branch** → pick `main` and the `/ (root)` folder → **Save**.
3. After a minute or two the page is live at the address shown at the top of the Pages settings.
