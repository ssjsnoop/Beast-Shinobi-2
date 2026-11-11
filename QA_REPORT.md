# Stormstep Awakening verification

New actual-JavaScript motion fixtures pass: initial ground jump plus six further jump inputs, rejection of a seventh air jump, normal limit after Awakening ends; measured normal movement 340 / sprint 561 and powered movement 714 / sprint 1178.1; full-speed collision against a solid wall; both-direction controller air dash strike; keyboard air gesture; one-hit 20-damage aerial rush; all six beast forms travel through the new aerial rush. Reviewed native Canvas rendering of the new mantle, run and corner reminder.

Regression passed: full seven-realm Normal ending/save route; core movement/contact/save/slots/debug checks; controller wheel and combo suite; protected prologue/Emperor ending and NG+ fixtures; all three wolf held blasts and companions; extended beast combat/Dragon controls; final balance/platform fixtures; focus/disconnect safety and flush-corner layout; five native Canvas viewport layouts; audio scheduling. Mixed-form soak completed 47,073 gameplay steps with nine expected deaths/respawns and all six forms plus Ninja, without reported assertions.

Real browser CSS, physical controller/phone feel, audible device playback and GitHub upload remain unverified. Native motion/render tests do not prove hardware frame rate or human difficulty. Approved raster art and prior content were preserved; the new cloak/stride effects are drawn in Canvas.

## Earlier verification records

# Pass 5 / 5 — Final Balance verification

## Final balance changes
Normal ordinary-enemy health multipliers by realm are 1.00 / 1.02 / 1.04 / 1.06 / 1.08 / 1.10 / 1.12. A grunt ranges from 46.36 to 51.9232 HP, before existing difficulty/NG+ settings. Attack damage, move speed, warning durations and spawn cap do not rise with this multiplier. Normal 14-base-damage contact still removes 16 HP in both realm 1 and realm 7; immediate repeated crowd hits are blocked by existing invulnerability. Guardian NG+ health scaling is now consistent at 12% per cycle.

Archer/ghost world shot origin regression tests cover both facings and nonzero map heights. Separate 20-second no-defense, base-100-HP fixtures confirm all six sampled enemy roles can damage the player. First damage arrived in 0.83–1.90 seconds after their chase began; ranged fixtures left 16 HP (archer) and 28 HP (ghost) after 20 seconds. These are deliberately undefended threat checks, not human difficulty estimates.

Real boss physics fixture launches a leap from floor height 2208 and lands on a one-way ledge at 2016, with peak rise 236.25. No position warp or forced landing is used. Impact fixture confirms a player on the floor 192 units below is safe while an overlapping player at landing height is damaged. Emperor seal tests verify the captured elevated target height, warning geometry and damage rectangle agree. Late windup-facing commitment checks cover grunt, rival, samurai and oni.

## Final regression coverage
Executed shipped JavaScript under Node/native Canvas with emulated DOM/storage and synthetic keyboard/touch/controller input. Full seven-realm Easy, Normal, Hard and Normal New Game+ campaigns reached clear states and saved the Emperor ending. Campaign controls do not directly set enemy HP, force kills or enable God mode, but have exact entity/terrain information.

Also passed: eight optional guardian duels; all five pass-specific fixtures; starter rise/500-cost triple jump and spirit progression; contact/damage/cooldown/save migration/slot/debug backup checks; protected prologue loan, tutorial, theft, true ending and linear NG+; companion repeat/recall and wolf two-second charges through hit pauses/menu pause; six-second elemental trails/bridge/drop-through/expiry; frozen-shell and thaw; Dragon reach, burst and lightning; controller wheel and forward-forward attack; focus/disconnect/hidden-page input safety; flush-corner move panel and shortcut separation; bounded refit work; original art fallback (all 30 sprites); five native Canvas viewport layouts; audio graph/scheduling and original score checks.

Final mixed-form soak completed 47,279 gameplay steps with seven deaths/respawns, all six beast forms plus Ninja, peaks of 15 enemies / 352 particles / 60 effects / 15 projectiles. A death is an expected gameplay event in this fixture, not a failure.

## Limits
Real-browser CSS, physical phone/controller feel, audible device playback/mixing, notch behavior, offline installation and GitHub upload remain unverified. Native renders and synthetic input do not establish hardware FPS or guarantee human difficulty. There are no known failing targeted automated checks in this build.

