# Gustavo Gardusi

Systems software engineer focused on backend architecture, distributed systems,
containerization, and repository governance.

## Architecture portfolio

### 1. Contracts

- **package-proto** — pure `.proto` service definitions and wire contracts, managed with Buf.
- **package-json** — JSON Schema definitions for API payloads, events, configuration, and repository contracts.
- **package-sql** — canonical SQL schemas, migrations, and dialect notes.
- **package-graphql** — GraphQL SDL schemas for query and mutation contracts.

### 2. Tooling and control plane

- **package-sh** — shell automation, Git hooks, and pinned helper scripts.
- **devops** — reusable CI workflows, repository policy, backups, and bootstrap tooling.

### 3. Language packages

Publishable, framework-free reference libraries:

- **package-cpp** — C++ algorithms and systems reference.
- **package-python** — Python ETL and utility library.
- **package-ts** — TypeScript/npm utilities and DOM helpers.
- **package-rs** — Rust crate reference.
- **package-go** — Go module reference.
- **package-java** — JVM library with Java and Kotlin examples.
- **package-cs** — C# reference.
- **package-php** — PHP/Composer reference.
- **package-rb** — Ruby/Gem reference.
- **package-ui** — pure HTML/CSS design tokens and structural partials.

### 4. Data

- **database** — public raw data lake, daily datasets, validation schemas, and seeds.

### 5. Workflows

- **workflow-news**, **workflow-stocks**, **workflow-lottery**, **workflow-agent** — data extraction, rolling ingestion, and event-driven runners.

### 6. Dashboards

- **dashboard-news**, **dashboard-stocks**, **dashboard-lottery**, **dashboard-wiki** — static interfaces built from `database` and `package-ui`.

### 7. Games

- **game-sudoku**, **game-logic-grid**, **game-crosswords** — algorithmic puzzle applications.

### 8. Private boundary

- **private** — private configurations, vault backups, and sensitive administrative data.
