# Overkill Run

A top-down pixel survival game where you only steer. Your weapons fire on their own, kills drop souls, and every level-up is a pick of three upgrades. The threat never stops climbing.

**Play it:** https://kefirman9000.github.io/overkill-run/ (works on desktop and phones)

## How it plays

- **Move** with WASD or the arrow keys. On a phone, drag anywhere on the screen.
- **Dash** with Space or Shift, or the DASH button on touch screens. It's your only defensive move, and it gives a moment of invulnerability.
- **Level up** by collecting souls. Pick one of three cards with 1, 2, 3 or a tap.
- **Power Surge**: level-ups that come faster than one every few seconds (or during a super mode) are banked. Three or more open one Power Surge screen: spend banked levels on a hand of cards or on surge cards (Overcharge a weapon +2 levels, Fast Evolution, a boosted Legendary), or cash the rest out for overkill meter and HP. The upgrade picker has **AUTO-PICK (Q)** (take the card auto-pick would choose) and **ALWAYS AUTO-PICK** (stop showing the picker; turn it back off in Options). Options also has auto-pick: at 5+ banked levels, or always (you never see the pick screen; it takes evolutions, then mutations that finish an evolution, defense when you're hurt, weapon upgrades and the rarest cards).
- **Pause** with P or Esc to see your build.

### Escalation

- Rarity runs Common → Rare → Epic → Legendary → Mythic. Higher threat and longer kill streaks push the odds toward the extreme stuff.
- Enemies attack in squads from one to three directions at a time, sometimes a pincer from both sides. The directions shift every 10 seconds or so, and red arrows at the screen edge point to where the next wave is coming from.
- Keep moving in a fight: stand in one spot for a few seconds with enemies close around you and something comes for you, either a **UFO** that beams you up and drops you elsewhere, or a **sandworm** that burrows over and erupts beneath you. Red marks close in around you first. In quiet spots, with few enemies nearby, you can stand still as long as you like. None of them can be shot; they all give up once you move. Souls and pickups left on the ground also fade away (they blink first).
- A **Soul Thief** turns up every minute or so. It runs from you dropping souls; catch it within 14 seconds for a burst of rare souls and a pickup (often a Heart Container).
- The threat meter rises with kills and time. It drives spawn rate, enemy toughness and elite chance.
- Six lands, each with its own enemies and hazards: Grassy Ruins, Burning Forest (lava), Frozen Wastes (ice you slide on), Toxic Swamp (poison clouds), Crystal Caves (eruptions), The Void (black holes). After the Void, the cycle repeats harder.
- Orbit Blades block enemy shots (evolved Saw Ring sends them back) and each Drone Minion can soak a shot every second.
- Tougher enemies join as the threat climbs: Wraiths (turn ghostly, threat 9), Lancers (telegraphed charges, 11), Mortars (shell where you're heading, 13), Splitters (burst into shards, 15), Snipers (long aim line, 18) and Juggernauts (bullet-resistant, ring-of-shots stomp, 20).
- Every 5 threat levels the land's boss arrives, and each one is a different kind of fight:
  - **The Warden** (Grassy Ruins): an arena. The horde vanishes, walls rise, and it's you against it.
  - **Cinder King** (Burning Forest): a ring of fire. It starts far out around you and closes in over about 30 seconds to a small arena, burning anything outside it.
  - **Glacial Maw** (Frozen Wastes): thin ice. An all-ice arena whose edge cracks away during the fight.
  - **Bog Mother** (Toxic Swamp): she dives and resurfaces elsewhere, and bubbles show where a second early.
  - **Prism Colossus** (Crystal Caves): shielded. Break its four pylons first, and each one enrages it.
  - **The Hollow** (The Void): a hunt. It stalks you unseen and can only be hurt when it shows itself.
- During every boss fight only the boss and whatever it summons are on the field.
- Later bosses fight in tighter arenas (down to 80% size). Every boss stops to catch its breath after each full cycle of attacks: for a couple of seconds it takes extra damage and a heart drops near you.
- Beating a boss heals you, banks a Power Surge and drops a Heart Container (+max HP).

### Weapons

Pea Shooter, Fireball, Chain Lightning, Homing Needles, Orbit Blades, Oil Slick, Homing Missiles, Cluster Bombs, Drone Minions, Prism Beam, Scattergun, Boomerang and Frost Nova. You start with one, carry up to four, and unlock more starting choices as you play.

### Evolutions

Max a weapon (Lv 6) while holding its matching mutation and the next level-up offers an evolution:

| Weapon | + Mutation | Evolves into |
|---|---|---|
| Pea Shooter | Ricochet | Pinball Cannon |
| Fireball | Chain Reaction | Meteor Storm |
| Chain Lightning | Cryo Coating | Storm Lattice |
| Homing Needles | Shrapnel | Hornet Swarm |
| Orbit Blades | Spike Trail | Saw Ring |
| Oil Slick | Incendiary | Napalm Wake |
| Homing Missiles | Twin Barrels | Missile Barrage |
| Cluster Bombs | Wide Load | Carpet Bomb |
| Drone Minions | Hair Trigger | Hive Mind |
| Prism Beam | Heavier Rounds | Death Ray |
| Scattergun | Rear Guns | Dragon's Breath |
| Boomerang | Drill Tips | Glaive Storm |
| Frost Nova | Cold Snap | Absolute Zero |

### Mutations

Rear guns, ricochet, shrapnel, snowball rounds that grow as they fly, halo volleys, spike trails, dash shockwaves, and late-run reality breaks such as bullets that orbit you, every 10th shot being a nuke, screen-wide pulses, black holes, and a permanent trail of fire.

Mutation cards show which of your weapons they evolve, and the pause screen lists your evolution plan.

### Look and feel

Each boss arrives with a cinematic intro card and a moment of slow motion. Changing land sweeps a stripe of the new land's colour across the screen, and the floating particles blend between lands. Screen effects add a soft glow to bright things, colour fringing during Overdrive and big moments, and heat shimmer near the Cinder King's fire wall. **Options → EFFECTS: OFF** turns them off, and they switch off on their own if the frame rate drops.

**Options → GRAPHICS: SIMPLE** (the default) keeps the middle of the screen clear: messages sit in a strip at the top, banners are smaller, your own shots, helpers, particles and ground details are toned down, and lands crossfade instead of changing tile by tile. GRAPHICS: FULL brings back the busier look.

Colours follow one simple rule so busy fights stay readable: anything that can hurt you is red or pink (enemy shots are always pink-red, chilling shots just get an ice-blue centre, and big hazards get a faint red outline), your own shots are shades of gold, and every pickup has a gold frame. Souls keep their rarity colours. **Options → COLORS: VIVID** brings back the old, more colourful look.

### Health and defense

Heart Containers raise max HP (bosses always drop one, elites sometimes do). Cards: Thick Skin, Iron Heart (+50 max HP, full heal), Plating (less damage taken), Giant's Blood (max HP x1.5). Rare pickups: Iron Skin (half damage for 12 s) and Guardian Orbs (three orbs that block shots for 15 s), alongside the existing heal, shield bubble, frenzy, freeze and screen bomb.

### Story, ranks and run cards

- Each land has a line of story the first time you reach it; the title screen collects them under **The Story So Far**, and winning adds the ending.
- Cards carry a line of flavour, and landmarks have names (the Weeping Spring, the Miser's Vault...).
- Your look grows with you: **Veteran** at level 10 (armor, gold belt, scarf), **Champion** at 25 (gold helm, crown, cape) and **Legend** at 40 (glowing eyes and outline). Each character has its own colours.
- The game-over screen shows highlights (MVP weapon, closest call, best streak, fastest boss, allies, landmarks, rank) and a **run card** image you can save or share.

### Characters and the ending

Pick a character on the title screen: **Wanderer** (no tricks), **Medic** (every upgrade pick heals 10%, -10% damage; unlock at threat 8), **Berserker** (up to +60% damage the lower your HP, -20 max HP; threat 12), **Scout** (faster, extra dash, double soul reach, -15 max HP; claim 10 landmarks) or **Tinker** (starts with a second random weapon, weapons recharge 10% slower; win a run).

The Hollow at the end of the first Void is the **final boss**. Beat it to win the run, then end there or keep going in endless mode.

### Pacing

Only one special event runs at a time (shrine, supply crate, Soul Thief, vault guards, calm), with at least 20 seconds of plain fighting between them. Super modes come from shrines, obelisks and the Overkill meter, roughly one every couple of minutes. Heart Containers are capped at 10 per run.

### Clear-outs, calms and checkpoints

- **Clear-out:** when a boss is due, the horde stops coming. Kill everything that's left (a counter shows how many) and the boss arrives. After 12 seconds the stragglers rush you, and after 30 anything left dissolves.
- **Calm:** midway between bosses the horde melts away and a beacon lights up some distance off, with a trail of souls leading to it. Reach it within 22 seconds for a heal, two free levels and a **checkpoint**: if you die later, you come back there once at half HP. Too slow, and the horde returns from every side.

### Landmarks

The world is dotted with places worth a detour, with markers at the screen edge when one is near:

- **Healing spring:** stand in it to heal until it runs dry.
- **Obelisk:** touch it to wake a super mode.
- **Vault:** a chest guarded by an elite pack. Clear the guards, then open it for souls, a Heart Container and a free level.
- **Nest:** spawns minis while you're near. Destroy it for a big payout.
- **Ally camp:** someone is caged here. Stand by the cage for a moment to free them, and they join you.

### Allies

Up to two allies follow you at once: the **Gunner** shoots whatever is closest, the **Field Medic** heals you and your other ally while close, and the **Knight** charges enemies near you and draws attackers off you onto itself. Allies have their own HP and heal slowly; if they go down, they're gone. They follow you into boss fights and catch up if you're teleported.

### More pickups and cards

Pickups also include **Wind Boots** (endless dashes and +30% speed for 10 s) and **Thunderclap** (lightning through up to 25 enemies). New cards: Dash Barrage (each dash fires a ring of shots), Bounty Hunter (elites always drop one) and Glass Cannon (+60% damage, -30% max HP).

### Super modes

Short, overpowered bursts you trigger on the battlefield:

- **Power shrines** appear about once a minute. Stand on one for under two seconds.
- **Supply crates** drop in with a shadow. Your weapons crack them open and they leave a power orb.
- **The Overkill meter** fills while you hold a 25+ kill streak and fires a mode on its own when full.

Modes: Overdrive (every weapon evolved), Titan (huge, invulnerable, crushes what you touch), Time Stop, Orbital Strike, Storm Cloud, Turret Drop, Soul Rush.

## Install on your phone

Open the GitHub Pages link in Chrome and tap **Install app** on the title screen, or use the browser menu's **Add to Home screen** / **Install** (Firefox: menu → Install). It runs full screen and works offline after the first load.

## Run reports

Pause or die, type any thoughts into the notes box, then press **Copy run report**. It copies a summary of the run (picks, damage by source, a 30-second timeline, frame rate, device) that you can paste into a chat for balance review. **Save report file** downloads the same thing as a .txt.

## Updates

On the title screen, **Check for update** asks GitHub for the latest version and only updates when you choose to.

## Run it locally

It's a single file. Download `index.html` and open it in a browser.

## Support

If you enjoy this, you can support development through [GitHub Sponsors](https://github.com/sponsors/kefirman9000).
