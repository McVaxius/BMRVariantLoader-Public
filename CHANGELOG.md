# Public changelog

Only content marked Public is listed. Entries describe released versions unless marked Upcoming; encounter improvements do not imply a verified live clear.

## 3.1.3.42 - 2026-11-09

- P10S Silkspit: marked players now clear nearby pillars while retaining player-spread avoidance and native floor hazards.
- Preserve the mechanic's existing timing and avoid duplicate guidance on newer native hosts.

**In progress**

- P9S comet protection, P11S tether preparation and Zodiark EX splash isolation across supported host versions.

**Queued (approved; evidence gaps remain)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.

## 3.1.3.41 - 2026-11-09

- Yiazmat's held-add target preference now follows the active encounter provider and Current/Old selection.
- Preserve manual/support targeting, forced targets and native encounter priorities when providers change.
- Added reviewer explanations for scripted-quest pull safeguards and False Idol phase compatibility; their behavior is unchanged.

**In progress**

- Further Endwalker and Shadowbringers encounter guidance.

**Queued (approved; evidence gaps remain)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.


## 3.1.3.40 - 2026-11-09

- Updated shared text controls and glass rendering to the reviewed AethertekUI 0.3.1 baseline.

**In progress**

- Reviewing encounter-specific targeting ownership.

**Queued (approved; evidence gaps remain)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.

## 3.1.3.39 - 2026-11-08

- Removed GMC's legacy combined mini window and drawing callback, avoiding theme-scope errors in native GodMod.
- Added module state and selection actions for GodMod's updated native mini while preserving saved choices and between-pull safeguards.
- Preserve native BMR windows and GMC's encounter browser and module settings.

**In progress (unreleased, partial)**

- Native GodMod mini integration and Crewcible shared-state support.

**Queued (approved; evidence gaps remain)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.

## 3.1.3.38 - 2026-11-08

- Crewcible: recover with the best remaining eligible team across all five boards while retaining available planned familiars.
- Preserve battle progress through team recovery and refreshed plans; use each encounter's own cooldown plan.
- Correct recovery setup for Siren and Guttler encounters.

**In progress (unreleased, partial)**

- Move all compact-mini controls into native GodMod, with module state and selection actions supplied by GMC.
- Native GodMod Crewcible shared-state integration.

**Queued (approved; evidence gaps remain)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.

## 3.1.3.37 - 2026-11-08

- Improved native PvP control for MOM during busy AI frames, reloads and manual preset changes.
- Crewcible: needed scripted familiar heals can proceed through burst and affinity holds while preserving command checks.
- Preserve GodMod's native Crewcible rotation registrations instead of creating duplicate entries.
- Release uploads now contain only the runtime ZIP and plugin manifest.

**In progress (unreleased, partial)**

- Native GodMod Crewcible shared-state binding and lifecycle handling.

**Queued (approved)**

- Seven Shadowbringers Extreme boss/arena foundations and first mechanic slices.

## 3.1.3.36 - 2026-11-08

- P6S: added Transmission cone avoidance and facing guidance, with clean recovery after death and combat reset.
- P8S phase 2: added movement into the native-assigned active Limitless Desolation tower while preserving spread handling.

**In progress (unreleased, partial)**

- Native GodMod compact controls and rotation integration.
- MOM native PvP ownership handoff and Crewcible difficulty-3 resource/recovery improvements.

## 3.1.3.35 - 2026-11-08

- Improved GodMod/BMR selection and cleanup while preserving the chosen backend when AI is stopped.
- Added Current/Old labels and shared module selection for the native GodMod mini.
- Preserve native Dhog healer/PvP rotations and MOM state when available.
- Native-capable GodMod handles engagement; older hosts retain GMC targeting.

**In progress (unreleased, partial)**

- Native GodMod compact controls and rotation integration.
- Remaining approved DevHub fixes before encounter work resumes.

## 3.1.3.34 - 2026-11-07

- Shiva Savage: improved Reflections light-orb assignments and Thin Ice movement guidance.
- Barbariccia Extreme: added guidance around other players' Secret Breeze cones.
- Eden's Gate: Descent (Savage): added Empty Hate knockback-resistance support.

**Further work paused**

Public encounter support remains partial. Further encounter automation is paused.

## 3.1.3.33 - 2026-11-07

- Added Pandaemonium Savage Meltdown positioning guidance using the observed stack and spread targets.

**In progress (unreleased, partial)**

