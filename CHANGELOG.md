# The Fortress - changelog

Every build that changed something, newest first. Each entry is that build's own changes.

## v0.0.29-P457

- Restore Tactics lab-tab hero gate + guard tab-unlock research clobber
- Roster-row pill width + class-icon adjacency — slice B
- Shell format slice A — Straw reserve / Filter styling / COMMAND tile inset
- Cost buttons render real currency icon chips — shared CostButton composite
- Gear-doll v2 — full-width doll over always-visible LOOT, modal interactions
- Remember the window's position between sessions (1.1.26)
- Pause-proof input — the desktop shell froze ALL input while paused
- Count-card action says the action + remaining, not "Capacity"
- QA round 2 — inline wallet, natural chips, MARCH in-column, detail-click folds to icons
- Tip-truth pass 2 — remove unbuilt-content tips, grain→straw
- Game delta-update client — download the patch, not the build (phase 2b)
- Truthful lock messages + lock-message Auditor suite
- Delta-update boot overlay — first-autoload patch mount (phase 2a)
- 3-column nav — thin top bar, tri-state buildings column, pip width controls
- Remember the desktop window's position, not just its monitor

Behind the scenes:
- Remove dead card-body builders — slice C item 8
- Web 'new version ready' banner for the browser build
- Portable native widgets — form-factor-free, mobile-first (Nathan 2026-07-09)
- Native-first slice 1 — battle HUDs size to content, no hand-coded boxes

## v0.0.29-P442

- 1.1.24 — first real delta release + friendly patch-download label
- Delta self-update via boot-time patch overlay (delta engine, part A)
- TYPECARD — per-type build-card/open-detail fork shape added to the modularity known set
- Scaler buildings to 99 levels + vault cap = gear-equipping unit count
- Speedup family routed through CheatManager — CHEAT FINISH unreachable in release
- Show release notes on the self-update screen
- Credit game-icons.net, drop the 'everything handmade' overclaim
- Host player docs on R2 + link them from the site Codex
- Tip-truth pass — tournament tips pulled, Leveling renamed Units
- Fresh non-maxed marketing screenshots + recover clean-capture mode
- Flush-left fill + Option-A detail pane (density pass v1)
- Wide-viewport overlay floats with a bottom gap instead of butting the bottom edge
- Grid gallery + lightbox, drop false expand-chevrons
- Render cost/price as real flat-icon chips, not emoji (web tofu)
- Mipmaps on ALL art imports — completes the small-icon clarity fix tree-wide
- Icon-audit PDF in the Player Documents post + box dead-man check
- Rail label fits natively (no PRODUCTION clip) + native-first rule

Behind the scenes:
- Illustrate the player documents with in-game icons + art (deferred)
- Multi-AI execution offload — deferred parking-lot entry
- Schematic was never retired — five discovery types restored across all claim sites
- Delta downloads — native patch-PCK chosen, zsync parked (roadmap v12)
- Unify mode-button styling across the bar AND rail (one shared definition)

## v0.0.29-P428

- Mipmap-aware default texture filter — small icons render crisp, not muddy
- MARCH mode-bar action slot gets its walking-boot icon
- True-width step 2 — desktop-only left mode rail

Behind the scenes:
- Recover live website source into the repo
- MARCH becomes a bottom-bar action slot; compress space above modes
- Add web auto-deploy + live docs/roadmap plumbing lines

## v0.0.29-P422

- Trim level counts to milestone-delivering levels
- True-width step 1 - aspect-matched game surface, capped at 1080 logical
- F5 flow = the launcher's flow — notes first, then choose, then launch
- Drop D-65-deleted threshold parsers — unblocks the player-docs generator
- Doll proportions + production contrast + armguards final — roster 36/36
- Version subtitle under the title
- Unified notes — current-minor history, Full-notes link, --notes-shown
- F5 flash fix + current-minor full history + Full-notes link
- Unify level-up milestones + reshape Builder-track unlock pacing
- Mode pill fills its space - icon 56, label 22, stretch 2.6
- Unify release-notes trigger — one ReleaseNotesGate (Step 1)
- Icon-first mode bar — big idle icons, active gold pill with label
- In-game screen is mobile-only; PC/Mac use the launcher
- Anchor-based doll layout — slots at anatomical positions over the silhouette
- All 19 doll slots visible (staged locked), equipped slots show painterly, light silhouette backdrop
- Once-per-launch boot gate before any mode
- Health checks never apply to adopted server spawns
- Loot painterly visible in-game + silhouette doll backdrop + redo promotions
- Itemization redesign + loot art final state — earrings/tabard, 6 sets, flavor text, seed library, audit v25
- Show on every launch with a Continue button (all platforms + Godot)
- In-game "What's New" screen — recent release notes on all platforms
- Per-release notes history on the update and ready screens
- Per-build incremental notes, everything that reached the game since last build
- Wide-ratio shell — game in a SubViewport with real side margins

Behind the scenes:
- Add browser-playable build + thefortressgame.com website
- Add browser-play option to the QA setup forum
- Progression permutation fuzzer + progression design philosophy
- Relabel mis-aimed character scenario to what it captures
- Static Critic for research/lab progression
- Graphics audit joins the monthly player-docs post + on-demand lane
- Production gears brightened to #C7CDD6 (Nathan-approved contrast fix); audit order - MODES page follows currencies
- Roster complete — all 37 items Nathan-approved + shape-control playbook
- Knotted Sling + Rusty Sabatons promotions; registry picks recorded
- Seeded-round candidates + noun-seed registry draft + cuffs/girdle promotions
- Mark "remember the monitor" done under v0.0.27
- Zombie-link detector — sustained zero connections = dead bridge, recycle
- Dynamic Discord retrofit — fix recent #releases posts in place
- Retroactively fix the 34 release notes (launcher scrollback + old Discord)
- Desktop side-margins shell + QA watermark done

## v0.0.29-P400

- Remember which monitor the desktop game was on and reopen there
- Loot itemization — 4 sets, 18 new items, renames, staged slots
- Watermark visible at window top-left — drop the stretch-inverse transform
- Watermark off-screen — use OrientationLock's proven stretch transform

Behind the scenes:
- Placeholder for muddy small icons + remember-the-monitor request
- Record watermark, desktop-margins fix, coin-icon fix, launcher-notes
- Gear-slot placement approved + audit v24 cover versioning
- P391 + wire character painterly tiers to resolver naming
- Worklist item 1 + party/camp/character model + audit restructure

## v0.0.29-P389

- Watermark to true window top-left + remove duplicate version displays
- Always-on version watermark in the top-left (QA/dev builds)
- Silence the last 4 integer-division warnings (intentional window math)
- QA/Regular order + Icon Testing parity in editor picker
- Restore Standard/Scientific notation example on Numbers buttons
- Margin fortress icon points at importable art (P382)
- Label the chunky icon style 'Pixelated' (P381)

Behind the scenes:
- Pin system, incident fixes, tech-reference v6, roadmap v6 retro-fill
- Record today's v0.0.27 ships (boot cleanup, settings + launcher polish)
- Bump LAUNCHER_VERSION to 1.1.19 so installed launchers self-update
- RC four-engine infra sync + always-on hardening
- Record browser-direct self-healing AI sessions (in-flight infra)
- Player reference PDFs monthly + icon-PDF roadmap line

## v0.0.29-P380

