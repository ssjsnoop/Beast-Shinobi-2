# Stormstep Awakening (2026-11-11)

- Awakened Ninja gains six additional midair jumps after takeoff (seven jumps including the ground jump). The triple-jump upgrade does not add a seventh air jump. Normal jump limits return when Awakening ends.
- Powered running multiplier rises from 1.35 to 2.1: unupgraded move speed 714 and sprint 1178.1, compared with normal 340 / 561. Faster powered acceleration and braking keep the speed controllable; wall collisions remain solid.
- Added streaming blue-white spirit cloak, lightning strokes, crown sigils and powered jump bursts over approved ninja art. Reduced the old white wash so the character stays visible.
- Regular and powered run animation uses faster speed-driven leg cadence, forward lean, leg-only pose echoes and trailing motion lines.
- Forward-neutral-forward + attack dash strikes now work in midair, with natural gravity and one hit per strike. Unified gesture for controller, keyboard and touch directions. Fixed Dragon steering overriding the rush movement. Rising slash and down-air plunge retain directional priority.
- Updated Awakening controls/tutorial and dynamic corner reminder. Full five-pass game preserved.

# Pass 5 / 5 — Final Balance (2026-11-10)

- Fixed archer/ghost shot creation: the y-offset option overwrote the computed world position, causing shots to originate at y=64 or y=50. Shots now originate beside the attacker at the intended firing height. Existing speed, warning, damage and cadence retained.
- Ordinary enemy health rises 2% per realm, reaching 12% extra in the palace. No added attack-damage, movement-speed or crowd-size multiplier. Stronger enemy composition and boss phases remain the primary difficulty progression.
- Normal melee enemies commit their facing during the final portion of their windups. Archer's close-range warning lasts through its full 0.55-second draw.
- Guardian health now uses the same 12%-per-cycle New Game+ scaling as other foes.
- Preserved boss pursuit onto reachable platforms. Fixed leap landing burst hitting a player far below the impact. Emperor seal warning and damage rectangle now use the captured target height together, including upper platforms.
- Completed all five passes; preserved artwork, music, full progression, saves, controller wheel, companion recall, wolf trails/charges and corner moves panel.

# Pass 4 / 5 — Corner and Control (2026-11-10)

- Anchored the desktop moves panel exactly to the bottom-right game-canvas edges. Its height follows the current form; footer remains inside the box. Compact form shortcuts reserve the space beside it, including narrow desktop aspect ratios. Corrected Fire Wolf's claw description and controller shortcut labels.
- Blur, hidden-page and controller-disconnect events pause play, close the form wheel, clear queued/held input, cancel partial charges and discard dash-combo timing. Returning to focus never auto-resumes. Controller buttons/triggers must return to neutral before a fresh action can occur after focus loss.
- Added touch safe-area offsets for action controls, pause and joystick; safe-area menu padding. Larger minimum radial wheel targets with border-box sizing.
- Canvas backing dimensions no longer reset when unchanged. Resize/orientation settle callbacks are replaced rather than accumulated. Off-screen cosmetic particles skip drawing without changing their lifetimes or any gameplay simulation.
- Preserved approved artwork, music, campaign, saves and all prior passes.

# Pass 3 / 5 — Read the Storm (2026-11-10)

- Added named boss attack tells, windup progress strips and directional ground markers. Recovery windows show OPENING; vulnerable charge recovery shows EXPOSED. Labels stay inside the camera horizontally.
- Combo follow-ups now warn and commit their facing; warning steps have a 0.36-second floor in later phases.
- Phase changes clear enemy shots, enemy zones and queued rain, then provide a 0.85-second regroup without contact damage. Bosses retain their health and phase scaling; player projectiles remain.
- Replaced move-selection retries with legal candidate selection: no immediate repeats when another eligible move exists, no melee selected out of range, and no summon selection above the minion cap.
- Every third non-Bear guardian action can charge a signature volley: Kitsune three-way spirit fan, Fire Wolf flame shot, Electric Wolf fast gold lightning, Ice Wolf ice lance, Dragon paired fire shots. 0.85-second windup, locked target line, short projectile lifetime and recovery. Ice lances rotate into their travel direction. Heavy hits can interrupt guardian windups.
- Preserved full game, approved sprites, original score, saves, companion recall and two-second wolf charging.

# Pass 2 / 5 — Spirit Recall (2026-11-11)

- Removed the 22-second companion cooldown and active-pet summon block. Release and hold ATTACK for three seconds to summon again or recall/refresh the current pair. One call per hold. Recalling active pets does not farm mastery.
- Wolf elemental breath charges for two gameplay seconds including impact freezes; pauses, tutorials, wheel and cutscenes do not advance it. Release to rearm. Damage/dash still interrupt charging.
- Added companion lifetime label and SUMMON/RECALL charge labels; updated tutorial guidance and respawn charge resets.
- Preserved all prior combat/art/audio/progression/save features.

# Version history
R1–R4: six-realm expanded game, HUD/combat overhaul, registered character animation art, wolf elements and ice bridges, Kitsune and mixed undead patrols.
Beast Shinobi 2 v1: full-power sanctuary prologue and Emperor power theft; Haunted Temple undead humans; Emperor’s Palace seventh realm and Raizen final boss; original-ending continuation; true victory page; linear New Game+ with powers retained; new title art and branding. Prior save-slot keys retained.

Beast Shinobi 2 v2 — Spirit Doors: six-form roster; Bear level-one reward; four optional guardian-door trials; RT tap/hold wheel with saved choice; controller dash attack; starter rising slash; 500-coin Triple Jump; Dragon lightning; desktop-only move reminders.

Beast Shinobi 2 v3 — Stormfire: lower desktop move reminders; redesigned, larger and stronger Dragon; mouth-anchored Dragon lightning/fire; two-second elemental wolf breaths; contextual Y beast-special / Ninja clone controller mapping.

Five-pass improvement series, Pass 1/5 — Wild Fang Combat: extended elemental wolf slashes, Dragon fire-hand combo, shorter steerable burst and lightning, original three-track score, differentiated sword/element effects, audio pause/mute recovery and bounded scheduling fixes.
