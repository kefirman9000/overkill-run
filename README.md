# Overkill Run

A top-down pixel survival game where you only steer. Your weapons fire on their own, kills drop souls, and every level-up is a pick of three upgrades. The threat never stops climbing.

**Play it:** https://kefirman9000.github.io/overkill-run/ (works on desktop and phones)

## How it plays

- **Move** with WASD or the arrow keys. On a phone, drag anywhere on the screen.
- **Dash** with Space or Shift, or the DASH button on touch screens. It gives a moment of invulnerability.
- **Ability** with E (or the small gold button next to Dash): each character has one, on a cooldown. Wanderer: Second Wind (heal and a moment untouchable). Medic: Triage (heal over time, allies fully healed). Berserker: Rampage (+60% damage, faster weapons). Scout: Smoke Bomb (a decoy that explodes). Tinker: Overclock (every weapon fires at once, then recharges much faster).
- **Level up** by collecting souls. Pick one of three cards with 1, 2, 3 or a tap.
- **Power Surge**: level-ups that come faster than one every few seconds (or during a super mode) are banked. Three or more open one Power Surge screen: spend banked levels on a hand of cards or on surge cards (Overcharge a weapon +2 levels, Fast Evolution, a boosted Legendary), or cash the rest out for overkill meter and HP. The upgrade picker has **AUTO-PICK (Q)** (take the card auto-pick would choose) and **ALWAYS AUTO-PICK** (stop showing the picker; turn it back off in Options). Options also has auto-pick: at 5+ banked levels, or always (you never see the pick screen; it takes evolutions, then mutations that finish an evolution, defense when you're hurt or have fallen behind on it (about one defensive card per 4 threat), weapon upgrades and the rarest cards).
- **Pause** with P or Esc to see your build.

### Escalation

- Rarity runs Common → Rare → Epic → Legendary → Mythic. Higher threat and longer kill streaks push the odds toward the extreme stuff.
- Enemies attack in squads from one to three directions at a time, sometimes a pincer from both sides. The directions shift every 10 seconds or so, and red arrows at the screen edge point to where the next wave is coming from.
- Keep moving in a fight: stand in one spot for a few seconds with enemies close around you and something comes for you, either a **UFO** that beams you up and drops you elsewhere, or a **sandworm** that burrows over and erupts beneath you. Red marks close in around you first. In quiet spots, with few enemies nearby, you can stand still as long as you like. None of them can be shot; they all give up once you move. Souls and pickups left on the ground also fade away (they blink first).
- A **Soul Thief** turns up every minute or so. It runs from you dropping souls; catch it within 14 seconds for a burst of rare souls and a pickup (often a Heart Container).
- The threat meter rises with kills and time. It drives spawn rate, enemy toughness and elite chance.
- **Fewer, bigger enemies:** past threat 4 the horde grows in size rather than numbers. Big enemies are drawn larger, hit harder, move a little slower and shoulder small ones aside; one twice as wide counts as four small ones for souls, kills, threat, the Overkill meter and on-kill effects. Piercing shots drill through big bodies for extra damage instead of passing on. The number of bodies on screen is capped (80 on phones).
- **Big enemies have moves** (size 1.75 and up): Tanks and Crystal Golems stop and **slam** the ground (a red ring grows around them first), Chasers stop, aim and **lunge**, big Spitters fire five shots and big Frostlings three, and big Exploders leave a **pool of fire**.
- Seven lands, each with its own enemies and hazards: Grassy Ruins, Burning Forest (lava), Frozen Wastes (ice you slide on), Toxic Swamp (poison clouds), Crystal Caves (eruptions), Storm Peaks (gusts that shove you, with streaks showing the direction), The Void (black holes). After the Void, the cycle repeats harder.
- Orbit Blades block enemy shots (evolved Saw Ring sends them back) and each Drone Minion can soak a shot every second.
- Tougher enemies join as the threat climbs: Wraiths (turn ghostly, threat 9), Lancers (telegraphed charges, 11), Mortars (shell where you're heading, 13), Splitters (burst into shards, 15), Snipers (long aim line, 18) and Juggernauts (bullet-resistant, ring-of-shots stomp, 20).
- Every 5 threat levels the land's boss arrives, and each one is a different kind of fight:
  - **The Warden** (Grassy Ruins): an arena. The horde vanishes, walls rise, and it's you against it.
  - **Cinder King** (Burning Forest): a ring of fire. It starts far out around you and closes in over about 30 seconds to a small arena, burning anything outside it.
  - **Glacial Maw** (Frozen Wastes): thin ice. An all-ice arena whose edge cracks away during the fight.
  - **Bog Mother** (Toxic Swamp): she dives and resurfaces elsewhere, and bubbles show where a second early.
  - **Prism Colossus** (Crystal Caves): shielded. Break its four pylons first, and each one enrages it.
  - **Tempest** (Storm Peaks): blows you around with gusts, calls down lightning where you're heading, and in phase two sends rings of wind in from the arena wall. Beat it for the **Storm Vane** (+15% speed, dashes throw lightning).
  - **The Hollow** (The Void): a hunt. It stalks you unseen and can only be hurt when it shows itself.
- During every boss fight only the boss and whatever it summons are on the field.
- Bosses are **huge**, over four times your width and bigger with each one you beat, and the camera pulls back for them. Their HP keeps up with strong builds (at least what your recent damage against the horde would need 16 seconds to get through), and right after enraging they take less damage for a moment so phase two is always seen.
- Every boss also fights with its body: a **stomp** (a ring around it) and, once enraged, a **sweep** (an arc toward you that lands from one side to the other). Each leaves its **core exposed** for a moment: it glows gold, the boss bar turns gold, and it takes 50% more damage. The boss bar has a mark at half HP, where it enrages.
- Boss bullets come in **patterns** you can read, like a bullet hell: rings always leave lanes wider than you and line up on you, alternating between a lane and a bullet pointing your way (a small sidestep takes you through each); counter-rotating spirals form an even lattice; the Tempest's gusts push you sideways without moving the bullets, its fans interleave, and its lightning lands in a + or × cross on where you're heading (step diagonally). A cap on enemy shots keeps patterns from stacking into a wall.
- Later bosses fight in tighter arenas (down to 80% size of a larger base arena). Every boss stops to catch its breath after each full cycle of attacks: for a couple of seconds it takes extra damage and a heart drops near you.
- At half HP every boss **enrages**: a shockwave pushes you back, it attacks faster, and it adds a new attack (Warden crossfire, Cinder King meteor fall, Glacial Maw ice walls, Bog Mother brood burst, Prism Colossus rotating lasers, Hollow eclipse).
- Every boss drops its **trophy**, a power for the rest of the run, and the first win unlocks it as a starting relic.
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

Mutation cards show which of your weapons they evolve, and the pause screen lists your evolution plan. Once a weapon is maxed, the mutation it still needs turns up much more often.

### Look and feel

Each boss arrives with a cinematic intro card and a moment of slow motion. Changing land sweeps a stripe of the new land's colour across the screen, and the floating particles blend between lands. Screen effects add a soft glow to bright things, colour fringing during Overdrive and big moments, and heat shimmer near the Cinder King's fire wall. **Options → EFFECTS: OFF** turns them off, and they switch off on their own if the frame rate drops.

**Options → GRAPHICS: SIMPLE** (the default) keeps the middle of the screen clear: messages sit in a strip at the top, banners are smaller, your own shots, helpers, particles and ground details are toned down, and lands crossfade instead of changing tile by tile. GRAPHICS: FULL brings back the busier look.

Colours follow one simple rule so busy fights stay readable: anything that can hurt you is red or pink (enemy shots are always pink-red, chilling shots just get an ice-blue centre, and big hazards get a faint red outline), your own shots are shades of gold, and every pickup has a gold frame. Souls keep their rarity colours. **Options → COLORS: VIVID** brings back the old, more colourful look.

### Elements

Hits can burn, slow, shock, blast and now **poison** (Venom Rounds, the Bog Bladder). Mixing elements causes reactions: **steam** (fire on a frozen enemy, or frost on a burning one) bursts on everything close, a **gas explosion** (fire or a blast on a poisoned enemy) spreads fire, and **toxic shock** (lightning on a poisoned enemy) jumps between poisoned enemies.

### Relics

Pick up to two on the title screen: Lodestone Charm, Mutagen, Running Shoes, Gilded Idol (+25% souls; threat 15), Hourglass (super modes last longer; win a run), and one per boss trophy (Warden's Seal, Cinder Crown, Frost Heart, Bog Bladder, Prism Lens, Hollow Core). Some pairs combine into a bonus: Steam Engine, Wildfire, Toxic Prism, Blink Strider, Featherweight, Gold Rush, Time Sink and Mutant Lens.

### Health and defense

Heart Containers raise max HP (bosses always drop one, elites sometimes do). Cards: Thick Skin, Iron Heart (+50 max HP, full heal), Plating (less damage taken), Giant's Blood (max HP x1.5). Rare pickups: Iron Skin (half damage for 12 s) and Guardian Orbs (three orbs that block shots for 15 s), alongside the existing heal, shield bubble, frenzy, freeze and screen bomb.

### Story, ranks and run cards

- Each land has a line of story the first time you reach it; the title screen collects them under **The Story So Far**, and winning adds the ending.
- Cards carry a line of flavour, and landmarks have names (the Weeping Spring, the Miser's Vault...).
- Your look grows with you: **Veteran** at level 10 (armor, gold belt, scarf), **Champion** at 25 (gold helm, crown, cape) and **Legend** at 40 (glowing eyes and outline). Each character has its own colours.
- The game-over screen shows highlights (MVP weapon, closest call, best streak, fastest boss, allies, landmarks, rank) and a **run card** image you can save or share.

The title screen keeps it short: START RUN and DAILY RUN up top, then one row showing your character, weapon and relics. Tap any of them to change it. How to play and the story are folded away underneath.

### Characters and the ending

Pick a character on the title screen: **Wanderer** (no tricks), **Medic** (every upgrade pick heals 10%, -10% damage; unlock at threat 8), **Berserker** (up to +60% damage the lower your HP, -20 max HP; threat 12), **Scout** (faster, extra dash, double soul reach, -15 max HP; claim 10 landmarks) or **Tinker** (starts with a second random weapon, weapons recharge 10% slower; win a run).

The Hollow at the end of the first Void is the **final boss**. Beat it to win the run, then end there or keep going in endless mode.

In **endless mode** bosses come back changed. Each lap they get stranger colours (shifted, then neon, then a cycling rainbow) and one more random mutation, up to four: Swift, Armored, Volatile, Brooding, Regenerating, Chaotic (steals another boss's attack), Colossal and Vampiric. The boss card names them.

### Modes, characters, chests and more (1.35)

- **Modes** (title screen → MODE): Standard, **Boss Rush** (threat climbs 3x as fast, start with 3 levels), **Horde** (twice the enemies at half health), **Chaos** (events, strikes, altars, worms and formations twice as often and earlier; 10 passive slots), **Purist** (only your starting weapon, +60% damage) and **Glass** (max HP stuck at 40, double damage).
- **New characters**, all available from the start: **Necromancer** (kills raise wisps that hunt for you; ability Mass Raise), **Juggernaut** (+100 HP, spiked hide, slower; dash is a ground slam; ability Earthquake), **Gambler** (much luckier, bigger and more frequent chests; ability All In opens a chest) and **Pyromancer** (starts with Fireball too, fire +50%, immune to lava and flames; ability Inferno).
- **Treasure chests** drop from bosses, champions and sometimes elites. Opening one spins a reel and pays out 1, 3 or (rarely) 5 upgrades, evolutions first.
- **Banish (B) and Skip (X)** on the level-up screen. Banish removes a card or weapon from the rest of the run (3 per run, +1 per boss). Skip takes nothing and heals 10%.
- **Passive cap:** you can hold 8 different passive cards (Chaos: 10). After that you only get offers that stack what you have, plus weapons. When everything is full, **Limit Break** cards keep giving damage, fire rate or healing.
- **New weapons:** Chain Whip (lash to the side you face → Bloody Tear with Lucky Shots), Holy Aura (burning halo → Soul Eater with Spiked Armor), Mine Layer (mines where you walk → Cluster Field with Shoulder Check) and Sentry Kit (plants turrets → Fortress with Barrier).
- **New enemies:** Bombers (lob bombs at where you're heading, shown as red circles), Gunners (stop and spray a stream of shots), Watchers (charge a laser shown as a red line) and **Worms**: long chains of segments that weave toward you. Cut one in the middle and you get two worms.

### Events, danger and terrain (1.34)

- **Rule-changing events** (one at a time, every minute or two from threat 2): **Siege** (a two-row wall of enemies from one side), **Ambush** (the field goes quiet, red marks appear around you, then they spawn), **Hunt** (a fleeing golden runner with a fortune: catch it in 22 s), **Hold the Line** (stand in a circle until it fills for a heal and 2 levels), **Stampede** (lanes of unstoppable beasts, warned by red lines), **Blackout** (only a circle of light; enemies show as eyes; souls worth 1.5x) and **Storm Front** (a wall that sweeps the map; stay ahead of it).
- **Strikes** from threat 4: artillery circles, sweeping lasers and meteor showers, telegraphed in red. They hit for a share of your **max HP** and armour doesn't reduce them, so stacking health doesn't make you safe. They hurt enemies too.
- **The Hunter** from threat 8: can't be killed, follows you for 30 s, and a touch takes a third of your max HP. Lose it without being touched for a free level.
- **Formations:** shield walls that march in a line (go around the ends), packs that circle you and then rush, and columns that march through.
- **Terrain:** every land has its own obstacles. Ruin walls and pillars, burnt trees, boulders, swamp streams with bridges (water slows everyone), crystal clusters and void rifts, plus breakable crates. Walls block enemy shots; your shots pass over them. Enemies stuck behind a wall for long squeeze through. Terrain clears itself around boss arenas, beacons, shrines and landmarks. Options: TERRAIN ON / OFF.
- **Cursed altars** from threat 3: walk over one to read its bargain, stand on it to accept. Greed (a Legendary card, but half of new enemies are elite for 60 s), Hunger (3 levels, no healing until the next boss), Souls (double souls but faster enemies for 90 s), Blood (full heal and +25 max HP, threat +2) and Iron (+2 levels to your weakest weapon, and the Hunter comes).
- **A fork in the road** after each boss: green gate for the safe road, red gate for the hard road (tougher enemies, more elites, better cards and +50% souls until the next boss).
- **Auto-pick can stop for Epic and up** so build-defining picks stay yours: Options → AUTO-PICK STOPS FOR EPIC+ (off by default).
- Stacked defense now has diminishing returns: each extra Plating or Leech gives less, and extra Barrier charges recharge only a little faster.

### Pacing

Only one special event runs at a time (shrine, supply crate, Soul Thief, vault guards, calm), with at least 20 seconds of plain fighting between them. Super modes come from shrines, obelisks and the Overkill meter, roughly one every couple of minutes. Heart Containers are capped at 10 per run.

### Clear-outs, calms and checkpoints

- **Clear-out:** when a boss is due, the horde stops coming. Kill everything that's left (a counter shows how many) and the boss arrives. After 12 seconds the stragglers rush you, and after 30 anything left dissolves.
- **Calm:** midway between bosses the horde melts away and a beacon lights up some distance off, with a trail of souls leading to it. Reach it within 26 seconds for a heal, two free levels and a **checkpoint**: if you die later, you come back there once at half HP. Get there in the first half of the time for a **fast bonus** (an extra level and a bigger heal). Dawdle and stragglers start closing in from behind, and the last ten seconds tick down with a red pulse. Too slow, and the horde returns from every side.

### Landmarks

The world is dotted with places worth a detour, with markers at the screen edge when one is near:

- **Healing spring:** holds a set amount of healing; stand in it to heal until it runs dry.
- **Obelisk:** touch it to wake a super mode.
- **Vault:** a chest guarded by an elite pack. Clear the guards, then open it for souls, a Heart Container and a free level.
- **Nest:** spawns minis while you're near. Destroy it for a big payout.
- **Ally camp:** someone is caged here. Stand by the cage for a moment to free them, and they join you.

### Curios

Smaller things turn up while you explore, some useful and some just there: abandoned packs, broken carts, old signposts, graves (usually quiet), mushroom rings (something happens, probably), watching statues, campfires (heal when it's quiet, until the fuel runs out), treasure maps (dig up the chest), a wandering merchant (a rare card for a fifth of your HP), wishing wells (throw in souls, make a wish), a lost dog that follows you and fetches souls, and sleeping giants carrying a lot of loot.

### Difficulty and champions

Pick **Easy**, **Normal** or **Nightmare** on the title screen (tap the Difficulty box to cycle). Each keeps its own best. Nightmare enemies are tougher and hit harder, elites get two tricks, champions show up twice as often, and every boss is mutated from the first lap. Daily runs are always Normal.

**Champions** are rare named elites (like *Vexa the Volatile*) with a crown and one mutation: Swift, Armored, Volatile, Brooding, Undying or Blinking. Kill one for a free level, a heart and a pickup.

New enemies: the **Shielder** (enemies near it take far less damage), the **Burrower** (digs under and bursts out where you stand) and the **Medic** (heals hurt enemies near it).

### Achievements, looks and perks

31 achievements (open them from the title screen). Many unlock a new **look** for your character (picked under Character) or a small **perk** that applies to every non-daily run: a starting reroll, +20% soul reach or +10 max HP.

### Daily mutations and seeds

Each daily run has two mutations that apply to every enemy that day, the same for everyone (hover or long-press Daily Run to see them). Every run has a six-character **seed**, shown when paused and at the end. Type one into *Play a seed* on the title screen to get the same map and the same upgrade offers; enemies still vary.

### Options worth knowing

Damage numbers are off by default; turn them on for big hits only or for every hit (hits on the same enemy add up into one number). A small radar in the top-right corner shows the beacon, the boss, shrines, nearby landmarks and where enemies are bunching up. The end-of-run screen breaks down where your damage came from, what hurt you, how much you healed, beacons reached and each boss's fight time and mutations.

### Phones

On touch screens the game caps itself at 60 fps (120 Hz phones otherwise do twice the work for no gain), draws at most 2 canvas pixels per world pixel (drawing at 4 was about 6 times slower for a little extra smoothness), skips the glow when the screen is crowded, lets far-off enemies think less often, and draws the radar and damage numbers from cached images.

### Codex

The pause menu's **Codex** lists every enemy, boss, place, curio, evolution and card you've found across all your runs.

### New players

Until you've reached threat 10 once, the game introduces its systems gradually: landmarks and shrines from threat 1, Soul Thieves, crates and standing-still threats from 2, allies and sleeping giants from 3, and the first calm at threat 8.

### Allies

Up to two allies follow you at once: the **Gunner** shoots whatever is closest, the **Field Medic** heals you and your other ally while close, and the **Knight** charges enemies near you and draws attackers off you onto itself. Allies have their own HP and heal slowly; if they go down, they're gone. They follow you into boss fights and catch up if you're teleported.

Allies **level up** too, slower than you: each level takes a few more of your upgrade picks than the last (3 picks for Lv 2 up to 7 for Lv 6), shown as gold pips over its head, for +25% damage, a faster weapon, more max HP and a heal. Allies who join later arrive a level or two up.

At **Lv 3 and Lv 5 you choose a perk** for the ally: two perk cards take the place of two cards on your next level-up (auto-pick takes one too).

| Ally | Lv 3 | Lv 5 |
|---|---|---|
| Gunner | Scattershot (three shots, wider) or Deadeye (pierce two more, +30% damage) | Rocketeer (every fourth volley adds a homing rocket) or Rapid Fire (40% faster) |
| Field Medic | Triage (heals you twice as fast, from further) or Combat Medic (two shots, +40%, they slow) | Aegis (a shield that blocks one hit every 20 s) or Field Hospital (all allies heal 4x faster and take 30% less damage) |
| Knight | Bulwark (draws enemies from twice as far, takes 40% less) or Bloodblade (swings heal you and it) | Whirlwind (spins every 3 s, hitting everything around it) or Cleaver (wider swings, +60%) |

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

Pause or die, type any thoughts into the notes box, then press **Copy run report**. It copies a summary of the run (picks, damage by source, a 30-second timeline, frame rate, device, and for each boss fight its HP, size, your horde damage per second going in and the damage you took, including a fight you lost) that you can paste into a chat for balance review. **Save report file** downloads the same thing as a .txt.

## Continue a run

The game saves your run whenever it pauses, including when you switch apps or the phone locks. If the browser closes the tab in the background, **CONTINUE** on the title screen picks up where you left off (it shows the threat and time). Starting a new run, quitting to the title or dying clears the save.

## Run history

**Run History** on the title screen keeps your last 40 runs in this browser: deaths, wins, and quits after the first minute. It shows totals (runs, wins, best threat, longest run), what kills you most, your most used weapons and each boss's record and average fight time, then every run with its result, threat, time, kills, level and weapons. The newest 10 keep their full run report, with a button to copy it. **COPY FOR REVIEW** copies one summary of all of them: how often each card was offered and taken (and which are never taken), super modes, how often each system came up, and every run with its picks.

## Updates

On the title screen, **Check for update** asks GitHub for the latest version and only updates when you choose to.

## Run it locally

It's a single file. Download `index.html` and open it in a browser.

## Support

If you enjoy this, you can support development through [GitHub Sponsors](https://github.com/sponsors/kefirman9000).