- Center all settings popups (P378, verified)
- Center all popups on full screen; fix invisible debug margin content
- Vault in 02-08, walls+stonemason in 05-08 (P373)
- Add walls and stonemason to _snapshot_build_side_buildings (P371)
- Promote damage/slots/headers to flat; fix classifier; D-81 gear model
- Remove Guardhouse empty-state overlay; Builder Improve button own row

## v0.0.29-P369

- Display-settings overhaul + desktop full-width prep + quit relocation
- Built buildings never show locked in mode picker
- Missing-art placeholder when painterly absent (Outriders portrait)
- Promote 10 assets, large-font sheets, pagination, gear fix
- Redesign generator, promote 12 flats, generate candidates, rename sheets
- Wrap empty-state flavor text; cap Improve button width (P364)
- First-open picker stacking (P364)
- Font bump + lock, generalize generator, 8 contact sheets

Behind the scenes:
- Install scripts register tasks windowless (no console flash on reinstall)
- Stamp version v3

## v0.0.29-P363

- High-contrast palette maximum-strength pass (P362)
- Landscape-readiness prep; roadmap lines for font-scaling and landscape UI
- Quit nav item + comprehensive high-contrast mode
- Relocate never-ending tracks from Library to buildings
- Unsaved-changes detection, popup cancel, bottom bar, window modes, HC toggle
- Remove resolution control from mobile tab
- Retire launcher-picker shared-submodule line
- Enable resolution control on PC tab; remove window-size workaround
- Label the picker buttons; picker survives a blocked window resize
- Reload ThemeConstants profile after picker resolves
- Launcher picker as a true shared component (deferred infrastructure)
- Picker window — 480x440 at picker stage, resize to profile on selection
- F5 picker — brand styling, mobile window sizing, profile-aware display defaults
- Phase B building art reorg — single-tree consolidation
- Building-lock single-source line + Character pre-throne portrait art line
- Change placeholder text to "Coming soon."
- Save+Exit buttons; fix chunky icon preview black square
- Four settings-panel follow-up fixes
- One combined card across all four modes + overflow/cold-start/empty-state
- Settings panel layout, rail collapse, icon color fix

Behind the scenes:
- Gitignore Python bytecode — the salvage-commit junk
- Rule 7 — done items stay until build close, migrate to #about by category
- Visual-testing channel built; drive-to-state next
- Weekly committed-art PDF publish to Discord (planned, v0.1.0)
- Current with five-style model, reorg, lanes, and review system
- On-screen visual testing in progress, mechanism proven
- Archive Project Instructions v128
- Mark engine-file split shipped, move to #about built record
- Finish open-issues/impl-plan retirement
- Unify mobile profile into single source of truth
- Extract HeroesBarracksState slice — final D-78 slice
- Add art-manifest-v1 — full repo image inventory
- Extract BuildingsMilestonesState slice
- Phase A icon reorg — one tree under assets/art/
- Extract ProductionQueueState slice
- Lock pass into impl-plan(v85) + open-issues(v37) + DECISIONS + art-roadmap
- Add art-directory-layout-v1 — one-tree layout spec
- Extract ResearchState slice
- Archive Project Instructions v125, restart archive practice

## v0.0.29-P340

- First published build.

## v0.0.29-P320

