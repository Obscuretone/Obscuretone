# Evan d'Entremont

Montreal-based software developer focused on systems, backend architecture,
and developer tooling. I am interested in **senior, lead, and staff engineering**
roles, as well as **software development management**.

My background spans backend, full-stack, and embedded work, including core
services, compliance tooling, incident management, QA process design, database
performance, and industrial/IoT interfaces. My public projects make the design
choices, constraints, and verification work available for review.

[Engineering notes](https://obscuretone.com) · [Email](mailto:marc@obscuretone.com)

## Selected projects

| Project | Engineering focus | Start here |
| --- | --- | --- |
| [PyGameBoy](https://github.com/Obscuretone/pygameboy) | Python Game Boy emulator: CPU dispatch, NumPy rendering, audio pacing, and cartridge banking | [Architecture](https://github.com/Obscuretone/pygameboy/blob/main/ARCHITECTURE.md) · [Benchmarks](https://github.com/Obscuretone/pygameboy/blob/main/BENCHMARKS.md) |
| [GBPython](https://github.com/Obscuretone/GBPython) | Python interpreter on a Game Boy, with banked SRAM, software floats, and an interactive REPL | [Architecture](https://github.com/Obscuretone/GBPython/blob/main/docs/ARCHITECTURE.md) · [Emulator tests](https://github.com/Obscuretone/GBPython/blob/main/tests/run_tests.py) |
| [Nira](https://github.com/Obscuretone/nira) | Local issue tracker with a Python CLI, web UI, SQLite storage, and workflows for people and agents | [Quick start](https://github.com/Obscuretone/nira#quick-start) · [Tests](https://github.com/Obscuretone/nira/tree/main/tests) |
| [factorer](https://github.com/Obscuretone/factorer) | Parallel Fermat factorization in Go, with bounded searches and worker scaling benchmarks | [Build and benchmarks](https://github.com/Obscuretone/factorer#build) |
| [Dive](https://github.com/Obscuretone/dive) | Laravel/React task planner with AI subtask generation and shared rate-limit handling | [Setup and API](https://github.com/Obscuretone/dive#backend-setup) |

[Obscuretone Test ROM](https://github.com/Obscuretone/obscuretone-test-rom)
complements the Game Boy projects with self-checking opcode and subsystem probes,
a reproducible Python generator, and a structured serial reporting protocol.

## Recent developer tooling

[Repository Policy Evidence](https://github.com/Obscuretone/repo-policy-evidence)
is a bounded, AI-assisted prototype for read-only GitHub audits. It ties three explicit
controls to a captured commit, preserves unknown results when evidence is missing, and
supports deterministic offline replay. Start with the fictional HTML demo, evidence
contract, and tests; it is not a production compliance service.

## Engineering approach

- **Architecture grounded in constraints:** explain boundaries, failure modes,
  and performance costs before adding complexity. PyGameBoy and GBPython make
  those tradeoffs concrete at the CPU, memory, and runtime level.
- **Quality as a delivery practice:** use reproducible builds, automated checks,
  conformance tests, and focused commits so changes can be reviewed and maintained.
- **Tools that support a team:** Nira explores a shared workflow for people and
  agents, with a CLI for automation and a web UI for review.
- **Operational judgment:** my writing on
  [production incidents](https://obscuretone.com/posts/en/trial_by_fire) and
  [engineering metrics](https://obscuretone.com/posts/en/pieces_of_flair)
  covers reliability, feedback loops, and the incentives around software delivery.

## Experiments

[BlockchainCoin](https://github.com/Obscuretone/BlockchainCoin) is a vibe-coded
experiment with Codex to explore blockchain mechanics. It is a learning exercise,
not a flagship project or evidence of production blockchain experience.

[RustPHP](https://github.com/Obscuretone/RustPHP) is an automation-driven,
AI-assisted runtime/compiler prototype. Development is paused; it is incomplete
and is not production software or a supported PHP replacement.

## Backend experiments

I have also explored task APIs across
[Spring Boot / Oracle](https://github.com/Obscuretone/todo-enterprise),
[Go / Neo4j](https://github.com/Obscuretone/todo-go-neo4j),
[PHP / RoadRunner](https://github.com/Obscuretone/todo-roadrunner), and
[TypeScript / MongoDB](https://github.com/Obscuretone/todo-mets).
These are ecosystem experiments; each repository documents its own scope.

Smaller research prototypes, archived work, and satire remain in the repository
list. The projects above are the best starting point for a technical review.
