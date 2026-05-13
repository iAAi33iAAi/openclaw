# AGENTS.md

Alpha Intelligence governance. Root rules only. Read scoped AGENTS.md before subtree work.

## Identity

- Repo: https://github.com/iAAi33iAAi/openclaw
- Owner: John David Taylor Preston -- Founder-Architect, Alpha Intelligence
- Fork of: openclaw/openclaw (upstream) -- customized for Alpha Intelligence sovereign platform
- Mission: Sovereign technology for affordable housing, decentralized energy, transparent governance, and universal economic dignity

## Start

- Replies: repo-root refs only. No absolute paths, no ~/.
- Run docs list first: pnpm docs:list if available; read relevant docs only.
- High-confidence answers only when fixing/triaging: verify source, tests, and behavior before deciding.
- Dependency-backed behavior: read upstream dependency docs/source/types first.
- Missing deps: pnpm install, retry once, then report first actionable error.
- Alpha Intelligence skill: always load .agents/skills/alpha-intelligence/SKILL.md for ecosystem context.

## Alpha Intelligence Ecosystem

This repo is the OpenClaw gateway layer of the Alpha Intelligence platform.

| Repo | Layer | Purpose |
|---|---|---|
| ALEXARAC | UI | Sovereign platform dashboard -- 9 IPs, 16 tabs |
| alpha-intelligence-hub | Orchestration | Docker-orchestrated LLM + governance hub |
| safety-kernel | Governance | Fail-closed AI safety engine -- 65/65 tests passing |
| project-mono | Runtime | ALGA_FOLD_KERNEL + QUIBIDT 1440 Treasury |
| crew-colony | Agents | Multi-agent sovereign crew |
| undermoon | Infrastructure | Rust coordination substrate |
| World-Tribe-Protocol | Contracts | 6-Sided Civilization OS -- Solidity |
| CORE_CODEX.md | Philosophy | Foundational design principles |
| openclaw (this repo) | Gateway | AI assistant platform customized for Alpha Intelligence |

## Repo Map

- Core TS: src/, ui/, packages/
- Plugins: extensions/
- SDK: src/plugin-sdk/*
- Channels: src/channels/*
- Loader: src/plugins/*
- Protocol: src/gateway/protocol/*
- Docs/apps: docs/, apps/, Swabble/
- Alpha Intelligence additions: .agents/, .pi/, git-hooks/

## Architecture

- Core stays extension-agnostic.
- Extensions cross into core only via openclaw/plugin-sdk/*, manifest metadata, injected runtime helpers, documented barrels.
- Alpha Intelligence governance skills live in .agents/skills/alpha-intelligence/.
- Follow CORE_CODEX.md principles for all contributions.

## Commands

- Runtime: Node 22+
- Install: pnpm install
- CLI: pnpm openclaw ... or pnpm dev; build: pnpm build
- Tests: pnpm test, pnpm test:changed
- Typecheck: pnpm tsgo* lanes only
- Formatting: oxfmt -- pnpm format:check / pnpm format
- Linting: pnpm lint:*

## Git

- Commits: conventional-ish, concise, grouped
- Branch: main
- No merge commits; rebase on latest origin/main before push
- Alpha Intelligence changes: prefix feat(ai):, fix(ai):, docs(ai):

## Code

- TS ESM, strict. Avoid any; prefer real types.
- No @ts-nocheck. Lint suppressions only intentional + explained.
- Comments: brief, only non-obvious logic.
- American English spelling.

## Tests

- Vitest. Colocated *.test.ts.
- Clean timers/env/globals/mocks after each test.
- Do not run multiple independent pnpm test commands concurrently.

## Security

- Never commit credentials, phone numbers, or live config.
- Secrets in ~/.openclaw/credentials/.
- All Alpha Intelligence governance changes require review against CORE_CODEX.md principles.

## Governance Principle

No matter how. No matter what. No matter why. No matter when. No matter where.
There is a place here for all that live.