- Barbariccia Extreme: Secret Breeze movement guidance.
- Further Public Savage encounter automation.

## 3.1.3.32 - 2026-11-07

- Added Zeromus Extreme Bonds of Darkness separation guidance for current tether pairs.

**In progress (unreleased, partial)**

- Barbariccia Extreme: Secret Breeze movement guidance.
- Further Public Savage encounter automation.

## 3.1.3.31 - 2026-11-07

- P8S Footprint positioning now considers projected knockback landings against current arena bounds, including any holes.

**In progress (unreleased, partial)**

- Zeromus Extreme: Bonds of Darkness guidance.
- Barbariccia Extreme: Secret Breeze movement guidance.
- Shiva Savage: Reflections light-orb ownership.

## 3.1.3.30 - 2026-11-07

- Retired stale Her Inflorescence Energy warnings when their source disappears or is replaced.
- Added Menphina Thin Ice guidance from current statuses.
- Improved Compound 2P phase handoff when its second actor has not arrived yet.
- Added guidance to separate a currently linked Connla from Scathach.

**In progress (unreleased, partial)**

- Hephaistos Savage: Footprint knockback landing guidance.
- Zeromus Extreme: Bonds of Darkness guidance.
- Barbariccia Extreme: Secret Breeze guidance.
- Shiva Savage: Reflections light-orb ownership.

## 3.1.3.29 - 2026-11-07

- Added guidance for Scathach's current Shadethrust casts.

**In progress (unreleased, partial)**

- Scathach: Connla separation.
- Hephaistos Savage: Footprint knockback landing guidance.
- Zeromus Extreme: Bonds of Darkness guidance.

## 3.1.3.28 - 2026-11-07

- Added Agdistis Savage Minotaur tether bait guidance for observed targets.
- Added Red Girl Shock positioning in phase two near walls of the opposite colour.
- Added a preference to move farther from the arena center during Construct 7's current Lithobrake cast.

**In progress (unreleased, partial)**

- Scathach: Shadethrust guidance and Connla separation.
- Her Inflorescence: Energy warning cleanup.
- Menphina: Thin Ice movement guidance.
- Compound 2P: phase handoff handling.

## 3.1.3.27 - 2026-11-07

- Added Construct 7 Ignite cast guidance for the current frontal attack.

**In progress (unreleased, partial)**

- Agdistis (P7S): Minotaur tether bait guidance.
- Red Girl: Shock hazard guidance.
- Construct 7: Lithobrake guidance.
- Further Scathach, Compound 2P and Her Inflorescence coverage.

## 3.1.3.26 - 2026-11-07

- Improved Red Girl intermission arena and wall mapping for participants in their current rooms.
- Added repeated Scathach Thirty Cries stack guidance, including updates as the marked target moves.

**In progress (unreleased, partial)**

- Agdistis (P7S): Minotaur tether bait guidance validation.
- Construct 7: Ignite cast guidance.
- Further Scathach and Red Girl encounter coverage under review.

## 3.1.3.25 - 2026-11-07

- Added Themis (P11S) Dismissal knockback landing guidance using current arena bounds, hazards due by impact and current knockback immunity.

**In progress (unreleased, partial)**

- Scathach: observed Thirty Cries shared-stack assistance.
- Agdistis (P7S): Minotaur tether bait guidance.
- Red Girl: intermission arena and wall mapping.
- Construct 7: Ignite lifecycle cleanup.

## 3.1.3.24 - 2026-11-07

- Improved Explosion timing and cleanup for observed Magic Bullets in Hansel and Gretel.
- Preserved existing separation, shield and tank guidance.

**In progress (unreleased, partial)**

- Scathach: observed Thirty Cries shared-stack assistance.
- Themis (P11S): Dismissal knockback landing guidance.
- Agdistis (P7S): Minotaur tether bait guidance.
- Red Girl: intermission arena and wall mapping.

## 3.1.3.23 - 2026-11-07

- Restored Nophica March guidance when directional statuses are already present at phase activation.
- Added Barbariccia Extreme partner allocation for current Upbraid stacks, preserving containment and landing guidance.

**In progress (unreleased, partial)**

- Hansel and Gretel: Explosion lifecycle cleanup.
- Scathach: observed Thirty Cries shared-stack assistance.
- Themis (P11S): Dismissal knockback landing guidance.

## 3.1.3.22 - 2026-11-07

