# Beast Shinobi 2 — The Emperor’s Seal

Complete downloadable HTML/JavaScript action game. Seven campaign realms plus a shorter playable prologue. No build step or external CDN.

## Put it on GitHub
Extract Beast-Shinobi-2.zip. Open the extracted folder and drag EVERYTHING INSIDE it, including index.html and the assets folder, onto the upload page at your GitHub repository root. Wait until all files finish uploading, then Commit changes. Replace matching files. Do not upload the ZIP or an extra enclosing folder. No split STEP folders. Existing older PNG files can remain; this version uses the included WebP artwork.

## New campaign
Start a new empty save slot to play Wild Fang Sanctuary with every remaining form, jutsu, companion, upgrade and Awakening. Seven brief, skippable pauses teach movement, sword/dash, clone/chain, the six forms, jutsu/element trails, companions and Awakening. You can practice freely against harmless training echoes. At the gate the Shinobi Emperor teleports down, seals your powers, and begins the original six-realm recovery journey.

The original Shogun ending now reveals the higher throne. Enter the seventh realm, Emperor’s Palace: a gilded approach with two battle courts and a new three-phase final boss, Raizen. Watch his seal marker, projectile crown and delayed judgment strikes, then punish recovery windows. Beat him and reach the exit gate for the true victory page.

Legacy saves keep their progress and upgrades. A save already past the Shogun can enter the new palace without replaying the prologue. Temporary prologue powers are never written into normal save progress. Leaving/reloading training restores the prior loadout.

## New Game+
Unlocked only by defeating the Emperor and clearing his realm. The confirmation explains that this slot’s realm progression will reset. All beast forms, jutsu, companions, Awakening, upgrades, coins and mastery carry over. The prologue is skipped, so your powers are not stolen again. Only the CURRENT uncleared realm can be selected; past and future realms stay locked during that cycle. Enemy and boss health increases 12% per cycle. Other save slots stay separate.

## Controls
A/D or arrows move; double-tap and hold a direction to sprint. Space/W jumps and double-jumps; toward a wall + jump wall-jumps. Down + jump drops through one-way platforms. J attacks; down + attack in air plunges. Shift/L dashes. R summons a shadow clone (8 jutsu energy). F binds foes with the chain. Q plus direction casts jutsu; Z changes equipped jutsu. M opens forms; Tab cycles; 1–6 select Bear, Kitsune, Fire Wolf, Electric Wolf, Ice Wolf and Dragon. Hold ATTACK for three seconds to call hawk/snake companions after unlocking them. H triggers Awakening with full jutsu energy. P/Escape pauses. Touch and controller mappings are listed inside Beasts & Controls.

The Haunted Temple’s human enemies are now skeletal/undead versions of themselves. Misty Mountain retains its mixed living/undead patrols. Wolves retain finite beast energy and six-second elemental trails. Ice Wolf’s ice path is a solid temporary bridge.

## Hidden developer tools
Tap the subtitle on the title screen (or PAUSED) five times within 2.5 seconds, then enter 2057. Realm jumps now include the Emperor’s palace. Debug tools use per-slot backups; restore the original save from the debug menu after testing.

## Validation
See QA_REPORT.md for tests and remaining verification limits. Native Canvas rendering and automated simulation are not physical phone/browser testing.

## Spirit Doors v2 changes
Gorilla and Rhino are removed from the roster, wheel, prologue and shipped sprite definitions. Old saves keep their other powers, upgrades and coins. Previously implicit Fire/Electric Wolf unlocks are retained for legacy saves; new saves unlock each wolf separately.

| Beast | New-game unlock |
| --- | --- |
| Bear | Reward at the end of level 1 |
| Kitsune | Optional door midway through level 2; defeat Kitsune inside |
| Fire Wolf | Optional door before level 2’s boss; defeat the guardian |
| Electric Wolf | Optional door before level 3’s boss; defeat the guardian |
| Ice Wolf | Optional door before level 4’s boss; defeat the guardian |
| Dragon | Existing guardian near the end of level 5 |

At a spirit door, press UP on keyboard/controller or tap ENTER TRIAL on touch. Return through the left door after victory; you can retreat without earning the form. Dying sends you to the main realm checkpoint. Trials preserve the outside world’s live state while you are inside.

Controller RT: tap to toggle the last picked beast; hold for 0.26 seconds to pause the world and open the wheel, point the stick or D-pad at the desired form, then release RT to select it. B cancels. The last chosen beast is remembered in the save. Forward, neutral, forward + X within the input window performs a dash attack. It also accepts X just after releasing the second forward. UP + X remains the rising slash.