## Earlier pass records

# Pass 4 / 5 — Corner and Control verification

New tests executed actual JavaScript using native Canvas and synthetic DOM/input. For Ninja and all six beast forms at three desktop aspect ratios, recorded drawing rectangles confirm the move box ends exactly at canvas width and height, and the seven-icon shortcut ribbon stays to its left. Reviewed a native rendered palace fight with the panel at the corner. Touch-mode fixture confirms the panel remains hidden.

Input checks: blur clears pending actions and partial companion/wolf charges; hidden page and controller disconnection pause; visibility restoration does not auto-resume; holding controller attack through focus loss cannot fire until released; holding RT cannot open the wheel or transform on return. Resize test issues 100 refit bursts and confirms at most six additional settle timers; unchanged-size fit preserves Canvas state. Cosmetic test confirms a distant particle skips drawing while remaining in the simulation.

Passed regression: full seven-realm Normal ending/save route; 47,584-step mixed-form soak with four respawns; core touch/keyboard/synthetic-controller movement and saves; RT wheel and forward-forward attack; companion resummoning and all wolf two-second charges through hit pauses/menu pause; elemental trails and bridge collision; prologue/Emperor/NG+; Pass 1 combat/audio scheduling; Pass 3 guardian/boss fixtures. Five native Canvas viewport fixtures cover desktop, phone landscape and portrait.

Real browser CSS layout, notch/safe-area behavior on hardware, physical controller/phone input, audible device mixing, offline installation and GitHub upload remain unverified. Simulation timings are not hardware frame-rate measurements. Earlier Hard/NG+ campaign checks belong to Pass 3; this pass changed presentation/input interruption handling rather than balance.

## Previous pass records

# Pass 3 / 5 — Read the Storm verification

The shipped JavaScript ran in Node/native Canvas with emulated DOM/storage and synthetic input. New tests cover combo warning/facing commitment; warning floors through all three phases; phase queue cleanup and contact-free regroup; 100 legal boss move selections with minions capped and targets out of melee range; all five ranged guardian signatures in both directions; actual third-action windup with locked aim; damaging projectile collisions and avoidance fixtures. Native boss scene reviewed for visual readability; elemental projectiles rendered through the real drawing code.

Regression checks passed: seven-realm Normal campaign, Hard campaign with alternate seed, Normal New Game+ ending/save path; eight Ninja/Bear optional guardian duels; companion recall and wolf charge through hit pauses/menu pause; core movement/input/contact/save migration; sequel/prologue/ending/NG+; all spirit doors/controller wheel; Pass 1 extended combat and audio scheduling; elemental trails/tutorial; five native Canvas viewport layouts. Mixed-form soak completed 47,584 gameplay steps with four respawns, all six beast forms plus Ninja, no reported assertions.

The campaign controller has exact world/attack information, so these results prove progression paths rather than human difficulty. Avoidance fixtures place the player outside a projectile path; they do not measure human reaction time. Real browser CSS, physical phone/controller behavior, audible playback/mixing, offline installation and GitHub upload remain unverified. No hardware frame-rate claim is made.

## Previous pass records

# Pass 2 / 5 — Spirit Recall verification

Executed current shipped JavaScript with Node/native Canvas and synthetic inputs. New checks cover initial summon, active recall, immediate resummon, one call per hold, no mastery gain from active recalls; all three wolf blasts at 120 fixed 60Hz steps even under continuous hit freeze; controller X with a five-second menu pause excluded from charge. Passed prior mouth, elemental trails, Pass 1 combat/audio, core controls/save/migration, sequel/prologue/NG+, spirit doors, eight optional guardian duels, five native Canvas viewport layouts, and the full seven-realm Normal legal-input campaign. Mixed-form soak completed 47,584 gameplay steps with four respawns and no reported assertions.

Real browser CSS, physical controller/phone behavior, audible mixing, offline installation and GitHub upload remain unverified. Native simulation does not measure hardware frame rate or establish human difficulty.

## Preserved Pass 1 verification

# Beast Shinobi 2 — Improvement Pass 1/5 verification

## Method and limits
The shipped JavaScript was executed in Node 24 with native Canvas image decoding/rendering and an emulated DOM, save storage and input layer. Controller tests use synthetic Xbox-standard axes/buttons through real input polling. Audio graph/playback state was tested with recording Web Audio and media-element doubles; actual MP3 files were separately encoded, decoded and numerically analyzed. Actual browser CSS, physical phone/controller input, audible device playback/mixing, GitHub commit and offline installation remain unverified.