- Added ordinary tower pair assignments, personal highlighting and text guidance for Proto-Carbuncle Savage.
- Added Ramuh Savage ground AoE guidance for current Shock Strike casts.

**In progress (unreleased, partial)**

- Nophica: March recovery after late activation.
- Barbariccia Extreme: partner guidance.
- Proto-Carbuncle Savage: further tower execution.
- Ramuh Savage: further Thunderstorm execution.

## 3.1.3.21 - 2026-11-06

- Adjusted Rubicante Extreme Total Immolation stack guidance for the eligible party members present.
- Preserved the forced stack target, spread exclusions, mechanic areas and cast timing.

**In progress (unreleased, partial)**

- Nophica: March recovery after late activation.
- Barbariccia Extreme: partner guidance.
- Proto-Carbuncle Savage: tower pairing.
- Ramuh Savage: ground AoE handling.

## 3.1.3.20 - 2026-11-06

- E4S Titan now stops adding legacy tile assignments after a confirmed blue marker and shows a manual-handling notice until reset.
- Preserved other mechanic hints; blue tile allocation remains manual.

**In progress (unreleased, partial)**

- Nophica: March recovery after late activation.
- Barbariccia Extreme: partner guidance.
- Proto-Carbuncle Savage: tower pairing.
- Ramuh Savage: ground AoE handling.

## 3.1.3.19 - 2026-11-06

- Added Hydaelyn Extreme guidance for Lightwave, Parhelion, Crystallize and Spectrum/Arc, with stack guidance based on the current party.
- Added P4S Pinax current-cast hazard guidance and water-knockback preparation.

**In progress (unreleased)**

- Further Public Extreme, Savage and alliance automation.

## 3.1.3.18 - 2026-11-06

- Added Zodiark Extreme movement guidance for Adikia, Algedon, Exoterikos, Paradeigma and Astral Eclipse, plus reduced-party Styx participation.
- Added Innocence Extreme current-cast warnings, add priorities and party-damage forecasts.

**In progress (unreleased)**

- Further Public Extreme, Savage and alliance automation.

## 3.1.3.17 - 2026-11-06

- Improved Auto targeting during Yiazmat's add phase to prefer the Archaeodemon currently held by the player when the adds have distinct observed holders.
- Preserved existing objective priorities and target restrictions.

**In progress (unreleased)**

- Further encounter movement and Extreme trial support.

## 3.1.3.16 - 2026-11-06

- Added Endsinger Extreme Twinsong guidance for cone, circle and donut hazards.
- Added rewind preparation from observed head casts and ring markers, with cleanup as casts resolve or change.

**In progress (unreleased)**

- Further encounter movement and Extreme trial support.

## 3.1.3.15 - 2026-11-06

- Removed stale Rhalgr Shock forecasts when the current Lightning Orb is destroyed, including before its cast starts.
- Preserved replacement-orb hazards and unrelated warning fields during cleanup.

**In progress (unreleased)**

- Further encounter movement and Extreme trial support.

## 3.1.3.14 - 2026-11-06

- Revised difficulty 3 beast teams and cooldown plans across all five Crewcible boards.
- Improved add burst, beast retention and protection, and Geshunpest sustain decisions.
- Added ready-beast continuation and refined Pas mage targeting and bomb delivery.

**In progress (unreleased)**

- Further encounter movement and assignments.

## 3.1.3.13 - 2026-11-06

- Prioritized Yiazmat's Archaeodemons and Heart during intermission while preserving mechanic target restrictions.

**In progress (unreleased)**

- Crewcible difficulty 3: beast retention, sustain and five-board cooldown-plan verification.
- Further alliance mechanics and GodMod PvP/MOM lifecycle verification.

## 3.1.3.12 - 2026-11-06

- Added Dhog PvP rotations for all 21 jobs and GMC-side support for MOM's native rotation handoff.
- Improved Golbez Extreme's Double Meteor tower assignments and knockback launch positioning.
- Kept Yiazmat's Dust Storm warnings active until the damage arrives.
- Added matching Public module-pack source and licence files to the release.

**In progress (unreleased)**

- Yiazmat heart and required-add targeting.
- Crewcible difficulty 3: five-board beast teams, sustain, handoffs and cooldown-plan verification.
- Further alliance mechanics and cross-host PvP/MOM verification.

## 3.1.3.11 - 2026-11-06

- Dhog healer rotations now consider eligible Duty Support and Trust NPC allies for healing and game-permitted raising.
- One GMC package now supports active GodMod or BossModReborn, with a matching bundled module pack for each host.
- Improved backend reload cleanup, cooldown-plan discovery and zone-module replacement while preserving provider ownership.

