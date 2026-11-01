# Data Structures and Algorithms

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/vitorparras/Data-Structures-and-Algorithms/badge)](https://scorecard.dev/viewer/?uri=github.com/vitorparras/Data-Structures-and-Algorithms)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Implementations and explanations of classic data structures and algorithms,
organized by topic, for study and quick reference.

> **Status:** starting. The repository structure and conventions are defined
> below; implementations are added over time. Contributions are welcome from
> day one.

## Table of contents

- [Goal](#goal)
- [Planned structure](#planned-structure)
- [Conventions](#conventions)
- [How to use it](#how-to-use-it)
- [Contributing](#contributing)
- [Security](#security)
- [Code of conduct](#code-of-conduct)
- [License](#license)

## Goal

To be a place where each fundamental data structure and algorithm has:

- a short explanation of the idea and when to use it;
- a clean, commented implementation;
- its time and space complexity;
- small tests or examples that show it working.

Python is the first language; other languages are welcome side by side, in the
same folder, as long as they follow the conventions below.

## Planned structure

```text
Data-Structures-and-Algorithms/
├── data-structures/
│   ├── arrays/
│   ├── linked-lists/          # singly, doubly, circular
│   ├── stacks-and-queues/
│   ├── hash-tables/
│   ├── trees/                 # binary, BST, AVL, heaps, tries
│   └── graphs/                # representations, BFS, DFS
├── algorithms/
│   ├── sorting/               # bubble, insertion, merge, quick, heap, counting
│   ├── searching/             # linear, binary, interpolation
│   ├── recursion-and-backtracking/
│   ├── dynamic-programming/
│   ├── greedy/
│   └── graph-algorithms/      # Dijkstra, Bellman-Ford, Kruskal, Prim, topological sort
└── README.md
```

Each leaf folder contains a `README.md` with the explanation and complexity
table, one implementation file per language (for example `linked_list.py`), and
a test file (for example `test_linked_list.py`).

## Conventions

- **Folder names** in lowercase with hyphens; **file names** follow the
  language convention (snake_case for Python, PascalCase for C#).
- **Every README** has: problem, idea, step-by-step example, complexity
  (best, average, worst) and references.
- **Code is readable before it is clever.** Comments explain decisions, not
  syntax.
- **Tests run with the standard toolchain** of the language (for Python,
  `python -m pytest` or `python -m unittest`). State the version used.
- **No external dependencies** unless the topic requires them.

## How to use it

1. Browse to the topic you want.
2. Read the `README.md` for the concept and its complexity.
3. Open the implementation and the tests, and run them:

   ```bash
   git clone https://github.com/vitorparras/Data-Structures-and-Algorithms.git
   cd Data-Structures-and-Algorithms
   python -m pytest   # once tests exist
   ```

## Contributing

New implementations, better explanations and corrections are welcome. Please
read [CONTRIBUTING.md](CONTRIBUTING.md) first. Open a
[suggestion](https://github.com/vitorparras/Data-Structures-and-Algorithms/issues/new?template=content_suggestion.yml)
before writing a large piece so we can agree on scope. The `main` branch is
protected and only receives changes through reviewed pull requests.

## Security

Found a problem in this repository's code or configuration? Follow
[SECURITY.md](SECURITY.md) and report it privately.

## Code of conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By
participating you agree to uphold it.

## License

Licensed under the [MIT License](LICENSE). Copyright © Vitor Hugo Parras.