- Infinity lab category - reframe v0.0.27 never-ending tracks, add Infinity icon art item
- Building portrait art
- Painterly building portrait hero in maker-tab header
- Building portrait hero in DetailModal
- Add gold-box stat bonus and never-ending-track gate to Placeholder
- Regen currency icons with locked glyph set, retire desktop/
- Strike the two shipped tab-restructure items
- Add monthly source-file-size regrowth check
- Add engine-file decomposition workstream to Infrastructure track
- Cleaner release notes, Update button above notes, bigger window
- Bug-mirroring (GitHub <-> #known-bugs) at top of infrastructure
- Mark modularity items confirmed by P312 QA
- Cut QA build
- Incorporate icon-style picker recommendations
- Icon Testing launcher entry + in-game true-size icon preview
- Built building's picker modal shows build-state only
- Cut QA build (build-state/level decoupling, green caption)
- Per-device window mode/resolution with boot validation
- Add art-style toggle (ASCII / flat icons / painterly) to Placeholder
- Promote display settings to active (v0.0.29), per-device
- Render the cap-rise caption in green, not muted
- Cut QA build for real building level + green cap-rise caption
- Consolidate modularity and infra embeds; add PC graphics item
- Desktop preview shows the portrait UI centered instead of stretched
- Tactics lab, cap-raise +10, picker cards, detail-modal fixes
- QA Desktop opens landscape, QA Mobile opens phone-sized, each with its own graphics
- Full base fetch so the governed-paths diff always resolves a merge base
- Desktop window opens large and centered, sized to the monitor
- Build on the box instead of cloud Linux
- 3-screen wizard installing the clean build that honors --qa
- Mark shipped pipeline savers done
- Pin gate model to claude-sonnet-4-6
- Add leaner-pipeline savers to infra track
- Coming-soon flavor line under header-only building cards
- Split the over-length Placeholder post to unblock the channel sync

Behind the scenes:
- Reframe delta-download as undetermined-future, low priority
- Add chunky currency icon set (8 PNGs)
- Record GameManager decomposition + scope the doc-edit write-barrier
- Building portrait hero notes in dev-gui-management-v6
- Record building-art-into-UI in DECISIONS and roadmap source
- Mark engine-file split progress on the roadmap (3 self-contained slices done)
- Centralize portrait resolution with id/filename normalization
- Builder never-ending track ships as a coming-soon placeholder
- Archive instructions v106 before v107
- Impl-plan v83 - Builder never-ending track parked as a placeholder
- Extract gear/loot slice into GearState component
- Extract alert/badge slice into AlertState component
- Implementation plan v82 - correct v0.0.27 close-out STATUS
- Extract wallet/run-earnings/lifetime-stats into EconomyState component
- Implementation plan v81 - record v0.0.27 tab restructure
- Rename business-infrastructure v12 to v13
- Record server-authoritative fair play (early groundwork + v1.0 cluster)
- Scrub change/delta narrative from 12 resident docs; version-bump
- Security/competitive-integrity spec + roadmap fair-play update
- Icon-lookup-and-currencies spec v3
- Lock unified skill/progression modal field set + testable picker builder
- Single StatusDisplay resolver for availability status
- Builder picker cards show build-state, not level
- Separate build-state from level (derived)
- Delete superseded game-design-economy-v1
- Economy v2 - art/skins framework as the cosmetic monetization vehicle
- Batch-3 building tiles (stonemason, academy, treasury)
- Batch-2 building tiles (forge, quarry, thresher)
- Android build step exits 0 reliably (aapt2 badging exit-code fix)
- Batch-1 building tiles (vault, throne, sentry-towers)
- Add launcher self-update and smaller-update items
- Add mobile-preview line under v0.0.29
- Mark self-updating Windows install as done
- Add before-launch interface reassessment to Placeholder

## v0.0.29-P297

- Builder tab is build-only, uniform per-building leveling on each tab
- Add endlessly repeatable gathering-building queue to placeholder
- Single tester build, one download
- Currency phone icons (grad+outline) + desktop flat overrides
- Non-destructive publish so the link can't break
- Download progress bar

Behind the scenes:
- Trigger P293 tester build (render + cheat fixes + currency icons)

## v0.0.29-P293

- Render PRODUCTION gathering tabs (gate early-return on maker type)
- Newest-game-release selection + castle icon
- Windows export preset + Inno Setup installer script
- Windows update launcher standalone project
- Shared per-platform icon lookup
- Add self-updating Windows install to the infrastructure track
- Add shared combat-HUD-button component to v0.1 Enhance Explore
- Move passive readout to its own layer below the buttons (P286)
- Move gear/CHEAT chrome onto its own CanvasLayer above the HUD (P285)
- Reverse milestone order - Enhance Explore v0.1, Enhance Defense v0.2

Behind the scenes:
- Route currency icons through IconLookup
- Trigger v0.0.27-P289 tester build
- Trigger v0.0.27-P284 build

## v0.0.29-P284

- Gear lower-edge dead zone, passive HUD strip steals the tap (P284)
- Explore button hit-rect + press overlay (diagnostic, P283)
- Drive Explore movement from mouse stream only, tighten corner buttons
- Add two missing approved items to placeholder
- Implement UI occlusion gate on Explore screen
- Fold branded startup splash into the v0.0.29 intro-splash item
- Add startup splash and Android portrait boot splash to placeholder
- Add custom controls to placeholder (tracked, not scheduled)
- Corner-as-gear guard for Explore-screen gear taps
- Fold building/tab unification into the modularity-pass block
- Park the bug-loop back half as a future item
- Reopen v0.0.27 with remaining modularity items as features
- Add a quit button in the settings gear to the Placeholder bucket
- Expand v0.0.29 save work with multiple characters, QA slot, unified build, and entry flow
- Remove dead Forge armament-detail path
- Selection-flow lock-reason consolidation + locked wording
- Mark phone tap-to-update done
- Rewrite v0.0.27 block to show the six open must-do items
- Force portrait at runtime; bump Android version/code
- Fund gems/spoils/crowns from the +99,999 All button
- Add class/magic activatable combat effects to the Placeholder bucket
- Add screen-ratio scaling to the Placeholder bucket
- Add general long-press-for-info feature (Placeholder, no version)
- Add detailed-wallet feature under v0.5

Behind the scenes:
- Remove debug overlay (Play Protect block)
- Trigger v0.0.27-P283 QA build
- Trigger v0.0.27-P282 QA build
- Split over-length v0.0.27 post so roadmap-sync passes
- Trigger v0.0.27-P281 QA build
- Mark app launcher icon done in art-now roadmap block
- Add input/gesture architecture requirement for gameplay screens
- Trigger all-platform QA build for v0.0.27-P276
- Bump dev-implementation-plan v78 to v79
- Drop the weekly technical appendix entirely, fold ledger lines into the seed
- WATCHTOWER coherence - daily appendix and branch-cleanup residuals
- Remove the technical appendix from the channel
- Extract shared ScreenChrome (gear + CHEAT) across screens
- Add multiple-characters and unified-QA-build save spec
- Add game-style-sizing standard and index it
- Implementation plan v78 - realign the 27/28 split to the roadmap

## v0.0.29-P259

- V0.0.29 run data collection, v1.0 cheat prevention; art-track economy rule
- Hosted-runner sync + real-world-money-only disclosure rule
- Tooling onto the art side path; sync art editorial rule
- One list, full transparency. Add the tooling and pipeline track; rewrite editorial rules to hold back only economics and monetization
- Confirming a bug files it to known-bugs without auto-launching the fix
- Strip whitespace from all the poller's env reads
- Strip whitespace from the poller's NATHAN_ID env read
- Discord User-Agent on all three loop scripts; watcher posts into the forum thread
- Poller reads the bug-reports forum's posts (threads), not channel messages
- #about self-sync by channel name + milestone-tree roadmap
- Remove dead build-queue-slot text from Builder alerts
- Watcher matches non-closing Bug-loop-fixes: #N
- Known-bug label + confirm-to-close on the poller
- Weekly digest reviews the player roadmap
- Library research queue to level-gated multi-slot
- QA bug-report loop (poller + merge watcher, fail-inert until secrets set)
- Roadmap sync posts before deleting (fail-safe migration)
- Drop construction queue to a single slot at every level

Behind the scenes:
- Restore infrastructure track as its own parallel roadmap section
- Painterly building generator + 17 placeholder renders
- Record roadmap canonicalization and decision reversals
- Add idle loop v0.3, NPC build-out, tournament split, onboarding + achievements
- Reorder side sections to the end, decouple art from versions, add v2.0 biomes + placeholder items
- Work-model version numbering + full parallel art track
- Bump business-infra to v11 and field manual to v6
- Record bug-loop go-live in WATCHTOWER and DECISIONS
- 1:1 note, version clarification, bugs + placeholder sections, phased art, Defense reframe
- Stat-rollup reframe, split Explore into three milestones, balance to v0.6.0
- Merge stat-wiring build, Enhance Defense/Explore, art track up
- Milestone-based detail, split 27, blueprints to Explore, local-then-cloud saves
- Future tiers as prose paragraphs, no version numbers
- Expand the roadmap - evergreen intro + full aspirational tree
- Version tree, versioning defined, Defend/Explore/Throne moved to in-the-build
- Bug-report loop + known-bugs sync armed (all secrets set)
- Business-infrastructure v9 - bug loop armed (all secrets set)
- Add generic empty-slot icon set (wip, draft for review)
- Adopt the channel as the authoritative active backlog + Current Build working list
- Game-design-items v15 to v16 (Library research-slot count corrected)
- Add proportional humanoid silhouette for gear doll (wip)
- Stage premium-currency and discovery-item placeholder icons in art/icons-wip
- Stage live-currency placeholder icons in art/icons-wip (gdignored)
- Spec the full lifecycle and conventions
- Remove orphaned state file
- Seed poller cursor to now so first run ignores pre-existing channel history
- Add Discord #qa-setup channel source
- Remove dead pip ecosystem from dependabot config
- Remove item rarity concept (field, display, color)

## v0.0.29-P252

- Shared modal gains optional STATS section
- Gear leveling mechanic
- Clamp overflowing control so tab fits viewport at max font (Windows)
- Paused items show paid state, never affordability
- Resume bypasses affordability check

Behind the scenes:
- Game-design-items v14 to v15
- Entity/queue language fix - leveling-header reframe (plan v73, ui-audit v2)
- One config-driven queue lifecycle
- Four canonical queue ids, translation layer deleted

## v0.0.29-P238

- Deterministic weekday for the Morning Brief - date command is the only day authority (Friday-as-Thursday digest, Jun 12)
- Snapshot relock - re-seed tab locks + unconditional mode-filter re-apply
- DV-2/3/4 + DA-3.1 + DA-1.3/1.4 closed, DV-1 re-scoped, DA-3.9 added
- Monthly Deep Review - comprehensive structural review, no rotation pointers
- Brief format v3 - bannered per-section posts, seed as attached file, three-channel map
- Thursday is the full comprehensive review, never a sample; ledger gains the dev chat's overnight findings
- Readable briefs, Thursday review delta + recommendations seed, standing review ledger
- Runner Live, two Coming rows satisfied, bulk-sweep row added
- Research cap language, building ladder counts construction, revert maxed-cost row

Behind the scenes:
- Game-architecture-data-core v13 to v14
- Chronicle v81 bump + v79 numbering note (field manual v5)
- Review ledger - CR-3 closed (P235)
- Field-manual v5 chronicle - record v80 bump
- Dev-field-manual v4 to v5 - v79 chronicle, ghost closed, BIOS dropped
- Review ledger - DV-7 closed (P234)
- Dev-field-manual v3 to v4 - permission writes proven, case closed
- Dev-field-manual v2 to v3 - Zapier/Discord case file
- Dev-field-manual-v1 (v77 thin-core split)
- Bug intake convention (player-report issue contract)
- Crash reports via engine log file; drop console wrapper; two-exe zip
- Dual exports per release - clean player build + QA build
- Full version string and generated release notes
- QA builds export debug to keep the cheat/QA panel and version readout
- Stop promoting Godot stderr noise to fatal build errors
- Readable build-failure reports
- Build failures to #spam-updates, self-reporting failure evidence
- Business infrastructure v6 - Discord three-channel ops + Section 7 community operations spec
- Deep Review crons move overnight Eastern (0 5 / 0 7 UTC)
- Bulk branch sweep DONE (119 to 9, self-verifying errand); row moved from Coming to the mapped table
- Coming ledger + three-standing-worries section + dual-home note

## v0.0.29-P224

- Unit effect is capacity, research carries the noun, sections never hide
- Wire unit pickers to shared effect/total generators
- Skill modal carries the unified section contract (P222)
- Total_text for Type-1 research modals

Behind the scenes:
- Daily toolchain-sync check in the morning brief
- Thursday debt sweep - config bypasses + cross-board fixes
- Session-52 increment + same-turn clean sweep (interval 2 to 3, counter to 0)
- Session-51 counter increment (0 to 1)
- Retire superseded P158/P177 effect-line mechanism
- Productive sweep over sessions 48-49, reset counter
- Dev-parking-lot v14 (modal unification sweep + resolved items)
- Session-49 counter increment 1 to 2 (sweep now due)

## v0.0.29-P217

- A/B/C lettering, round-robin sentry posting, hero status spread
- Snapshot buttons auto-close the panel
- Research cap-raise line shows per-level magnitude + cumulative total
- Refactor(tabs) 2/2: Armory + Guardhouse empty states through shared renderer

Behind the scenes:
- Remove unparseable fork-bomb deny rule

## v0.0.29-P209

- Refactor(tabs) 1/2: shared _show_empty_state in TabBase + Hall migration
- Fix pre-Throne snapshot infinite recursion
- Pre-Throne flavor stable across re-expand (option c)

## v0.0.29-P205

- Create UNITS Hall tab as terminal-node class
- Mounted armament instance name + gate Camp deploy line when locked
- Fix stale COMMAND garrison header + number cheat armament names

## v0.0.29-P199

- Party Soldiers + Siege Weapons always show flavor placeholder
- Allow simultaneous deploy + post (UI gates + pool counts)
- Gold maxed-card styling on LevelingHeaderCard
- Hint no longer lies "raise hero limit" at flat cap
- Cap hero recruiting at 2 per class
- MAX snapshot 2 heroes/class, posted + max-level soldiers
- Cap armament inventory at 3 per type, research-driven
- Seed proportional research into snapshots 3-10
- Remove unreachable (max +50%) cap claim from Treasury/Academy
- MAX snapshot maxes pool skills, research, party slots
- Header treatment C - gold section labels, cream value text (incl. Current Level number), dashed dividers between sections, so labels read distinctly from values even in the maxed gold state
- Take the TOTAL line's sign and percent from the effect rule so it always agrees with the EFFECT line (fixes reductions showing + and the missing % on percent stats)
- MAXED snapshot really maxes all (Commander labs + buildings)
- Clear unused-variable debugger warnings
- Immunity clamp note in stat modal EFFECT
- HP / HP-per-second units on stat values
- % suffix on percent stat row value lines
- Stat modal uses real description, drops "effect pending"
- Type-1 modal total-effect line via one shared builder

Behind the scenes:
- Guard→soldier in fortress card, guardhouse roster, guard-pool skills
- Distinguishing names for injected heroes + armaments
- Dev-gui-management v3 — correct cheat-panel snapshot labels
- Row shows only resolved value, no base+mod subline
- Bump v1 → v2, retire v1

## v0.0.29-P176

- Remove hero/PARTY Library lab tab from current set
- Vault ring cap = double the non-ring cap
- Fighter is free via the old hero, not rescue-gated
- Repurpose Academy as the global loot-cap controller
- Maxed snapshot full gear (incl. quiver/shield) on every hero
- Teaser render path, throne modal sizing, pre-Throne hero recruit gate
- Pre-Throne Offense/Defense skill sub-tabs as no-value teasers
- Throne modal overlay fix + Inject Hero cheat gate
- Pre-Throne gating

Behind the scenes:
- Game-style-management v11 - builder 4 categories, library 5 lab tabs by design
- Retire six superseded doc versions (v18/v11/v10/v15/v2/v6)
- GDD prose sync to Fighter-loop rework + ring cap (loop v3, progressions v11, items v12, entities v16, glossary v7)
- Correct MODEL ROUTING to alias-based (latest Opus/Sonnet, not 4.7 pin)
- Split loot cap to a new Vault building, restore Academy XP, restore ring cap 4
- Dedupe Docs/ - retire four stale doc versions
- Retire five superseded doc versions (v9/v5/v1/v15)

## v0.0.29-P161

- Throne transition explicitly re-evaluates tab visibility
- Pool stat upgrades play juice + MAX flourish
- Pool skill rows show per-stat description lines
- Pool skill rows render as boxes + tap-to-modal
- Fortress entity-tier up-sum (posted heroes + on-duty guards + mounted armaments) — D-45 v3 / D-49
- Unify guard/armament per-unit stat resolution with heroes — D-12 parity step 2
- Fortress entity-tier HP pool stats + core/walls base retune

Behind the scenes:
- Switch Claude Code model selection to opus/sonnet aliases
- Thread stat breakdown to DetailModal, collapse 4 entity-tab tap handlers
- Unify stat-upgrade callback behind TabBase helper
- Dev-gui-management v1 to v2 (label-by-mode matrix at top of §C)

## v0.0.29-P147

- Party working-together floor on non-HP skill stats
- Party-defense member-collection sum
- Party-offense per-member down-buff
- Wire hero-pool scope contribution
- Fix dead hero rename affordance (labels block tap handler)

Behind the scenes:
- Delete four superseded Docs versions, refs repointed first
- Mirror S33 docs to repo
- Parking-lot v11 - infrastructure initiative complete
- Correct stale RelationshipEvaluator header comment

## v0.0.29-P139

- Route hero rename through shared RenameModal (delete inline duplicate)
- Route 3 pool tabs through StatRowBuilder (finish consolidation)
- StatRowBuilder + route 4 entity tabs (show resolved net value)
- Add RelationshipEvaluator + relationship table skeleton (additive)

Behind the scenes:
- Audit how combat assembles entities for compile-step design

## v0.0.29-P130

- Drop per-currency dimming, restore native Button text centering
- Repoint maker Improve to ProgressionButton
- Research card names render correct lab/forge/recruit colors
- Add miscellaneous lab color + harden color-mapping fallbacks
- Bounded HEADER_DEBUG prints for barracks/builder
- Repo consistency check + fix all detected path drift
- Verifier base-ref resolution on push events
- CODEOWNERS + PR template + bugfix shape check + Dependabot
- Deterministic Gate 3 identifier verifier (replaces removed LLM gate)
- Add godot-quirks skill
- Opus 4.7 default + sonnet label opt-in
- Add id-token: write permission required for OAuth token verification
- Bump SUB_PATCH P120 to P121
- Wip-122 fix Improve click handler reconciliation and DetailModal affordability gate
- Wip-121 fix Barracks maker-header refresh in PRODUCTION mode + remove wip-120 diagnostics
- Wip-120 instrument cheat-zero Barracks Improve bug
- Wip-119 maker upgrade UI refresh fix — explicit _update_production_header() in _execute_improve_building, remove wip-118 diagnostic prints
- Wip-118 diagnostic instrumentation for Barracks upgrade deduct-but-no-increment bug
- Wip-115 sticky maker-header card + maker-header card row-style state treatment + maker-header DetailModal matches progression DetailModal
- Wip-114 SelectionCard shows cost when Locked, drops giant overlay, renders lock reason inline as action text
- Wip-113 Selection Screen filter consolidation with search bar + arrow navigation between queue slots + queue cards show all slots including locked
- Wip-112 show COST and BUILD TIME on Locked DetailModal, return actual effect description on Maxed in EffectSummary, widen Maxed action button
- Wip-111 DetailModal Availability section + Current Level promoted to top + Maxed gold treatment + per-currency cost graying
- Wip-109 rename Library lab tab "TACTICS" → "PARTY" in UI label
- Wip-106 DetailModal renders placeholder text for empty DESCRIPTION and EFFECT sections so missing flavor is visible
- SUB_PATCH P59
- Extract _should_hide_header helper; add _show_header_in_command_skills virtual
- Throne opts into level-up header in COMMAND/Skills
- SUB_PATCH P58
- Revert party COMMAND/Skills header fallthrough
- Revert fortress COMMAND/Skills header fallthrough
- SUB_PATCH P57
- Barracks tab UNITS/Skills wired with hero pool stats
- Guardhouse tab UNITS/Skills wired with guard pool stats
- Armory tab UNITS/Skills wired with armament pool stats
- Pool stat definitions + scaling for hero/armament/guard pools
- Party tab COMMAND/Skills shows level-up header
- Fortress tab COMMAND/Skills shows level-up header
- Throne tab COMMAND/Skills shows level-up header
- Lock hint on locked GearDoll slot buttons
- Relic regression fix + COMMAND/Skills content split (Throne/Fortress/Camp)
- Relic on player + stats refresh on equip + FTR/ARC/COM + class on every item + empty=unusable
- Show class restriction in gear comparison panel description
- Class restriction badge on GearDoll inventory tiles (manual push - direct to main)
- Hero gear via GearDoll reuse + modal width 380->620
- Cold-start defaults — mode=COMMAND (leftmost), subview=secondary (Skills, leftmost)
- Extract _route_to_management_if_needed helper; apply to every snapshot entry point
- Fix snapshot UI reset + sub-toggle within-session memory
- Snapshots preserve current UI state (no navigation); fix sub-toggle visual desync on tab focus
- Strip UI state persistence — every cold launch starts fresh; only Reset All cheat resets within-session UI state
- Uid cleanup + window size override
- Reset sub-toggle to primary on cold start
- Simplify LEVELING to UNITS - remove sub-toggle, rename mode
- Fortress bonus case sensitivity - match lowercase damage types from CombatConfig (P30)
- Guard + armament inspect Fortress bonus row (P28)
- Hero inspect Commander bonus from player entity stats (P29)
- Hero slots unassign button + prioritize deploy status reason
- Hero inspect — always show Gear row in breakdown, strip Hero prefix from stat names (P28)
- StatBreakdownPopup add to tree before setup (P27)
- EntityInspectModal card SIZE_EXPAND_FILL for scroll content visibility (P21)
- Fix invented ThemeConstants properties in inspect content files
- StyleBoxFlat type annotations on inspect content button styles (P18)
- Discord-notify-release sed crash - replace with tr
- Stat Inspection - EntityInspectModal, inspect entry points, building headers corrected
- Fix last 2 debugger warnings
- Fix Discovery→Production mode switch and integer division warning
- Fix mode switching regression and debugger warnings
- Extract mode controller — Phase 1 new file
- Extract gear dropdown + bottom sheet helpers — Phase 1 new files
- Docs/archive cleanup — move superseded doc versions
- Mid-Game Stocked adds Archer + Fortress card order matches Party
- Party guard slots 4→3, Barracks cap 27→26

Behind the scenes:
- Parameterize ProgressionButton for maker-header reuse
- Slim 17KB → 12KB by moving DATA LAYER + architecture to fortress-data-layer skill
- Archive obsolete Docs/ versions and delete godot-quirks-v8
- Sync dev-technical-reference and game-business-infrastructure to v4
- Remove Slack-era reference in auto-merge PR body string
- Backfill critical project-knowledge files to Docs/ (partial sync)
- Add bugfix issue template (root-cause structure)
- Dev-implementation-plan v66 and dev-journal v12 - Session 8 sub-toggle reset and TabBar visual sync
- Dev-implementation-plan v65 — v0.0.27 Path B + sub-toggle (P37-P39), v0.0.28 scope updated
- Game-style-changelog v19 — Path B + sub-toggle entries for v0.0.27 P37-P39
- Dev-implementation-plan v64 — flicker fix done in v0.0.27 Session 5 (P36), close ready
- Dev-implementation-plan v63 — v0.0.27 Sessions 4-5 complete, flicker fix deferred to v0.0.28
- Game-architecture-components v8 — CommandSubviewToggle added, LevelingNav removed
- Game-style-changelog v18 — UNITS migration + Bonuses/Roster toggle entries
- Archive superseded docs (dev-implementation-plan-v61)
- Godot-quirks v8 (case-sensitivity rule) + dev-implementation-plan v62 (v0.0.27 scope update)
- Dev-journal v11 (new entry on API hallucination)
- Remove superseded dev-journal-v10
- Archive superseded dev-journal-v10 and components-v6
- Remove superseded game-architecture-components-v6
- Game-architecture-components v7 full content
- Game-architecture-components v7 (v0.0.27 inspect components)
- Implementation plan v61 - v0.0.26 closed, roadmap updated
- Impl-plan v60 - split v0.0.26 into Stat Inspection + COMMAND Polish, renumber through v0.0.30
- Game-design-items v9 — Forge/Barracks soft caps updated, party slots added to level chains
- Archive superseded v14/v15/v57 doc versions
- Remove superseded components v5 and journal v9
- Journal v10 — Running unsupervised entry (v0.0.25 Session 2)
- Archive components v5 (superseded by v6)
- Components v6 — add GearDropdownManager, BottomSheetHelpers, ModeController from v0.0.25 extraction
- Journal v9 index — Sessions 10-11 entries added
- Changelog v15 summary — Sessions 9-11 visual changes
- Data-core v12 full content — party guard/armament slots, guard/armament leveling
- Placeholder data-core v12 — will be replaced with full content
- Open-issues v32 — close guard/armament leveling + party slots, add tab scroll/modal overflow/nested inspect
- Glossary v4 — LEVELING tab names, slot count rule, guard/armament leveling

## v0.0.29-P121

- Add Mid-Game Stocked + Mid-Game Deployed cheat snapshots
- Unify slot visual rendering across Party and Fortress tabs
- Show locked party slots + raise cheat levels
- Party slot assignments — data structures + cheat + display
- Party Soldiers/Siege Weapons show numbered empty slots
- Barracks + Forge level chain update — party slot unlocks
- Add Guardhouse tab with guard leveling
- Rename LEVELING tabs to place-based names
- Resume UX - time display and complete suffix
- Add armament leveling — Gold cost, damage bonus

## v0.0.29-P108

- Fix tab bar overflow and armory tap crash
- Add Armory tab in LEVELING mode — armament roster grouped by type

## v0.0.29-P107

- Fix resume card trailing time and Fists inspect
- Fix resume timer display and remove redundant Inspect buttons
- Tap-to-inspect everywhere — COMMAND cards, Throne gear, LEVELING rows
- Fix resume flow — skip costs and restore timer when resuming paused items
- Cancel = Pause with confirmation modal
- Fix hero roster card layout — proper card panels, not pill buttons
- Fix active slot tap pass-through for swap warning flow
- Fix _leveling_header_card type annotation
- Fix type mismatch in ProductionHeader.update()
- Fix type mismatch crash from P88 production header change
- Add swap warning modal when replacing active queue item
- Progress persistence UI — partial progress indicators
- Add tap-to-inspect + press feedback to LEVELING/PRODUCTION headers
- Forge LEVELING mode shows armament roster cards
- Hero roster uses LevelingHeaderCard in LEVELING mode
- Fix locked tab toast not firing
- Reconcile cheat snapshots with inverse storage caps
- Fix LEVELING sections leaking into PRODUCTION mode
- Fix FilterPanel lingering on mode switch
- Fix locked tab L prefix + add lock message on tap
- Fix hero cap tables — add low-level entries + floor lookup
- Fix L HEROES tab label + Builder 999 max level + Library/Forge confirmation
- Wire inverse storage lookups in GameManager + remove old constants
- Add inverse storage config fields — hero/guard/armament cap tables + helpers
- Fix compile errors in extracted components — missing preloads
- Extract filter controller + consolidate card builders + dead code cleanup
- Consolidate text color hierarchy from 4 to 2 chrome levels
- Panel borders on content panels + O/D/U section header colors
- Three QA fixes — recruit count, filter margin, queue borders
- Fix Details button colors, hero name colors, Details disappearing bug
- Palette change waits for Done button instead of auto-reload
- Revert dynamic tab margins + fix DISCOVERY filter + tab visibility
- Filter area background matches selected tab color
- Fix compile error — := with Variant return from max()
- TabBar full-width tabs via dynamic margins
- TabBar cosmetics — even spacing + connected selected tab
- Replace custom tab bar with native Godot TabBar
- Fix overflow — hide gap line container entirely
- Analyzer agent — GODOT_QUIRKS authority rule + overflow regression check
- Fix gap line positioning — restore SIZE_FILL + PAD_SCREEN margins
- Fix tab underline overflow with flexible ColorRects
- Add tab area drill-down diagnostic
- Add delayed _main_vbox audit diagnostic
- Zero mode bar margins, add 1.0s timer diagnostic
- Fix mode bar overflow, remove diagnostics
- Add mode bar diagnostic
- Add analyzer, implementer, validator subagents to .claude/agents/
- Add diagnostic to find wide child in _main_vbox
- Manual button width distribution for tab/mode bars
- Tab/mode bar overflow fix — force minimum size reset
- Diagnostic prints for mode/tab bar overflow
- Verify SIZE_EXPAND_FILL already present in tab/mode bars
- Palette const→var conversion (18 chrome colors)
- Tab visibility + mode bar overflow fix
- Fix tab bar overflow — force minimum size recalculation
- Add _clamp_to_viewport fix + P23 diagnostic for tab overflow
- Diagnostic prints for tab bar overflow — position data
- Remove DIAG-P20 prints + rename heroes tab ID to barracks
- Diagnostic prints for tab bar layout sizing
- Fix tab bar overflow — constrain button widths on cold start
- Fix cold start tab visibility + Escape on all overlays
- Fix snapshot cold start mode reset + remaining warnings
- Fix snapshot UI reset to PRODUCTION + clean up Godot warnings
- Fix snapshot tab init + Escape key closes all overlays
- Persist selection screen filter state per queue
- Create FilterPanel component — self-contained filter toggle + options
- Watchdog diagnostic for filter options row visibility and position
- Diagnostic prints for filter bar layout sizes
- Fix filter options row init
- Fix filter options row init — sync visibility with saved expanded state
- Fix filter bar corruption — disable _process() on hidden tabs
- Clean roster section architecture, remove diagnostics
- Diagnostic prints for filter bug + roster section collapsibility fix
- Fix hero roster display — group by class, remove misleading cap
- Restore filter toggle as standalone row with persistence
- Fix filter bar visibility by removing clipped toggle button
- Per-subtab section state + filter bar on tab switch
- Game-design-items-v8 — building gate table, map update, Library 9 categories
- Game-balance-lab-contents-v7 — Library 9-category redesign
- Library 9-category redesign, building gate table, map update
- Update cheat panel version constants for new patch
- PRODUCTION mode redesign — queue slots, selection screen, detail modal, component extraction, visual fidelity pass
- Implementation-plan v51 (roadmap through v0.0.29), style-changelog v13 (visual fidelity pass entry)

Behind the scenes:
- Style-changelog v14, implementation-plan v54 — Session 8 updates
- Architecture-components v4, style-changelog v14, implementation-plan v54
- GODOT_QUIRKS v4 — upgrade Variant type inference to Battle-Tested, add max/min/clamp to known Variant functions
- GODOT_QUIRKS v3 — correct Dynamic ColorRect rule (SIZE_FILL + min=0 collapses, use calculated width)
- GODOT_QUIRKS v2 — add dynamic ColorRect minimum size, diagnostic timing lessons
- Dev-journal v7 — fix what blocks the eyes entry
- Game-architecture-components v3
- Game-design-open-issues v27
- Game-design-contents v2, game-design-open-issues v27, game-architecture-components v3

## v0.0.29-P100

- Add DismissButton component and wire into selection screen
- Fix selection screen card names to use category colors
- Fix queue slot visual borders to match style-management-v6 spec
- New component + wiring — universal ExitButton for overlay screens
- Fix detail modal action verb and queue slot tap target
- Component extraction — create RenameModal component
- Fix swap flow cancel-before-start for library, forge, and barracks tabs

Behind the scenes:
- Style-components v5 (dismiss pattern Section 9), style-modals v3 (per-modal dismiss text), implementation-plan v50 (visual fidelity scope)

## v0.0.29-P92

- Diagnostic — _saved_progress system and swap flow analysis
- Fix swap flow — active queue slot tap opens selection screen with swap warning
- Color() cleanup — convert theme matches, mark game world and derived colors
- Factory cleanup sweep — assess and convert remaining StyleBoxFlat calls across all files
- Create SelectionData adapter — prepare card configs from game state

Behind the scenes:
- Implementation-plan v49 (swap timer bug detail, hero level-up diagnostic), journal v6 (Session 10 entry)
- Open-issues v26 (stale items resolved), parking-lot v3 (QA automation roadmap, component extraction resolved)
- Game-architecture-components v2, dev-implementation-plan v48 — Session 9 updates

## v0.0.29-P76

- Create ProductionHeader component — maker tab header for PRODUCTION mode
- Create ContentSection component — collapsible section with header, chevron, count
- Fix Forge CHEAT FINISH — handler now covers craft queue type
- Create ResourceBar + FilterBar components, wire into both screens (Phase 2 Chunk 4)
- Create QueueSlot + QueueCard components (extraction Phase 1 Chunk 1a)
- Remove slot count, fix button overlap, match filter checkbox style
- Polish — wallet format, checkbox toggles, remove slot count, fix button overlap
- Restore cheat finish + cancel buttons on active queue slots
- Fix generic affordability, 3 filters, wallet bar, checkbox visibility
- Fix overlay — PanelContainer multi-child instead of Container wrapper
- Overlay all non-normal card states, disable action button when can't afford
- Card states overhaul — queued overlay, action text Row 2, remove pin border, can't-afford dimming
- Selection card 3-row redesign, pin moved to detail modal, bug fixes A/D/E
- Fix queue timer — clear and repopulate _queue_slot_widgets on tab switch, remove diagnostic prints
- Runtime diagnostic — trace queue timer update chain in PRODUCTION mode
- Bump SUB_PATCH to P57 — Code silently skipped this in wip-57 through wip-61
- Fix level overflow, lock reason in detail modal, card contrast
- Fix queue timer regression from mode-aware refactor + fix "remaining remaining" text duplication
- Fix palette switch ghost content — remove management screen refresh on palette change
- Palette system — swappable color themes with 3 presets (hearthfire/frosthold/verdant), settings UI picker, swatch preview
- Modular layer stylebox factories — single source of truth for all background/border styles
- Fix missing slot borders + restore slot tap interaction after 3-band restructure
- New color system + Tower-style queue slot layout — 6 background layers, accent tokens, 3-band slot structure
- Verify XP skip sharing + remove COST_DEBUG prints
- Queue slot pills below progress bar — Tower LAB layout match
- Modular color contrast — widen BG_* luminance steps in ThemeConstants
- Fix heroes queue visibility, level-up skip state, inner contrast, cost debug
- Queue slot layout redesign — The Tower LAB style
- Cost diagnostic, hero level-up confirmation, favorites rename, card contrast
- Fix missing costs on cards, hero level-up mode check, pinned section rebuild
- Dev-implementation-plan v45→v46 — Chunk 10 progress from Session 4
- QA round 2 — restore card costs, swap warning fix, hero XP check, remove GCC, last completed text, pills
- Design cleanup — costs layout, tappable locked/maxed, skip all, last-completed level, placeholder pills
- Critical fixes — revert hero detail, selection close button, category headers, slot routing
- Remaining fixes — hero level-up confirmation, tab switch glitch, barracks mode display
- Pin feature with disk persistence + progress save on swap
- Queue card features — second slot fix, info card removal, gold complete, last-completed, placeholder pills, swap warning
- Selection screen layout — ThemeConstants fonts, costs right of name, lock specificity, category headers
- Remove superseded doc versions — v44/v1/v3 replaced by v45/v2/v4
- Doc cleanup — push journal v4, remove stale files
- Detail_modal filters already-skipped currencies before showing confirmation modal
- Confirmation modal uses text labels instead of emoji, removes _get_currency_icon
- Selection screen uses full viewport with 4px margins
- Selection screen polish — 2-column grid, collapsible categories, search, filters
- SUB_PATCH bump to P32
- Multi-resource confirmation modal + center all modals
- Two-step flow — card tap → detail modal → Build → confirm → queue starts
- Queue re-tappable + selection screen costs + Library badge fix
- Audit + fix production card regressions on non-production modes
- Fix regression — production cards mode-aware visibility
- Generic SelectionScreen + wire Library/Forge/Barracks slot taps
- Fix clipping + CHEAT FINISH + hide filter bar on production cards
- Queue slot providers for all maker tabs + info card label fix
- Slot count rendering on forge/barracks
- Clean PRODUCTION view — cards only, hide rows/subtabs/old queue
- Fix selection screen builder level check for upgrades
- Chunk 9 — full flow wiring (slot tap → selection → queue)
- Chunk 8 — selection screen bottom sheet
- Chunk 7 — slot tap interaction with detail modal
- Chunk 6 — two-card PRODUCTION layout for builder tab
- Restore XP confirmation for header Level Up button
- Fix build 1/1 rows use gold styling like upgrade completions
- Fix gold star panel styling on maker tabs
- Chunks 2+3 — gold star for maxed upgrade rows + DIAGNOSTIC cleanup
- Tab_base function extraction for chunk 2+3
- Confirmation modal wiring extraction
- Delete superseded dev-technical-reference-v1
- Forge 10-level chain, barracks 23-level chain, fix builder level gates
- Remove control stat category + delete 7 superseded doc versions
- Replace placeholder with actual entities v11 content
- Replace placeholder with actual progressions v8 content
- Entities fix header formatting
- Entities header fix + progressions restore GUI sections
- Progressions restore GUI reference sections
- Tech-reference fix old cross-refs, strip changelog
- Entities fix header, cross-refs, strip changelog
- Tech-reference expanded with Build Notes and Code directives
- Entities doc review trim
- Impl-plan Build Notes moved to tech-reference
- Progressions trimmed - cross-refs replace duplicated content
- Open-issues with entries 49-50 in correct format
- Dev-journal header fix
- Doc review cleanup part 1
- Update game-design-contents with ownership annotations
- Replace game-style-management-v6 stub with full content
- Replace dev-implementation-plan-v44 stub with roadmap content
- Replace glossary-v2 stub with full content
- Re-add glossary-v2 (was deleted during reorg cleanup)
- Update game-style-management-v6 stub with pointer to project knowledge
- Update dev-implementation-plan-v44 stub with pointer to project knowledge
- Add game-design-closed-issues-v1
- Add dev-journal-v3 (was missing from reorg)
- File reorg renames and cleanup
- Add game-style-modals and game-architecture-data-systems (renames)
- Add game-style-battle and glossary (renames)
- Add game-style-contents, dev-technical-reference, dev-parking-lot, game-business-infrastructure
- Add game-design-open-issues (from gdd-tracking split)
- Add game-design-world (rename from gdd-world + mystery section)
- Add game-design-combat (rename from gdd-combat)
- Add game-design-contents and game-design-narrative (rename from narrative-beats)
- Add new game-design-philosophy, game-design-loop, game-design-economy from gdd-core/gdd-meta split
- Fix Discord notification commit message check, add .gitattributes for line endings
- LEVELING Mode Complete — card headers, filters, upgrade juice, gold star maxed rows, confirmation modals, NumberFormat
- Connect hero level-up to confirmation modal system, P71
- Fix checkbox visibility, add XP confirmation, verify currency reusability, P70
- Fix confirmation modal — only skip when checkbox is checked, P69
- Bundle 4 Chunk 7 — Tier 3 confirmation modals for resource spending, P68
- Locked rows in Affordable filter, active-tab-only filtering, P67
- Filter rewrite v2 — data-driven section visibility, comprehensive mode handling, P66
- Remove leftover _reapply_filters calls from filter rewrite, P64
- Filter system rewrite — one function, two call sites, consistent behavior, P63
- Fix over-correction — restore ODU visibility during rebuild, keep STATS guard, P62
- Fix STATS duplication in LEVELING — guard _content_section from filter re-show, P61
- UI duplication in LEVELING mode — STATS section + ODU sections
- Fix section header visibility with active filters, P60
- Fix duplicate ODU rows on refresh, propagate filter state to all tabs, remove debug prints, P59
- Filter diagnostic prints + label fix, P58
- Reactive filters on all state changes, label clarity, tab-switch re-apply, P57
- Reactive filters, filter layout fix, dramatic MAX celebration, P56
- Permanent gold styling for maxed rows + longer MAX celebration, P55
- Amplify juice effects — dramatic row flash, visible label pop, button compress, P54
- Fix juice — suppress auto-refresh during animation, remove debug prints, P53

Behind the scenes:
- Push FULL game-architecture-principles-v14 (replacing abbreviated version from earlier push)
- Push FULL game-design-open-issues-v25 (replacing placeholder from earlier push)
- Push FULL dev-implementation-plan-v47 (replacing placeholder from earlier push)
- Dev-journal v5 — FULL version with all entries preserved (replacing broken push that deleted v4 entries)
- Update architecture-principles v14, implementation-plan v47, open-issues v25 — four-concern separation, Session 8 progress, component extraction tracking
- Add game-architecture-components-v1 — component architecture, four-concern separation, extraction phases
- Update dev-parking-lot to v2 — mark confirmation refactor resolved, add push failure notes
- Update dev-implementation-plan to v45 — mark v0.0.23 chunks 1-9 as built
- Add QA testing conventions to dev-technical-reference
- Items v7 — Sentry Towers to offense, soft cap notes, gathering TBD, blueprint/labs labels, gear slots all Phase 1
- Data-core v11 — stat table rewrite matching code, UVM status, posting fix
- Progressions v8 + entities v11 — audit resolutions applied
- Style guide v4 — expand damage type colors from 5 to 13
- Glossary v3 — Character/Player entry, Sentry Towers = offense, Control removed, damage types added
- Update code-truth audit v2 — all 17 resolutions decided
- Add code-truth audit v1 — 17 discrepancies between docs and code
- Style-management-v6 placeholder (full content via Claude Code)
- Style-modals-v2 + game-design-document-v43 (version bumps)
- V0.0.23 design spec and implementation chunks

## v0.0.29-P40

- Fix level overflow, lock reason in detail modal, card contrast
- Dev-implementation-plan v45→v46 — Chunk 10 progress from Session 4
- QA round 2 — restore card costs, swap warning fix, hero XP check, remove GCC, last completed text, pills
- Design cleanup — costs layout, tappable locked/maxed, skip all, last-completed level, placeholder pills
- Critical fixes — revert hero detail, selection close button, category headers, slot routing
- Remaining fixes — hero level-up confirmation, tab switch glitch, barracks mode display
- Pin feature with disk persistence + progress save on swap
- Queue card features — second slot fix, info card removal, gold complete, last-completed, placeholder pills, swap warning
- Selection screen layout — ThemeConstants fonts, costs right of name, lock specificity, category headers
- Remove superseded doc versions — v44/v1/v3 replaced by v45/v2/v4
- Doc cleanup — push journal v4, remove stale files
- Detail_modal filters already-skipped currencies before showing confirmation modal
- Confirmation modal uses text labels instead of emoji, removes _get_currency_icon
- Selection screen uses full viewport with 4px margins
- Selection screen polish — 2-column grid, collapsible categories, search, filters

Behind the scenes:
- Update dev-parking-lot to v2 — mark confirmation refactor resolved, add push failure notes
- Update dev-implementation-plan to v45 — mark v0.0.23 chunks 1-9 as built

## v0.0.29-P32

- SUB_PATCH bump to P32
- Multi-resource confirmation modal + center all modals
- Two-step flow — card tap → detail modal → Build → confirm → queue starts
- Queue re-tappable + selection screen costs + Library badge fix
- Audit + fix production card regressions on non-production modes
- Fix regression — production cards mode-aware visibility

Behind the scenes:
- Add QA testing conventions to dev-technical-reference

## v0.0.29-P27

- Generic SelectionScreen + wire Library/Forge/Barracks slot taps
- Fix clipping + CHEAT FINISH + hide filter bar on production cards
- Queue slot providers for all maker tabs + info card label fix
- Slot count rendering on forge/barracks
- Clean PRODUCTION view — cards only, hide rows/subtabs/old queue
- Fix selection screen builder level check for upgrades
- Chunk 9 — full flow wiring (slot tap → selection → queue)
- Chunk 8 — selection screen bottom sheet
- Chunk 7 — slot tap interaction with detail modal
- Chunk 6 — two-card PRODUCTION layout for builder tab
- Restore XP confirmation for header Level Up button
- Fix build 1/1 rows use gold styling like upgrade completions
- Fix gold star panel styling on maker tabs
- Chunks 2+3 — gold star for maxed upgrade rows + DIAGNOSTIC cleanup
- Tab_base function extraction for chunk 2+3
- Confirmation modal wiring extraction
- Delete superseded dev-technical-reference-v1
- Forge 10-level chain, barracks 23-level chain, fix builder level gates
- Remove control stat category + delete 7 superseded doc versions
- Replace placeholder with actual entities v11 content
- Replace placeholder with actual progressions v8 content
- Entities fix header formatting
- Entities header fix + progressions restore GUI sections
- Progressions restore GUI reference sections
- Tech-reference fix old cross-refs, strip changelog
- Entities fix header, cross-refs, strip changelog
- Tech-reference expanded with Build Notes and Code directives
- Entities doc review trim
- Impl-plan Build Notes moved to tech-reference
- Progressions trimmed - cross-refs replace duplicated content
- Open-issues with entries 49-50 in correct format
- Dev-journal header fix
- Doc review cleanup part 1
- Update game-design-contents with ownership annotations
- Replace game-style-management-v6 stub with full content
- Replace dev-implementation-plan-v44 stub with roadmap content
- Replace glossary-v2 stub with full content
- Re-add glossary-v2 (was deleted during reorg cleanup)
- Update game-style-management-v6 stub with pointer to project knowledge
- Update dev-implementation-plan-v44 stub with pointer to project knowledge
- Add game-design-closed-issues-v1
- Add dev-journal-v3 (was missing from reorg)
- File reorg renames and cleanup
- Add game-style-modals and game-architecture-data-systems (renames)
- Add game-style-battle and glossary (renames)
- Add game-style-contents, dev-technical-reference, dev-parking-lot, game-business-infrastructure
- Add game-design-open-issues (from gdd-tracking split)
- Add game-design-world (rename from gdd-world + mystery section)
- Add game-design-combat (rename from gdd-combat)
- Add game-design-contents and game-design-narrative (rename from narrative-beats)
- Add new game-design-philosophy, game-design-loop, game-design-economy from gdd-core/gdd-meta split
- Fix Discord notification commit message check, add .gitattributes for line endings

Behind the scenes:
- Items v7 — Sentry Towers to offense, soft cap notes, gathering TBD, blueprint/labs labels, gear slots all Phase 1
- Data-core v11 — stat table rewrite matching code, UVM status, posting fix
- Progressions v8 + entities v11 — audit resolutions applied
- Style guide v4 — expand damage type colors from 5 to 13
- Glossary v3 — Character/Player entry, Sentry Towers = offense, Control removed, damage types added
- Update code-truth audit v2 — all 17 resolutions decided
- Add code-truth audit v1 — 17 discrepancies between docs and code
- Style-management-v6 placeholder (full content via Claude Code)
- Style-modals-v2 + game-design-document-v43 (version bumps)
- V0.0.23 design spec and implementation chunks

## v0.0.29-P1

- First published build.
