# Gustavo Gardusi

Systems software engineer specializing in backend architecture, distributed systems, containerization, and repository governance.

---

## Architecture Portfolio

### -1. Private Boundary

| Repository | Description |
| :--- | :--- |
| `private` *(Private)* | Secure vault backups, raw notes, and draft incubators for eventual public promotion |

### 0. Meta & Governance

| Repository | Description |
| :--- | :--- |
| [`.github`](https://github.com/gardusi-gustavo/.github) | Native GitHub platform defaults, reusable Actions workflows, issue/PR templates, and community health files |
| [`gardusi-gustavo`](https://github.com/gardusi-gustavo/gardusi-gustavo) | Account landing page, architecture portfolio, and organizational overview |

### 1. Interface & Data Contracts (`contract-*`)

Pure schema registries, wire formats, REST contracts, relational contracts, and account-level structured governance data:

| Repository | Description |
| :--- | :--- |
| [`contract-graphql`](https://github.com/gardusi-gustavo/contract-graphql) | Pure GraphQL SDL schemas for query and mutation contracts |
| [`contract-json`](https://github.com/gardusi-gustavo/contract-json) | JSON Schema definitions and account-level governance manifests |
| [`contract-openapi`](https://github.com/gardusi-gustavo/contract-openapi) | OpenAPI 3.1 REST specifications for the public devops data plane |
| [`contract-proto`](https://github.com/gardusi-gustavo/contract-proto) | Pure `.proto` service definitions and wire contracts managed via Buf |
| [`contract-sql`](https://github.com/gardusi-gustavo/contract-sql) | Relational DDL schemas, migration blueprints, and query contracts |

### 2. Language, Runtime & Infra Packages (`package-*`)

Publishable, zero-framework reference libraries, infrastructure modules, database utilities, runtime definitions, and documentation templates:

| Repository | Description |
| :--- | :--- |
| [`package-cpp`](https://github.com/gardusi-gustavo/package-cpp) | C++ algorithms, low-latency utilities, and systems reference |
| [`package-cs`](https://github.com/gardusi-gustavo/package-cs) | C# reference implementation |
| [`package-docker`](https://github.com/gardusi-gustavo/package-docker) | Dockerfiles, multi-stage builder patterns, and runtime environment setups |
| [`package-elixir`](https://github.com/gardusi-gustavo/package-elixir) | Elixir / BEAM actor concurrency reference and OTP patterns |
| [`package-go`](https://github.com/gardusi-gustavo/package-go) | Go module reference and concurrent systems patterns |
| [`package-java`](https://github.com/gardusi-gustavo/package-java) | Java JVM reference library and enterprise backend patterns |
| [`package-kotlin`](https://github.com/gardusi-gustavo/package-kotlin) | Kotlin JVM/Multiplatform reference (mirroring Java architecture) |
| [`package-lua`](https://github.com/gardusi-gustavo/package-lua) | Dependency-free Lua helpers for embedded automation |
| [`package-md`](https://github.com/gardusi-gustavo/package-md) | Reusable Markdown templates, documentation standards, and Mermaid diagrams |
| [`package-php`](https://github.com/gardusi-gustavo/package-php) | PHP / Composer reference implementation |
| [`package-python`](https://github.com/gardusi-gustavo/package-python) | Python ETL pipelines and utility library |
| [`package-rb`](https://github.com/gardusi-gustavo/package-rb) | Ruby / Gem reference implementation |
| [`package-rs`](https://github.com/gardusi-gustavo/package-rs) | Rust crate reference |
| [`package-scala`](https://github.com/gardusi-gustavo/package-scala) | Scala 3.3 functional programming, immutable patterns, and JVM concurrency |
| [`package-sh`](https://github.com/gardusi-gustavo/package-sh) | Portable POSIX/Bash automation, git hooks, bundle primitives, and helper scripts |
| [`package-swift`](https://github.com/gardusi-gustavo/package-swift) | Swift package reference and Apple platform runtime patterns |
| [`package-terraform`](https://github.com/gardusi-gustavo/package-terraform) | Infrastructure as Code modules, HCL blueprints, and Kubernetes manifest examples |
| [`package-ts`](https://github.com/gardusi-gustavo/package-ts) | TypeScript / npm utilities and DOM helpers |
| [`package-ui`](https://github.com/gardusi-gustavo/package-ui) | Pure HTML/CSS design tokens and structural layout partials |
| [`package-zig`](https://github.com/gardusi-gustavo/package-zig) | Zig low-level memory control, C-interop, and cross-compilation reference |

### 3. Pure Trigger Workflows (`workflow-*`)

Automated data pipelines, background runners, and CI/CD control planes grouped strictly by trigger nature:

| Repository | Description |
| :--- | :--- |
| [`workflow-event`](https://github.com/gardusi-gustavo/workflow-event) | Reactive automation runner handling pushes, PR checks, and webhook events |
| [`workflow-manual`](https://github.com/gardusi-gustavo/workflow-manual) | Autonomous repository maintenance agent, issue runner, and interactive dispatch |
| [`workflow-scheduled`](https://github.com/gardusi-gustavo/workflow-scheduled) | Thin time-based cron runner executing isolated data ingestion and backup jobs |

### 4. Operational Data State (`database-*`)

Public raw data lakes, daily datasets, validation schemas, and seeds partitioned by domain:

| Repository | Description |
| :--- | :--- |
| [`database-devops`](https://github.com/gardusi-gustavo/database-devops) | Sanitized repository health data, workflow metrics, and backup verification summaries |
| [`database-lottery`](https://github.com/gardusi-gustavo/database-lottery) | Historical lottery draws, statistical result datasets, and validation seeds |
| [`database-news`](https://github.com/gardusi-gustavo/database-news) | Aggregated news feed indices, daily article metadata, and text datasets |
| [`database-stocks`](https://github.com/gardusi-gustavo/database-stocks) | Historical ticker data, daily market metrics, and quantitative datasets |
| [`database-wiki`](https://github.com/gardusi-gustavo/database-wiki) | Structured knowledge-base pages and wiki indices consumed by dashboard-wiki |

### 5. Interactive Games (`game-*`)

Algorithmic puzzle platforms and interactive applications:

| Repository | Description |
| :--- | :--- |
| [`game-crosswords`](https://github.com/gardusi-gustavo/game-crosswords) | Algorithmic crossword puzzle application |
| [`game-logic-grid`](https://github.com/gardusi-gustavo/game-logic-grid) | Deductive logic-grid puzzle application |
| [`game-sudoku`](https://github.com/gardusi-gustavo/game-sudoku) | High-performance Sudoku generator and solver |

### 6. Consumer Dashboards (`dashboard-*`)

Static client-side UI interfaces and internal operations consoles consuming `database-*` and `package-ui`:

| Repository | Description |
| :--- | :--- |
| [`dashboard-devops`](https://github.com/gardusi-gustavo/dashboard-devops) | Internal operational dashboard monitoring ecosystem health, backups, and PR quotas |
| [`dashboard-lottery`](https://github.com/gardusi-gustavo/dashboard-lottery) | Web interface for statistical lottery data visualization |
| [`dashboard-news`](https://github.com/gardusi-gustavo/dashboard-news) | Web interface for aggregated news feeds |
| [`dashboard-stocks`](https://github.com/gardusi-gustavo/dashboard-stocks) | Web interface for market analytics and stock metrics |
| [`dashboard-wiki`](https://github.com/gardusi-gustavo/dashboard-wiki) | Personal knowledge base and system architecture specs |

---

## GitHub metadata

The repositories above are mirrored locally as `github/<prefix>/<repo>` — one directory per repository domain, and one fine-grained personal access token per domain.

| Domain | Local prefix | Repositories |
| :--- | :--- | :--- |
| Contracts | `contract/` | 5 |
| Packages | `package/` | 20 |
| Workflows | `workflow/` | 3 |
| Databases | `database/` | 5 |
| Games | `game/` | 3 |
| Dashboards | `dashboard/` | 5 |
| Meta | `meta/` | 2 |

Tokens are scoped to a single domain and limited to contents, pull-request, issue, and workflow writes. Administration is never granted, so no token can delete a repository. The private repository is excluded from the local workspace: it has no token and is updated manually in GitHub Codespaces.

- [Workspace manifest](https://github.com/gardusi-gustavo/contract-json/blob/main/governance/workspace.json)
- [Local workspace runbook](https://github.com/gardusi-gustavo/contract-json/blob/main/docs/runbooks/local-workspace.md)

## Setup

Local workspace: `github/<prefix>/<repo>`, one fine-grained token per domain, and no local copy of `private`.

Prerequisites: git, gh, python3, opencode.

1. `mkdir -p ~/github/{contract,dashboard,database,game,package,workflow,meta}`
2. `python3 scripts/workspace.py init --root ~/github`
3. `python3 scripts/workspace.py add <domain> --token-file <path>`
4. `python3 scripts/workspace.py clone`
5. `opencode` — run the chat-to-issue prompt for ongoing work

Tokens use contents, pull-request, issue, and workflow write; administration is never granted.

- [Workspace manifest](https://github.com/gardusi-gustavo/contract-json/blob/main/governance/workspace.json)
- [Local workspace runbook](https://github.com/gardusi-gustavo/contract-json/blob/main/docs/runbooks/local-workspace.md)

## Portable setup

Runs on any arm64 Android 12+ device: Termux, an Alpine container, and opencode. No root, no GPU, about 30 minutes.

Minimum: 8 GB RAM and 128 GB storage. Day to day the device is only a terminal and a review screen; CI and the agents run in GitHub Actions.

- [Portable setup runbook](https://github.com/gardusi-gustavo/contract-json/blob/main/docs/runbooks/portable-setup.md)

## Operating model

Think in chat; one conversation is one idea. Convert it to an issue or a comment, then delete the chat. Every issue becomes a short readable spec before an agent drafts a small PR. Humans review slowly and merge.

Budgets are bands, not targets:

| Resource per day | Floor | Roof | Target |
| :--- | ---: | ---: | ---: |
| AI spend | $0.50 | $1.50 | $1.00 |
| Review | 60 min | 180 min | 120 min |
| Chat and thinking | 30 min | 90 min | 60 min |
| Merged PRs | 5 | 15 | 10 |
| New issues | 5 | 15 | 10 |

A PR should take about 12 minutes to review: 4 files, 250 lines, 5 commits. Open issues resume at 30 and pause at 40; the queue is allowed to be full.

Empty is not the goal; flow is. Daily review, weekly triage, monthly restore drill.

- [Operating model](https://github.com/gardusi-gustavo/contract-json/blob/main/docs/runbooks/operating-model.md)
- [Operating budgets](https://github.com/gardusi-gustavo/contract-json/blob/main/governance/operating.json)

## Roadmap

| Phase | Focus | Exit criteria |
| :--- | :--- | :--- |
| Now | Manual loop: write issues, generate with opencode, review and merge. Local workspace with one token per domain. | Zero live Gitea references; one ready PR per repo |
| Next | Full automation: orchestrator picks issues, generator opens drafts, advisory AI review, daily budget ledger and state backups. | No repo selection or dispatch by hand |
| Later | Cloud runtime only where state is unavoidable: game progress API, datasets on object storage, Pages stays the UI. | One game keeps progress across devices |