**In progress (unreleased)**

- Further Copied Factory mechanic and recovery improvements.
- Crewcible difficulty 3: five-board beast teams, sustain, handoffs and cooldown-plan verification.
- PvP rotations for all 21 jobs and MOM integration, including source and licence packaging.

## 3.1.3.10 - 2026-11-05

- Auto targeting now acquires eligible enemies when an autorotation preset is active without movement AI.
- Improved switching to priority adds and reacquiring enemies after temporary untargetability while preserving encounter and manual targeting rules.

**In progress (unreleased)**

- Dhog healer rotations: healing and raise eligibility for duty NPC allies.
- Crewcible difficulty 3: five-board beast teams, sustain, handoffs and cooldown-plan verification.
- PvP rotations for all 21 jobs, including integrated source and licence packaging.

## 3.1.3.9 - 2026-11-05

- Added configurable Auto, Manual and Support targeting, engagement rules and target ordering in GMC.
- Improved target reacquisition after resurrection when enemies in a duty remain in combat without player aggro.

**In progress (unreleased)**

- Crewcible difficulty 3: five-board beast teams, sustain, handoffs and cooldown-plan verification.
- PvP rotations for all 21 jobs, including integrated source and licence packaging.

## 3.1.3.8 - 2026-11-05

- Preserved assigned targets during Red Girl's intermission instead of switching to a nearer enemy.
- Restored BMR's native settings, autorotation and AI presentation. GMC retains its own appearance controls and encounter browser.

**In progress (unreleased)**

- Crewcible difficulty 3: five-board beast teams, sustain, handoffs and cooldown-plan verification.
- PvP rotations for all 21 jobs, including integrated source and licence packaging.
- RSR-style GMC targeting controls with Auto as the default.

## 3.1.3.7 - 2026-11-05

- Improved Hansel and Gretel separation when one boss loses Stronger Together before the other.

**In progress (unreleased)**

- Crewcible difficulty 3: implementing the approved five-board beast teams, sustain, handoffs and cooldown-plan updates.
- PvP rotations: settings/editor integration for all 21 jobs, plus source and licence packaging within the GMC release.
- Further alliance encounter improvements.

## 3.1.3.6 - 2026-11-05

- Added `/gmc` to open GMC, sharing the existing module-window commands.
- Improved Knave of Hearts knockback landing safety when several current Colossal Impact areas overlap the landing route.

**In progress (unreleased)**

- PvP rotations: native action registration, settings and editor integration for all 21 jobs.
- Crewcible difficulty 3: concrete board strategies, beast handoffs and repeatable sustain without required random loot.
- Further alliance and Endsinger mechanic improvements.

## 3.1.3.5 - 2026-11-05

- Added optional duty enemy engagement with an on/off control, availability/error status, and protection for scripted stealth and encounter target restrictions.
- Improved Endsinger Extreme positioning for paired tankbusters, stacks, Grip, Endsong and planet mechanics.
- Added Endsinger damage forecasts and personal Despair guidance. Full encounter automation and live-clear validation remain incomplete.

**In progress (unreleased)**

- PvP rotations: all 21 job policy ports are written; native action, targeting and settings integration is being verified.
- Crewcible difficulty 3: comparing documented clears, beast teams and sustain plans, with random-loot dependencies called out.
- Further Endsinger tower/rewind work and end-to-end encounter validation.

## 3.1.3.4 - 2026-11-05

- Improved Amon's ice shelter, required-add targeting and bomb-cleanse guidance. Broader encounter automation remains incomplete.

## 3.1.3.3 - 2026-11-05

- Added compact combined AI and autorotation controls with preset and cooldown-plan drawers.
- Added global and per-encounter Current/Previous module selection, applied between pulls while preserving existing plans and provider ownership.
- Added a GMC-only filter to encounter browsing.
- Improved Halone add-phase safe areas, Hansel/Gretel shield-front movement and Hashmal Towerfall warning cleanup.

## 3.1.3.2 - 2026-11-04

- Made all five Crewcible boards Public, including both master boards and their BST strategies, cooldown plans and virtual plans.
- Improved Tower encounter continuation while Meng Zi remains alive.
- Added Elenchos avoidance guidance for Endsinger Extreme. Broader encounter support remains incomplete.

## 3.1.3.1 - 2026-11-04

