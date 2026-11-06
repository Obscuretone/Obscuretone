# Evan d'Entremont

Software developer based in Montreal. I build emulators, language runtimes,
and backend tools, with an interest in how design decisions hold up under
hardware constraints, testing, and real workloads.

[Engineering notes](https://obscuretone.com) · [Email](mailto:marc@obscuretone.com)

## Selected projects

| Project | Engineering focus | Start here |
| --- | --- | --- |
| [PyGameBoy](https://github.com/Obscuretone/pygameboy) | Python Game Boy emulator: CPU dispatch, NumPy rendering, audio pacing, and cartridge banking | [Architecture](https://github.com/Obscuretone/pygameboy/blob/main/ARCHITECTURE.md) · [Benchmarks](https://github.com/Obscuretone/pygameboy/blob/main/BENCHMARKS.md) |
| [GBPython](https://github.com/Obscuretone/GBPython) | Python interpreter on a Game Boy, with banked SRAM, software floats, and an interactive REPL | [Architecture](https://github.com/Obscuretone/GBPython/blob/main/docs/ARCHITECTURE.md) · [Emulator tests](https://github.com/Obscuretone/GBPython/blob/main/tests/run_tests.py) |
| [Nira](https://github.com/Obscuretone/nira) | Local issue tracker with a Python CLI, web UI, SQLite storage, and workflows for people and agents | [Quick start](https://github.com/Obscuretone/nira#quick-start) · [Tests](https://github.com/Obscuretone/nira/tree/main/tests) |
| [BlockchainCoin](https://github.com/Obscuretone/BlockchainCoin) | Academic UTXO node: durable state, fork choice, peer protocol, and reproducible builds | [Architecture](https://github.com/Obscuretone/BlockchainCoin/blob/main/docs/architecture.md) |
| [factorer](https://github.com/Obscuretone/factorer) | Parallel Fermat factorization in Go, with bounded searches and worker scaling benchmarks | [Build and benchmarks](https://github.com/Obscuretone/factorer#build) |
| [Dive](https://github.com/Obscuretone/dive) | Laravel/React task planner with AI subtask generation and shared rate-limit handling | [Setup and API](https://github.com/Obscuretone/dive#backend-setup) |

[Obscuretone Test ROM](https://github.com/Obscuretone/obscuretone-test-rom)
complements the Game Boy projects with self-checking opcode and subsystem probes,
a reproducible Python generator, and a structured serial reporting protocol.

## Backend experiments

I have also explored task APIs across
[Spring Boot / Oracle](https://github.com/Obscuretone/todo-enterprise),
[Go / Neo4j](https://github.com/Obscuretone/todo-go-neo4j),
[PHP / RoadRunner](https://github.com/Obscuretone/todo-roadrunner), and
[TypeScript / MongoDB](https://github.com/Obscuretone/todo-mets).
These are ecosystem experiments; each repository documents its own scope.

Smaller research prototypes, archived work, and satire remain in the repository
list. The projects above are the best starting point for a technical review.