## Combat changes
- Wolf strikes reach 156 world units; finishers reach 180. Ice-blue, fire-red and electric-gold claw effects launch during the active attack window. Targets in the extended range take damage; repeated active-frame checks do not multiply hits. Both facing directions passed. Wolf attacks still do not restore beast energy.
- Dragon normal attacks manifest a large fiery hand/talons. The two-strike combo reaches 230 / 270 units. Native renderings reviewed; forearm attachment and talon silhouette were revised during review. Solid walls limit both effective strike reach and the visible extension.
- Dragon fire special lasts 0.62 seconds, replacing 1.5 seconds. It emits a bounded short burst while allowing steering; movement fixture traveled 223 units across its action/recovery test rather than rooting the player. A late repeat press can queue the next burst; transforming or respawning cannot turn that queue into an unintended Ninja jutsu.
- Dragon lightning reaches at most 540 units, has 0.2-second action recovery and a 0.48-second cooldown. It retains mouth-anchored emission and terrain limits.
- Eight facing/form strike fixtures checked actual extended damage, active-window hit caps, effect identity and wolf energy rules. Separate fixtures checked wall blocking, Dragon combo, movement, projectile budget and buffered-input safety.

## Audio
Three original score loops shipped: exploration 43.636 seconds at 88 BPM; battle 32 seconds at 120 BPM; boss 26.667 seconds at 144 BPM. The decoded MP3 peaks were 0.693, 0.692 and 0.698 respectively, with no nonfinite samples or clipping. Combined audio files are about 821 KB.

Audio logic fixtures passed: exploration/battle transitions, inactive-track stopping, pause/hidden-tab silence, mute/resume, no repeated inactive restarts, Web Audio gain routing for hosted playback, missing-file synth fallback, real-click autoplay recovery control, sword/element effect scheduling, effect rate limits and node disconnection after stopping.

Fixed a scheduler backlog after long mute/background pauses. Tests advanced audio time by two hours and verified bounded future scheduling. Media tracks are primed from user gestures. On hosted pages their gains route through Web Audio and a limiter; local-file playback retains direct media volume control. These tests do not establish real-device loudness or audible quality.

## Broader regressions
- Core keyboard/touch/synthetic-controller sprint, multitouch release, save migration, starter rising slash, 500-coin Triple Jump, finisher damage cap, dash recovery, boss contact, streaming, save-slot/debug isolation, respawn and menus passed.
- Six-form roster, Bear reward, four optional guardian doors, reward/return/death state, independent wolf unlocks, RT tap/hold wheel, controller dash attack, Y beast-special/Ninja-clone mapping and desktop reminder checks passed.
- Prologue borrowed-power protection, seven skippable lessons, actual sanctuary route, Emperor power theft, original-ending continuation, palace, true victory persistence and linear New Game+ passed.
- Wolf two-second mouth attacks, element statuses, hold latches, energy cost, interrupts, wall blocking, no pet-input conflict, mouth anchors and actual synthetic-controller X charging passed. Six-second ice bridges, other elemental trails, airborne dash, expiry/drop-through, hazard cooldowns and freeze/shatter visuals passed.
- Automated input controllers cleared all seven realms on Easy, Normal and Hard, and completed Normal NG+. Optional guardian fixtures also won eight real-combat duels with Ninja and Bear. Campaigns/duels used ordinary HP/damage/energy and legal moves; no god mode, forced kills or level warps. Controllers know exact entity/telegraph state, so completion does not establish ordinary-player difficulty.
- Mixed-input stress: 47,794 gameplay update steps, two deaths recovered, all six beasts and Ninja observed. Peaks: 12 enemies, 369 particles, 57 effects, 15 projectiles. No nonfinite positions or resource values.
- All 30 sprite definitions recovered when external art was intentionally failed. All 687 registered frame references stay in image bounds and match animation counts. Canvas sizing/rendering checked at 1366×768, 1920×1080, 844×390, 915×412 and 390×844.

## Package
Complete ZIP with root index.html and every runtime image/audio asset, no split STEP folders, no test saves or QA screenshots. Runtime/cache references and archive integrity checked. Under 100 files and 25 MB extracted. Previous full-game checkpoint preserved.
