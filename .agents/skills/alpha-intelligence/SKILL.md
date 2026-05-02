# Alpha Intelligence Ecosystem Skill

You are an agent operating within the Alpha Intelligence sovereign technology platform. This skill gives you full context on the ecosystem, its repos, architecture, and mission.

## Founder

John David Taylor Preston -- Founder-Architect, Bethel Acres, Oklahoma.

## Mission

Build sovereign technology platforms that put people first -- affordable housing, decentralized energy, transparent governance, and universal economic dignity -- through open-source technology built with integrity.

Core Principle: "No matter how. No matter what. No matter why. No matter when. No matter where. There is a place here for all that live."

## Repository Map

| Repo | Purpose | Stack | Key Files |
|---|---|---|---|
| ALEXARAC | Alpha Intelligence Galactic HQ -- unified sovereign platform with 9 IPs and 16 operational tabs | HTML5, JavaScript, CSS | index.html, tabs/, assets/ |
| alpha-intelligence-hub | Master LLM Platform -- AI, cryptocurrency, and sovereign governance hub with Docker orchestration | Shell, Makefile, Docker | docker-compose.yml, init-hub.sh, requirements.txt |
| safety-kernel | Fail-closed governance engine for AI safety -- tamper-proof execution proofs | Python | sk/, test_sk.py, test_tamper.py, pyproject.toml |
| project-mono | Unified monorepo with ALGA_FOLD_KERNEL governance runtime and append-only Knowledge Ledger | Python, Shell | Various modules |
| undermoon | Modular coordination substrate for identity, governance, shelter, economy, safety, and continuity | Rust | Cargo.toml, src/ |
| World-Tribe-Protocol. | 6-Sided Civilization OS for universal equilibrium -- Solidity smart contracts | Solidity, Python | contracts/, tests/ |
| CORE_CODEX.md | Canonical public codex -- foundational principles and design philosophy | Markdown | CORE_CODEX.md |
| openclaw (fork) | Personal AI assistant platform -- OpenClaw fork customized for Alpha Intelligence | TypeScript | AGENTS.md, skills/, src/ |

## Architecture Relationships

```
ALEXARAC (Dashboard UI)
    +-- alpha-intelligence-hub (Orchestration Layer)
    |   +-- safety-kernel (Governance Engine)
    |   +-- World-Tribe-Protocol. (Smart Contracts)
    |   +-- undermoon (Coordination Substrate)
    |   +-- project-mono (Unified Runtime)
    +-- CORE_CODEX.md (Design Philosophy)
```

- ALEXARAC is the user-facing sovereign platform dashboard
- - alpha-intelligence-hub consolidates all sub-repos into a Docker-orchestrated monorepo
  - - safety-kernel enforces fail-closed AI governance with tamper-proof execution proofs
    - - undermoon provides the modular coordination substrate (Rust-based)
      - - World-Tribe-Protocol. implements the 6-Sided Civilization OS via Solidity smart contracts
        - - project-mono contains the ALGA_FOLD_KERNEL governance runtime
          - - CORE_CODEX.md documents the foundational principles
           
            - ## Sub-Systems (9 IPs)
           
            - 1. OpenClaw Gateway -- AI assistant integration
              2. 2. Quibidt 1440 Treasury -- Decentralized currency system
                 3. 3. World-Tribe Protocol -- Civilization OS smart contracts
                    4. 4. Safety Kernel -- AI governance engine
                       5. 5. Aethel Grid Validator -- Rust-based validation layer
                          6. 6. ALEXARAC UI -- Sovereign platform dashboard
                             7. 7. Platform Dashboard -- Operational monitoring
                                8. 8. Undermoon OS -- Coordination substrate
                                   9. 9. Civics OS -- Governance interface
                                     
                                      10. ## Tech Stack Reference
                                     
                                      11. - Python: safety-kernel (pytest, pyproject.toml), project-mono, World-Tribe-Protocol tests
                                          - - Rust: undermoon (Cargo workspace)
                                            - - Solidity: World-Tribe-Protocol smart contracts
                                              - - Shell/Makefile: alpha-intelligence-hub orchestration
                                                - - HTML5/JS/CSS: ALEXARAC dashboard
                                                  - - Docker: alpha-intelligence-hub containerization
                                                    - - TypeScript: openclaw fork
                                                     
                                                      - ## Working With This Ecosystem
                                                     
                                                      - When asked to work on Alpha Intelligence:
                                                     
                                                      - - Identify the target repo from the map above
                                                        - - Understand the layer -- is it UI (ALEXARAC), orchestration (hub), governance (safety-kernel), contracts (World-Tribe), infrastructure (undermoon), or runtime (project-mono)?
                                                          - - Check dependencies -- changes to safety-kernel may affect alpha-intelligence-hub; changes to undermoon affect the coordination layer
                                                            - - Follow the codex -- CORE_CODEX.md defines design principles; all code should align with those principles
                                                              - - Test thoroughly -- safety-kernel has 65/65 tests passing; maintain that standard across all repos
                                                               
                                                                - ## GitHub Organization
                                                               
                                                                - - Owner: iAAi33iAAi
                                                                  - - All repos: Public, MIT License
                                                                    - - CI: GitHub Actions where configured
                                                                      - - Primary branch: main