Ninja starts with one rising slash before landing, including old saves; dojo upgrades add more. Triple Jump costs 500 coins. Dragon’s B / DASH move is aimed mouth lightning; Y / SPECIAL retains fire breath. Desktop players see a current-form move reminder at bottom right with keyboard or controller labels. It is hidden on phone/touch devices.

## Stormfire v3
- Move reminders sit 16 canvas pixels lower and still appear only on desktop.
- Dragon is now the larger Stormfire Dragon, with dark sapphire armor, gold horns, broad wings and stronger claw, lightning and fire-breath damage. Lightning and fire originate at measured mouth points in the active casting pose, mirrored correctly when facing left.
- Ice, Fire and Electric Wolves: hold ATTACK (controller X) for TWO gameplay seconds to cast an elemental mouth attack. Ice freezes, fire burns, electricity shocks. Each cast spends 12 beast energy and fires once per held press; release ATTACK before charging another. Damage/hurt, dashes and form changes interrupt charging. Solid terrain blocks the breath. Existing elemental dash trails remain intact.
- Controller Y summons a clone as Ninja and uses the form’s special while transformed. LB remains an alternate special input. RB is the Ninja chain. Wolf held attacks are reserved for breath rather than companion summoning; return to Ninja or another form to call companions.

## Improvement Pass 1 of 5 — Wild Fang Combat
The wolves now have longer elemental claw strikes: icy blue, fire red and electric gold. Their extended reach matches damage collision and stops at solid walls. Dragon’s normal attack is a two-strike manifested fire hand with long talons; the finisher reaches farther than the opener.

Dragon’s Y / SPECIAL is now a 0.62-second steerable fire burst instead of the old 1.5-second channel. You can keep flying during the burst, and a late repeat press is buffered safely. B / DASH lightning has a shorter 540-unit reach, 0.2-second recovery and quicker cooldown. Mouth emission stays attached to the correct sprite pose.

Three original music loops accompany exploration, battles and bosses, with shamisen-style plucks, breathy flute, wood percussion and taiko-style drums. Sword swings/impacts, icy claws, burning claws, electric claws and Dragon attacks have distinct sounds. Sound ON/OFF controls all audio. If a browser requires a gesture, tap/click the small enable-sound button. Music pauses with the pause menu or hidden tab. Offline playback uses the included audio files; a synthesized fallback remains if a music file cannot load.

Four requested improvement passes remain. This download is the full playable Pass 1 game, preserving previous progression, forms, rooms, prologue, Emperor finale and New Game+.

## Pass 2: companion recall
Once companions are unlocked, hold ATTACK for three seconds in Ninja or a non-wolf form. Release and hold again whenever you want: active companions return beside you with refreshed lifetime; expired companions can be summoned immediately. Wolves reserve held ATTACK for their two-second elemental mouth blast. Brief combat hit pauses count toward both charges; menus and tutorials do not.

## Pass 3: reading guardian attacks
Bosses show move names and windup progress. Ground arrows mark the direction of melee attacks and rushes; they are directional warnings rather than exact hitboxes. OPENING marks recovery; EXPOSED marks increased vulnerability. Phase changes give a short regroup. Spirit guardians periodically charge elemental shots: move out of their target line or interrupt with a heavy attack.

## Pass 4: controls and corner layout
The computer moves box sits flush in the lower-right game corner; form shortcuts fit beside it. Switching tabs, losing focus or unplugging a controller pauses play. Resume explicitly, and release held controller buttons/triggers before the next action. Partial charge attacks reset on focus loss. Touch buttons account for device safe-area insets; form wheel targets have larger minimum dimensions.

## Five-pass final build
Later realms use heavier enemy mixes, boss phases and a gentle ordinary-enemy health curve (2% per realm, up to 12% extra at the palace). Their attack damage was not increased for this curve. Archers and ghosts now fire from the correct world position. Bosses can pursue reachable platforms; landing and Emperor seal damage respect platform height. Easy, Normal and Hard remain selectable on the title screen.

## Stormstep Awakening
Super-powered Ninja now has six additional midair jumps after the initial ground jump and much faster running/sprinting. Double-tap a direction and hold for the fastest sprint. Forward-neutral-forward + ATTACK performs a dash strike on the ground or in midair (controller X; keyboard J; touch attack). Its motion keeps gravity. The normal run has faster leg animation and motion echoes; Awakening adds a streaming spirit cloak and lightning accents.
