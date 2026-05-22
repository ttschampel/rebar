# Changelog

All notable changes to rebar. Versioned with [semver](https://semver.org/).

**Versioning policy:**
- **Major** — breaking changes to contract format, agent role structure, CLI interface, or enforcement script API
- **Minor** — new agents, templates, practices, profiles, scripts
- **Patch** — doc fixes, script bug fixes, template clarifications

---

## 1.0.0 (2026-05-22)


### Features

* add enforcement scripts, conventions, PR template, and CI hook ([a11116c](https://github.com/ttschampel/rebar/commit/a11116c3f8a35da79f3c200559fdaf472b603c68))
* add install script for first-time setup ([053dead](https://github.com/ttschampel/rebar/commit/053dead16deb970c9c6677345eb5eb73740913d2))
* add merger agent to ask init ([6e08e8a](https://github.com/ttschampel/rebar/commit/6e08e8a32154962ef5dc14f6b7ebb0d8355b9dac))
* add steward quality scanner — automated project health reporting ([b3ecd48](https://github.com/ttschampel/rebar/commit/b3ecd48c8e84bed0b49f42d403eb6bdb1edec00b))
* add steward to ASK init + Purlin comparison in README ([de0874e](https://github.com/ttschampel/rebar/commit/de0874e0a1694a1383b7ca5dd5f3269884ba7ad2))
* add subagent LOE levels, merge coordinator, and actor agent pattern ([755fbd7](https://github.com/ttschampel/rebar/commit/755fbd753ec324fb2ba9b9a4bdb98f2fb90025b9))
* agent commands — unquoted words dispatch to role-specific scans ([f3089d5](https://github.com/ttschampel/rebar/commit/f3089d5cd0b7213d8024824cb659dde0fbdbf313))
* anonymize case study references — Dapple SafeSign → Human-based Digital Signer ([7fb2d62](https://github.com/ttschampel/rebar/commit/7fb2d62ac8b44a82a1e8f3ad516e8467eb58fb88))
* **architecture,scripts:** close out Wave 2 — D/O/T prefixes + Contract Health detection ([0c4b556](https://github.com/ttschampel/rebar/commit/0c4b556aa030aea8bc986260e285cd035fb155cc))
* **architecture:** contracts for rebar's load-bearing services + tag impls ([c298dea](https://github.com/ttschampel/rebar/commit/c298dea624b90e1fd63fe1049af8d57874431576))
* **architecture:** require Why/Who/Scenarios in CONTRACT-TEMPLATE ([66d002b](https://github.com/ttschampel/rebar/commit/66d002b50d327f11a922ef4a4f6bb40b81091aa6))
* **ask-server:** repo discovery recurses one level into non-repo dirs ([b5ae266](https://github.com/ttschampel/rebar/commit/b5ae26613bac1bf2c992267b6e08788da694ddab))
* **ask,mcp:** case-insensitive repo + role resolution ([8e8675c](https://github.com/ttschampel/rebar/commit/8e8675c61f9c8f7a3ce5f0f600c3768f93aa2008))
* bootstrap-ready template structure — copy and GO experience ([3becbf6](https://github.com/ttschampel/rebar/commit/3becbf6e34b8cfe2e6aa2f308e5633fe4686452b))
* CHARTER.md + ask featurerequest gated MCP intake role ([6df6b3d](https://github.com/ttschampel/rebar/commit/6df6b3d7e8e1a8df71f4c8ed7375e64f970ecba4))
* **charter:** §1.6 federation + §2.10 not-a-registry — federation Cluster 1 ([e79c56b](https://github.com/ttschampel/rebar/commit/e79c56b2b3769c357140e318bd275f08bb8e459e))
* **cli:** error-path polish — --version, did-you-mean, descriptions ([aca68d5](https://github.com/ttschampel/rebar/commit/aca68d5b91e211276d60b9ca301d581d76b0ee5e))
* **cli:** rebar audit --all recurses one level into non-repo dirs ([cdb2c45](https://github.com/ttschampel/rebar/commit/cdb2c45ce7c79657ff7f834152ffe3205ce9f5fd))
* document MCP enablement for ASK tool swarm coordination ([28410e2](https://github.com/ttschampel/rebar/commit/28410e2e3c8409fa9aae9d4673fa20ab28f62272))
* enterprise ASK server — multi-repo agents over HTTP with round-robin ([2fe2bba](https://github.com/ttschampel/rebar/commit/2fe2bba7bc002f18174a08baef9b92c1225b0bc5))
* full MCP protocol implementation for ASK agents ([6c4227a](https://github.com/ttschampel/rebar/commit/6c4227a4f1ccbbff4260972097a4cdd22bba57bb))
* **mcp:** activate ASK as first-class Claude Code tool (Wave 2.5) ([d9e68fc](https://github.com/ttschampel/rebar/commit/d9e68fc7cf76039eb6306d52ff185afd2931f915))
* **mcp:** caller-facing role preambles for tool descriptions ([2f52983](https://github.com/ttschampel/rebar/commit/2f5298331d6cd000df76ecc45a418473ed704757))
* **mcp:** repo discovery recurses one level into non-repo dirs ([5800647](https://github.com/ttschampel/rebar/commit/58006471fb7c0b0af968a91b553fb2851dbae0ce))
* progressive disclosure architecture — "easy to try and love, with layers of power" ([73b3b4d](https://github.com/ttschampel/rebar/commit/73b3b4da5bc6fc71b4cbdcd6fbb0b066a78d8ebc))
* prominently feature ASK tool in swarm coordination section ([ef8f319](https://github.com/ttschampel/rebar/commit/ef8f3198ad480e853b47cc144a29db523d9a7e4e))
* rebar audit, adopt, new CLI commands + MCP wiring + LLM backend ([24ea799](https://github.com/ttschampel/rebar/commit/24ea79982c93feb49e6ab799c46e1ed2a05f9cf5))
* rebar CLI — integrity verification, enforced commits, digital signatures ([506c01a](https://github.com/ttschampel/rebar/commit/506c01aac282fe6a4271aca15e9ec5422303a870))
* rebar dogfoods rebar — 10/10 audit at Tier 3 ([1c76d94](https://github.com/ttschampel/rebar/commit/1c76d94e8d715c703346d85608957a7bf3832fba))
* rebar init bootstraps v2 files + README cleanup ([92ee243](https://github.com/ttschampel/rebar/commit/92ee2438013c4e22208f54d017a7c43d2d18e2bc))
* rebar v2.0.0 — session lifecycle, red team, CLI enhancements, The 10 Rules ([d02c30d](https://github.com/ttschampel/rebar/commit/d02c30dc4c67e3abad0616aaee824b118ef3d38b))
* **rebar:** adoption hygiene polish — skip-mcp + completions + paged log ([c517d25](https://github.com/ttschampel/rebar/commit/c517d255240924a66fae43b1f7bae5e19545d34e))
* **rebar:** cold-start completeness — agents/ + welcome + nudges ([b8894f6](https://github.com/ttschampel/rebar/commit/b8894f68c727462f5c5565af40c8222b8f6a6509))
* **rebar:** consumer-side federation commands — federation Cluster 4 ([5d2fbac](https://github.com/ttschampel/rebar/commit/5d2fbac27c85bd3d0c7a0da6ce892cd05ed3263f))
* **rebar:** federation compliance + docs — federation Cluster 5 ([2cbce75](https://github.com/ttschampel/rebar/commit/2cbce75247517c4432be35c205593a852165726e))
* reframe rebar as swarm coordination framework + TESTER agent + ask -w ([5d7cb8d](https://github.com/ttschampel/rebar/commit/5d7cb8d5611db04915fd6df332839bc4e431892e))
* scalability overhaul — slim templates, computed registry, tier enforcement, versioning ([94d0aa1](https://github.com/ttschampel/rebar/commit/94d0aa160ede62005f222a17d7a1a93b14aa1065))
* **scripts,practices:** close out Wave 3 — regression-fix gates G+I scripts + practice doc + H/L doctrine ([ddb44b8](https://github.com/ttschampel/rebar/commit/ddb44b830b909a4ce6575eaaf4d4ab9b9ca756a7))
* **scripts:** check-decay-patterns.sh — soft-hardening anti-pattern lens ([aafd9ba](https://github.com/ttschampel/rebar/commit/aafd9baed5403fe6f8f107e5c4ca135e8b5a950e))
* **scripts:** check-doc-refs.sh + repair 38 broken feedback links ([bd3b999](https://github.com/ttschampel/rebar/commit/bd3b99960172deee2c21be1a6fdb950ba67b5407))
* **scripts:** owner-side federation tooling — federation Cluster 3 ([c0f50bf](https://github.com/ttschampel/rebar/commit/c0f50bfde47f9fc46e2ee50d4f98df1ab26cbf28))
* **scripts:** test-e2e-live.sh — add live MCP tools/call keyword check ([ed7cc7f](https://github.com/ttschampel/rebar/commit/ed7cc7f9cb79cbe1eebad8c321c660a2e54007ed))
* **scripts:** test-e2e-live.sh — live smoke against claude + MCP + ASK server ([7ff1650](https://github.com/ttschampel/rebar/commit/7ff16500592778cba5f47144365d9bb2c3c2d2e5))
* **templates:** close out Wave 1 — bring slim adopter AGENTS.md to parity ([102fc0b](https://github.com/ttschampel/rebar/commit/102fc0b3421892527765b83a6d91c8c84c2386fc))
* **templates:** CONSUMES.md format spec + bootstrap — federation Cluster 2 ([614b353](https://github.com/ttschampel/rebar/commit/614b3530dc7004113568a60dcac225c9bfee29bf))
* **templates:** tag-to-CI coverage check (Node, project-specific) ([1ce0281](https://github.com/ttschampel/rebar/commit/1ce0281fc184a251c1f236d24b714019c5b9d8e5))
* v1.0 — ground truth enforcement, ASK Scoped Knowledge, field-tested feedback ([de49484](https://github.com/ttschampel/rebar/commit/de49484dc1db7836f751217247a98ba02156d33c))


### Bug Fixes

* **ask:** claude flag regressions — stream-json + -v leak ([b09f9fb](https://github.com/ttschampel/rebar/commit/b09f9fb3a44369fd10d4a0a3f86fadf67cdd53d1))
* **ask:** resilient session resume — replay on vanished claude session ([27a428d](https://github.com/ttschampel/rebar/commit/27a428d884f0ec8394e323c9c4b2d94f0d925c5f))
* **mcp:** extract full first paragraph for tool descriptions ([bc936cf](https://github.com/ttschampel/rebar/commit/bc936cf8ebbe3e7062da0452d3486f6dbb9f445a))
* **mcp:** ignore JSON-RPC notifications (stop triggering Claude Code ZodError) ([0db9073](https://github.com/ttschampel/rebar/commit/0db90735ba4511e56c599ff8a385764547811ae4))
* remove remaining rebar.dev reference in main README ([a195f1d](https://github.com/ttschampel/rebar/commit/a195f1d318e8a109de356d3c99f4f8b33ede6af3))
* remove stale KNOWN_ISSUES.md references ([971320d](https://github.com/ttschampel/rebar/commit/971320d7a6d5694342faba473bfd00e71e40a8a7))
* **scripts,mcp:** bash 3.2 path-norm, steward arg-skip, MCP error transparency ([0d5e6c3](https://github.com/ttschampel/rebar/commit/0d5e6c3879575983689d6d36ad3222ffec644f65))
* **scripts:** bash 3.2 compatibility + mechanical bootstrap-scripts sync ([0abb549](https://github.com/ttschampel/rebar/commit/0abb5495ea2b16a9c96dce094ef9325b46990202))
* **scripts:** drift-detector polish — pipefail, bin/ scan, template/archive opt-outs ([6a9be3d](https://github.com/ttschampel/rebar/commit/6a9be3d05abba0e87b0bfe5fe2347af3db7488d8))
* use GitHub repo paths instead of non-existent rebar.dev ([f9071b7](https://github.com/ttschampel/rebar/commit/f9071b7bfd69d057b4c8b063be806d60bef1736a))
* version scrub + broken links + naming clarity for public release ([1d51a15](https://github.com/ttschampel/rebar/commit/1d51a1502e68de75a6e33af788473e373f397c4d))

## v2.0.1 (2026-04-26)

### Fixed
- **`bin/ask` resilient session resume** — when `claude --resume <id>` returns "No conversation found with session ID …" (vanished `~/.claude` store, interrupted first call, server-side retention boundary), `_ask_direct` now wipes the stale `.session-id`, regenerates a fresh UUID, and replays the question once with full agent context. Prints `[<agent>] session expired, restarting fresh` to stderr so the recovery is visible. Retry is capped at one attempt and only fires on the specific stale-session signature — auth/network/rate-limit errors still surface immediately.

---

## v2.0.0 (2026-04-01)

### Added
- **Session lifecycle protocol** — `practices/session-lifecycle.md`: start/checkpoint/end framework with wrapup template, marathon session guidance, architect review checkpoints
- **Red team protocol** — `practices/red-team-protocol.md`: 5-persona adversarial review strategy (adversarial user, performance, security, fidelity, API/contract)
- **Visual fidelity methodology** — `practices/visual-fidelity.md`: ground truth, RMSE measurement, oracle pattern, human emulator tests, regression prevention
- **Red team subagent template** — `agents/subagent-prompts/red-team.md`: multi-persona template with structured JSON output and fix DAG
- **Product review subagent template** — `agents/subagent-prompts/product-review.md`: BDD alignment, persona fit, flow completeness, scope assessment
- **Seam contracts** — new contract type for integration points across language/protocol boundaries; `architecture/CONTRACT-SEAM-TEMPLATE.md`
- **`rebar context` CLI command** — context shepherd that cats role-relevant files in reading order (`rebar context`, `rebar context architect`, `rebar context session-start`, etc.)
- **Context refresh script** — `templates/project-bootstrap/scripts/refresh-context.sh`: automated QUICKCONTEXT staleness checker
- **Feedback status tracking** — `feedback/README.md` now includes `Status:` and `Template impact:` fields

### Changed
- **Cold Start Quad enhanced** — staleness verification step added between QUICKCONTEXT and TODO reads
- **AGENTS.template.md** — session lifecycle reference, priority tracking rule (QUICKCONTEXT is single source of truth), issue dedup rule
- **CLAUDE.template.md** — session-end protocol added, `refresh-context.sh` in health check
- **TODO.template.md** — forward-looking only (<50 lines open items), completed items in collapsed `<details>` section
- **QUICKCONTEXT.template.md** — "What's Next" section as canonical priority list
- **Worktree collaboration** — fan-out merge ordering strategy (HOT/WARM/COLD), shared mock consolidation rule, worktree lifecycle checklist, cherry-pick best practices
- **Multi-agent orchestration** — file-level conflict matrix and interface-change sequencing in pre-launch audit
- **UX review template** — interaction stability (human emulator) dimension added
- **Security surface scan template** — red team mode (adversarial mindset) section added
- **DESIGN.md** — seam contracts in §3 (The Contract System), session lifecycle in §5 (The Information Environment)
- **README.md** — battle-tested results updated with OpenDocKit (15+ agents, 8K tests) and filedag (40+ agents, 62 commits in 48hrs)

### Why v2.0

Three field reports from production deployments (Dapple SafeSign, OpenDocKit, filedag) converged on the same meta-insight: rebar's structural protocols work; its behavioral protocols don't. v2.0 addresses the session lifecycle gap, adds adversarial review and visual fidelity practices, introduces seam contracts for integration points, and adds the `rebar context` CLI command. The core contract system is unchanged — this is a methodology evolution, not a rewrite.

### Migration from v1.2.0
1. Copy new practice files: `practices/session-lifecycle.md`, `practices/red-team-protocol.md`, `practices/visual-fidelity.md`
2. Copy new subagent templates: `agents/subagent-prompts/red-team.md`, `agents/subagent-prompts/product-review.md`
3. Copy `architecture/CONTRACT-SEAM-TEMPLATE.md`
4. Copy `templates/project-bootstrap/scripts/refresh-context.sh` to your project's `scripts/`
5. Re-diff your AGENTS.md against the new template — session lifecycle and priority tracking sections are new
6. Re-diff your CLAUDE.md — session-end protocol and staleness verification are new
7. Consider shortening your TODO.md — move completed items to a collapsed section
8. Add a "What's Next" section to QUICKCONTEXT.md as your canonical priority list
9. Rebuild rebar CLI: `cd cli && go build -o ../bin/rebar .`
10. Update `.rebar-version` to `v2.0.0`

---

## v1.2.0 (2026-03-20)

### Added
- **Scalability overhaul** — AGENTS.template.md slimmed from 917 to 382 lines
- **`practices/` directory** — multi-agent orchestration, E2E testing, deployment patterns, worktree collaboration extracted as reference guides
- **Computed registry** — `scripts/compute-registry.sh` generates CONTRACT-REGISTRY.md from contract files on disk (replaces manual maintenance)
- **Memory compaction** — `ask compact <agent>` summarizes old memory entries, auto-triggers at 50KB threshold
- **Script versioning** — all scripts have `# rebar-scripts: YYYY.MM.DD` headers; steward detects stale copies
- **Tier-aware enforcement** — `.rebarrc` configures tier (1=partial, 2=adopted, 3=enforced); scripts skip inapplicable checks
- **Team-size profiles** — `profiles/solo-dev.md`, `profiles/small-team.md`, `profiles/department.md`
- **Conventions minimum viable** — Tier 1 section at top of conventions.md
- **Rebar version tracking** — `.rebar-version` file + README badge for adopting repos
- **Adoption level validation** — steward checks README badge against actual compliance
- **CHANGELOG.md** — you're reading it

### Changed
- `AGENTS.template.md` — mandatory foundations only; advanced practices moved to `practices/`
- `architecture/CONTRACT-REGISTRY.template.md` — now documents the computed format
- `scripts/check-registry.sh` — deprecated in favor of `compute-registry.sh`
- `scripts/steward.sh` — uses `compute-registry.sh --check`, adds compliance validation
- `scripts/ci-check.sh` — uses `compute-registry.sh --check`
- `conventions.md` — added minimum viable section for Tier 1
- `SETUP.md` — added tier selection, team-size profiles, practices/ copy step
- All profile files — updated section references for practices/

### Migration from v1.1.0
1. Copy `practices/` directory into your project
2. Copy `scripts/compute-registry.sh` and `scripts/_rebar-config.sh`
3. Create `.rebarrc` from `.rebarrc.template` (set your tier)
4. Create `.rebar-version` with `v1.2.0`
5. Add rebar badge to top of your README.md (see README.template.md)
6. Re-diff your AGENTS.md against the new AGENTS.template.md — moved sections are now in `practices/`
7. Run `scripts/compute-registry.sh` to generate your registry
8. Optional: update all scripts from rebar (check `# rebar-scripts:` dates)

---

## v1.1.0 (2026-03-19)

### Added
- Merger agent — branch integration + conflict resolution (actor agent)
- Subagent LOE levels in prompt index
- Scout Rule — zero tolerance for skipped or failing tests
- Adoption badges — PARTIAL / ADOPTED / ENFORCED tiers
- AI-native contracts feedback — cross-repo namespacing (`CONTRACT:namespace/ID`)
- Blindpipe adoption feedback — ASK as context preservation, role discipline pattern

### Changed
- `ask init` now creates merger agent directory
- `AGENTS.template.md` — added Scout Rule section, merge coordinator flow

### Migration from v1.0.0
1. Copy `agents/merger/` directory
2. Merge Scout Rule section into your AGENTS.md (§Testing Expectations)
3. Optional: add adoption badge to README.md

---

## v1.0.0 (2026-03-17)

### Added
- Cold Start Quad templates — README, QUICKCONTEXT, TODO, AGENTS
- CLAUDE.md template with full Claude Code configuration
- Contract system — CONTRACT-TEMPLATE, CONTRACT-REGISTRY, naming conventions
- Methodology.md — full philosophy document
- Conventions.md — branch naming, commits, headers, discovery taxonomy
- 5 enforcement scripts — contract-headers, contract-refs, TODOs, freshness, ground-truth
- Steward — automated project health scanner with JSON + markdown output
- CI check runner and pre-commit hook
- ASK CLI — role-based agent queries with persistent sessions
- 8 subagent templates — code review, contract audit, security scan, UX review, doc drift, feature inventory, test shard, merge coordinator
- 4 project profiles — web-app, api-service, crypto-library, cli-tool
- SETUP.md — step-by-step adoption guide
- METRICS template with ground truth verification
- Learnings from OpenDocKit — 37KB of battle-tested patterns

### Migration
This is the initial release. Follow SETUP.md.
