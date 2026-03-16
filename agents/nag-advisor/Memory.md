# Nag's Memory

## Dependency Map
<!-- Format: source_change → what_needs_updating | reason -->
- agents/*/soul.md change → README.md | agent table may need updating
- agents/*/rules.md change → README.md | agent descriptions may be stale
- agents/ new folder → README.md | agent count and table need updating
- agents/ new folder → docs/index.html | presentation team slide needs updating
- agents/ new folder → Rick README.md | Demo Universe agent count reference may be stale
- workflows/*.yaml change → README.md | workflow table may need updating
- .rick/config.yaml change → README.md | project metadata may be stale
- cli/src/core/agent.rs change → README.md (Rick repo) | agent file structure docs may be stale
- cli/src/core/agent.rs change → docs/index.html | presentation "Anatomy of an Agent" slide may be stale
- cli/src/cli/commands.rs new command → README.md (Rick repo) | CLI command list needs updating
- cli/src/cli/commands.rs new command → SKILL.md | skill command list needs updating
- integrations/claude-code/skill/SKILL.md change → README.md (Rick repo) | feature descriptions may be stale
- agents/*/Memory.md added → docs/index.html | presentation may need to mention Memory feature
- new agent added → docs/index.html | presentation "Meet the Demo Team" slide needs updating
- uncommitted changes in both repos → risk of drift between what's pushed and what's local
- presentation exists in 3 places → rick-presentation.html (Rick repo), .rick/presentation.html (Demo), docs/index.html (github-pages branch) — all must stay in sync

## Recent Changes Log
<!-- Important changes I observed -->
- Memory upgrade: agents now have Memory.md (4th file: soul.md, rules.md, tools.md, Memory.md)
- Agent struct in agent.rs gained `memory` field, loaded from Memory.md
- Compiled agents now include ## Memory and ## Memory Management sections
- Rick's own Memory.md created at ~/.rick/persona/Memory.md
- `rick setup` now creates Memory.md alongside soul.md and rules.md
- SKILL.md updated with full Agent Memory documentation section
- All 6 original Demo Universe agents got starter Memory.md files
- I (Nag) was added as the 7th agent — Advisor role, background parallel execution
- All 3 workflows updated: nag step added at end with parallel: true, checkpoint: false
- SKILL.md updated with "Nag (Background Advisor)" section for ambient invocation
- Presentation (docs/index.html) was created with 12 slides, hosted via GitHub Pages at https://sagi363.github.io/Demo-Rick-Universe/
- 2026-03-16 scan: Both repos have significant uncommitted work (Memory + Nag features)
- 2026-03-16 scan: Demo Universe README.md (working tree) is updated with Nag, but not committed
- 2026-03-16 scan: Demo Universe workflows (working tree) have Nag steps, but not committed
- 2026-03-16 scan: Rick CLI has uncommitted changes to agent.rs, commands.rs, SKILL.md (Memory feature)
- 2026-03-16 scan: Presentation in all 3 locations still says "6 agents" — should be 7
- 2026-03-16 scan: Presentation "Anatomy of an Agent" slide lists 3 files (soul/rules/tools) — missing Memory.md
- 2026-03-16 scan: Rick README.md says "5 agents" in Demo Universe description (line 59)
- 2026-03-16 scan: Rick README.md agent section only lists soul.md, rules.md, tools.md — no Memory.md
- 2026-03-16 scan: CLAUDE.md (Rick repo) project structure doesn't mention Memory.md as part of agent structure
- 2026-03-16 scan: github-pages branch in Demo Universe is behind main — doesn't have Nag or Memory changes
- 2026-03-16 scan: rick-presentation.html is untracked in Rick repo (not committed)
- 2026-03-16 scan: Nag agent folder is untracked in Demo Universe (not committed)
- 2026-03-16 scan: All 7 Memory.md files for agents are untracked in Demo Universe

## Past Suggestions
<!-- Format: date | suggestion | status -->
- 2026-03-16 | Commit uncommitted changes in both repos (Memory + Nag features) | pending
- 2026-03-16 | Update all 3 presentations: "6 agents" → "7 agents", add Memory.md to anatomy slide | pending
- 2026-03-16 | Rick README.md line 59: "5 agents" → "7 agents" | pending
- 2026-03-16 | Rick README.md: add Memory.md to agent file structure docs (lines 108-120, 166) | pending
- 2026-03-16 | CLAUDE.md: add Memory.md to Key Architecture Decisions or agent description | pending
- 2026-03-16 | Merge github-pages branch with main in Demo Universe or rebase it | pending
- 2026-03-16 | Rick README.md persona section (line 232): Memory.md says "created at runtime" but it's now created by `rick setup` | pending

## User Preferences
<!-- Format: pattern | user response -->