- Added initial tankbuster and raidwide cast warnings for Hades Extreme. Automated movement and other mechanics remain incomplete.

## 3.1.3.0 - 2026-11-04

- Added Dhog WHM/CNJ, SCH, AST and SGE rotations with automatic healing, cleansing and raising.
- Added recipient and raise strategy options, including assistance outside combat.
- Grouped public custom rotations under Dhog and improved preset-editor reload handling.

## 3.1.2.9 - 2026-11-04

- Added Dust Storm damage preparation for Yiazmat.
- Improved Tower wall assignments, tank selection at arena boundaries and level-80 cooldown-plan support.

## 3.1.2.8 - 2026-11-04

- Added movement guidance for Belias's hand tethers.

## 3.1.2.7 - 2026-11-04

- Added Rake tankbuster warnings for Yiazmat in Ridorana.
- Added party-damage preparation for Engels during Demolish.

## 3.1.2.6 — 2026-11-04

- Added first-Glare warnings for Agdistis Savage.
- Added physical-ranged interrupt hints for Shadowcourt Hound in Dun Scaith.

## 3.1.2.5 — 2026-11-04

- Added Dominion tower assignments in phase two of Hephaistos Savage.
- Added polarity-aware Death Strike stack positioning for Yiazmat.

## 3.1.2.4 — 2026-11-04

- Improved party-damage preparation for Construct 7, Hashmal and Engels.
- Improved required-add targeting in Dun Scaith.
- Added Venomous Mass tankbuster avoidance in Proto-Carbuncle Savage, including pending attacks after the marked target dies.

## 3.1.2.3 — 2026-11-03

- Improved Ridorana Lighthouse polarity positioning, spread-then-stack handling and tankbuster warnings.
- Added Towerfall warnings in Rabanastre and current Pitfall positioning in Dun Scaith.
- Improved Engels add pickup and tank positioning in the Copied Factory.
- Corrected Hydaelyn tankbuster warnings and added current Levinstrike tower guidance in Kokytos Savage.

## 3.1.2.2 — 2026-11-03

- Improved Ashplume positioning in Phoinix Savage and Act 1 tower movement in Hesperos Savage.
- Added resistance-side movement guidance for Hegemone Savage.
- Corrected Pandaemonium Savage stack sizes, plume warnings and encounter startup.
- Improved Barbariccia knockback landings and tether safety.
- Added close Pulverize warnings for Construct 7 and hand targeting in Dun Scaith.

## 3.1.2.1 — 2026-11-03

- Hobbes is now offline-ready for normal combat entry.
- Added phase-two discovery and retry recovery for False Idol and Her Inflorescence.
- Improved early Pyretic preparation for Althyk and Nymeia.
- Corrected Halone tower groups to use players inside the arena.
- Added Construct 7 arithmetic positioning.
- Added initial Ferdiad Hollow mechanic support. Additional mechanics remain incomplete.

## 3.1.2.0 — 2026-11-03

- Completed this round of Puppets' Bunker improvements, including alphabetical Compound 2P tower assignments and tower-failure warnings.
- Improved movement through ordinary Hydrostasis knockbacks.
- Added missing Void Aero III warnings for Deathgaze Hollow.
- Improved Hobbes's remaining laser-hit forecasts.
- Improved positioning for Rofocale's Pomp and Circumstance.

## 3.1.1.7 — 2026-11-03

- Heavy Artillery Unit is now offline-ready for normal combat entry, with improved tower-failure warnings and cleanup.
- Expanded Walking Fortress guidance for tile waves, marked lasers and tank explosions.
- Improved Rofocale positioning after charges.
- Added Deathgaze Hollow spread, Doom and missing Bolt warnings. Additional mechanics remain incomplete.

## 3.1.1.6 — 2026-11-03

- Serial-jointed Command Model is now offline-ready for normal combat entry.
- Added earlier Marx warnings and continuing fire guidance for Engels.
- Improved movement through Hydrostasis knockbacks and continuation after Althyk dies.
- Added initial Rofocale arena and mechanic support. Later mechanics remain incomplete.

## 3.1.1.5 — 2026-11-03

- Improved Superior Flight Units' line stacks, missile warnings and activation during a cast.
- Improved Hobbes's missile-spread positioning during cargo knockbacks while preserving damage and spread warnings.
- Added Engels tower assignments and continuing head-laser guidance.
- Made Althyk and Nymeia's accelerated line warnings more preemptive.

