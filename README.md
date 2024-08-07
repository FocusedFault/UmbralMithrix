# Umbral Mithrix

**CHECK OUT THE SONG MOD MADE FOR THE FIGHT! [AltMithrixTheme](https://thunderstore.io/package/Nuxlar/AltMithrixTheme/) (works without umbral)**

**NEW LOGBOOK AUDIO! READ BY WAYNE JUNE (DARKEST DUNGEON NARRATOR) USING AI (control volume with SFX slider not music)**

**_SUBMIT ANY ISSUES FOUND WITH A LOG TO THE LINK ABOVE_**

Major reworks to the fight, a new trophy item, and a practice mode. When you spawn on the moon there'll be a shrine to optionally activate the mode. You only need to interact with it once even if you're using LunarApostles. When completing the fight you'll get a trophy item to track your victories against Umbral.

### Practice Mode

Practice mode just makes you respawn on death in case you want to learn/practice the fight but don't want to do a whole other run (infinite dio's). The trophy item won't spawn at the end of the fight. The mode deactivates after Mithrix dies in Phase 4.

### Config Info

You can edit config values in-game and during runs through Settings -> Mod Options -> UmbralMithrix. Stats are calculated at the start of each phase so you can change in-game configs up until the phase starts. If the in-game values are too limiting you can edit the modman config to input custom values.

## Credits

- Race for ideas, feedback, testing, and writing the trophy item's logbook entry
- breadguy for the trophy item idea
- Everyone else who gave feedback, ideas, and bug reports

## Changelog

**2.4.1**

- Removes P3 third pizza
- Reduces P3 pizza max spawn distance (45m -> 40m)
- Increases P3 pizza speed (21 -> 25) Vanilla pizza has a max speed of 30

**2.4.0**

- Difficulty update, since Umbral is now "too easy" because of Phase 4 being removed.
- Re-adds Crushing Leap (leap that tracks until the last second) - multiplayer will have the "normal" leap
- Re-adds a central moving pizza to Phase 2
- Reduces Phase 2 stationary pizza slices by 50%
- Adds a third pizza to Phase 3
- Adds glass clones to Phase 3
- Clone lifetime changes each phase (P1 12s, P2 6s, P3 4s)
- Increases base glass clone spawn distance 8m -> 12m (to hopefully prevent clipping)
- Reduces orbs in P3 fist slam (8 -> 6)
- Removes pitch spread from needles (only spreads left/right not up/down)
- Fixes fire pillar not showing up

**2.3.4**

- Removes Phase 4 entirely
- Note: I don't like current Umbral Phase 4 and vanilla isn't any better, so I'm removing this phase completely until I can make a phase 4 that's better

**2.3.3**

- Reverts some of the P4 changes
  - Removes FlameWall
  - Decreases intervals (faster)

**2.3.2**

- Fixes P4 using items (i forgor)

**2.3.1**

- Fixes Crystals not being on the right team
- Removes crystal explosion damage
- Reduces P4 missile count (8 -> 4)
- Reduces P4 missile homing
- Increases duration of P4 flame walls
- Adds umbral overlay to crystals

**2.3.0**

- Adds config for umbral effect on mithrix (purple lighting when spawning in)
- Adds Mithrix/Clones focusing mainly players throughout the fight
- Adds glass clones for phase 2
- Removes shockwave on swipe
- Increases distance for glass clone spawns
- Reduces distance Mithrix fire lunar shards (70 -> 20)
- Reduces lunar shard stock count (12 -> 6)
- Fixes HP thresholds not applying sometimes
- Fixes trophy item dropping outside of the fight
- Fixes P4 pizza breaking if dying in practice mode
- Phase 2 Tweaks
  - Instead of 4 static pizzas at fixed spots, the static pizzas surround a random player
  - There is no longer a spinning pizza under Mithrix
- Phase 4 Tweaks
  - Adds giant spinning flame wall
  - Increases intervals for pizza/shockwaves/missiles

**2.2.1**

- Adds a config for the purple arena wall/ceiling VFX (now off by default)

**2.2.0**

- Added narration for "Core of the Collective" logbook entry (2 buttons added to logbook entry - Play/Stop)
- Added some formatting for the "Core of the Collective" logbook entry
- Makes P3 invincible Mithrix chase players only
- Removes P3 drone destruction
- Increases P4 pizza damage
- Increases P4 shockwave damage
- Increases P4 missile damage

**2.1.6**

- Removes turret killing on P3 (for both Engi and Gunner turrets)
- Judgement Compat
  - Reduces P2 clone HP by 75%
  - Reduces clone orb damage by 25%
  - Removes P3 drone kills
  - Reduces P3 clone HP

**2.1.5**

- Fixed multiplayer P4 sending out multiple pizzas/shockwaves (fr this time)
- Fixed multiplayer skyleap wonky targeting (indicator spawns on one player but lands on another)
- Updated R2API Content Management dependency

**2.1.4**

- MOONSTORM/STARSTORM BUG FIXED FINALLY (THANK YOU NEBBY!!!) (ALSO ANY OTHER WEIRD INCOMPATS SHOULD BE FIXED)
- Fixes P4 pizzas not working if you die in practice mode
- Fixes multiplayer P4 releasing multiple shockwaves (maybe)

**2.1.3**

- Reduces P3 clone HP significantly
- Fixes leap indicator lingering if Mithrix dies while leaping

**2.1.2**

- Fixes Moonstorm/Starstorm bug (fr this time)
- Swaps P3 crystals with glass clones
- Changes how some things work internally to fix the bug

**2.1.1**

- Adds semi-tracking leap (jumps to a random player position)
- Fixes P4 intervals being way too slow
- Fixes P2 immunity threshold still being bypassed
- Fixes boss subtitle not having the 2 clouds
- Reduces P1 clone duration 12 -> 6 secs
- Adds sound cue to leap

**2.1.0**

- Removes Bonfire mode
- Fixes Starstorm/Moonstorm P3 crystal bug
- Fixes P2/P3 immune threshold not working
- Fixes Multiplayer issues (hopefully)
  - P3 crystals not disappearing
  - Leap spawning multiple shockwaves and only tracking the host
  - P4 shockwaves firing multiple times
  - P3/P4 pizza only tracking the host
- Balance changes
  - P1 clones spawn less frequently but last longer to make it less chaotic
  - Changes leap from tracking to in-place (jumps and lands in the same spot)
  - P3 drones can be bought back (all drones are still destroyed at the beginning of the phase)
  - P4 Tweaks
    - Kills all allies after items are stolen
    - Reduces shockwave interval 6 -> 5.75 seconds
    - Reduces missile interval 3 -> 1 second
    - Reduces pizza damage and force by 50%
    - Reduces shockwave force by 50%
  - Retalitory super shards are now chance based
    - 50% chance to fire a shard when frozen
    - 25% chance to fire a shard when nullified (tentabauble)