## 3.1.1.4 — 2026-11-03

- Improved Aegis damage warnings for Flight Unit explosions.
- Added earlier positioning for Walking Fortress's opening carpet attacks.
- Improved healing preparation for Nald'thal's marked cone targets.

## 3.1.1.3 — 2026-11-03

- Kept Nophica's active tankbuster guidance through marked-player deaths or untargetability.
- Added Red Girl wall, meteor and forced-movement guidance, including alphabetical assignment when two wall choices remain.
- Corrected movement to transferred towers in Compound 2P.

## 3.1.1.2 — 2026-11-03

- Improved Azeyma's later mechanics and repeat handling.
- Expanded movement and assignment guidance across Myths of the Realm and NieR alliance encounters; several encounters still have incomplete mechanics.
- Added Shinryu Unreal mechanic and NPC-healing assistance. Automated bridge traversal remains incomplete.
- Improved direct approach to the Infernal Nail and living-player selection in supported Eden, Omega and chaotic-raid mechanics.
- Improved Memoria Misera timeline support and recovery between attempts.

## 3.1.1.1 — 2026-11-03

- Improved Byregot's hammer-floor movement, later mechanic coverage and recovery between attempts.

## 3.1.1.0 — 2026-11-03

- Completed this round of Thaleia improvements, adding Angelos interrupt guidance and continued handling of surviving enemies.

## 3.1.0.7 — 2026-11-03

- Improved Llymlaen's corridor transitions, continuing hazards, knockback guidance and recovery.

## 3.1.0.6 — 2026-11-03

- Improved Eulogia's tile safety, knockback movement, damage warnings and recovery between attempts.

## 3.1.0.5 — 2026-11-03

- Improved Thaliak's tile positioning, knockback landings and continued mechanic guidance later in the fight.

## 3.1.0.4 — 2026-11-03

- Corrected Rhalgr's safe-finger selection during Beacon knockbacks and improved damage warnings.

## 3.1.0.3 — 2026-11-03

- Improved Oschon's phase transitions, later mechanic coverage, knockback landings and recovery.

## 3.1.0.2 — 2026-11-02

- Improved movement and automatic assignments across supported Eden, Omega, Alexander and Pandaemonium Savage encounters.
- Improved selected Extreme-trial mechanics and dungeon encounters.

## 3.1.0.1 — 2026-11-02

- Improved add targeting in Deltascape V3.0 (Savage), recovery in Sigmascape V2.0 (Savage), Rot handling in Sigmascape V3.0 (Savage), and Storms positioning in Asphodelos: The Third Circle (Savage).

## 3.0.0.1 — 2026-11-01

- Improved automatic tank assignments and movement in supported Extreme trials, Savage raids and the Cloud of Darkness chaotic raid.
- Improved mechanic handling in Alexander, Omega and Eden encounters.

## 3.0.0.0 — 2026-11-01

- Expanded encounter coverage and automatic party assignments, including support for smaller groups where the mechanics permit it.

## 2.1.0.7 — 2026-10-31

- Improved Pas des Seul positioning and survival when continuing with remaining beasts.

## 2.1.0.6 — 2026-10-31

- Added visibility into virtual cooldown plans and Difficulty 3 strategies for the public Crewcible boards.
- Added Pas des Seul backup-team plans and clearer recorded progress indicators.
- Made encounter additions available under BMR's default Contributed filter.

## 2.1.0.5 — 2026-10-30

- Refreshed the public Crewcible package following beast-management and fight-continuation improvements.

## 2.1.0.4 — 2026-10-30

- Corrected beast handling in standard Crewcible runs and improved continuation after revival or rotation changes.

## 2.1.0.3 — 2026-10-30

- Updated the companion window's appearance and presentation.

## 2.1.0.2 — 2026-10-29

- Improved Crewcible mechanic handling, beast handoffs and continuation after revival or lost beasts.

## 2.1.0.1 — 2026-10-29

- Corrected repeated beast preparation and improved Sands revival and tank handoffs.

## 2.1.0.0 — 2026-10-28

- Expanded encounter corrections and BST support for the public Crewcible boards.

## Earlier public releases — 2026-10-24 to 2026-10-26

Versions 0.1.0.0 through 2.0.0.0 established the companion window, encounter controls, translations, public encounter additions, Praetorium timelines and bundled cooldown plans. Individual packages remain available in [Releases](https://github.com/McVaxius/BMRVariantLoader-Public/releases).
