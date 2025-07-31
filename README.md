## Individual projects

- `ordserv`
  - Rust
  - Written late 2023
  - Highlights:
    - a technique for testing a distributed system
    - working closely with Linux for reliability/performance
    - basic algorithms
  - [Write-up](https://github.com/petervdonovan/ordserv/blob/main/explain/report.pdf)
  - [Specifications validated using the tool](https://github.com/petervdonovan/ordserv/blob/main/explain/explanations.md)
  - [Monorepo](https://github.com/petervdonovan/ordserv)
  - [Related paper describing the system under test](https://arxiv.org/pdf/2405.12117)
- `rvg`
  - OCaml
  - Written early 2023
  - Highlights:
    - starting a hardware-specific software stack from square one
    - RISC-V programming
    - interpreter for a templating DSL for RISC-V assembly
  - [Write-up](https://github.com/petervdonovan/rvg/blob/main/report.pdf)
  - Repositories: [interpreter](https://github.com/petervdonovan/rvg), [code examples](https://github.com/petervdonovan/rvg-flexpret-code-examples), [stdlib](https://github.com/petervdonovan/rvg-stdlib), [build tool](https://github.com/petervdonovan/rvgbuild), [editor support](https://github.com/petervdonovan/rvg-vsc), [NoC](https://github.com/t-crest/soc-comm/pull/3/files), [RISC-V core](https://github.com/lf-lang/interpret/pull/9/files#diff-5d4cb2e1b2d21261e925d0281d2d80d79f7acf58e9e77cd3386d772d97c7feb5)
  - [Related paper describing the hardware platform](https://dl.acm.org/doi/pdf/10.1145/3576914.3587497)
- `specialtree`
  - Rust
  - In progress as of 2025
  - Highlights:
    - advanced use of Rust generics and traits
    - Rust code generation
    - flexible software design patterns, unusual coding style
  - No write-up available yet
  - [Monorepo](https://github.com/petervdonovan/specialtree)

## Collaborative open-source work

- Lingua Franca coordination language, developed at iCyPhy at UC Berkeley
  - Contributions to the templating engine (Java):
    - [authored 116 merged PRs](https://github.com/lf-lang/lingua-franca/pulls?q=is%3Apr+is%3Amerged+author%3Apetervdonovan+)
    - [reviewed 122 merged PRs](https://github.com/lf-lang/lingua-franca/pulls?q=is%3Apr+is%3Amerged+reviewed-by%3Apetervdonovan+)
  - Contributions to the task execution framework (C, Pthreads):
    - [authored 31 merged PRs](https://github.com/lf-lang/reactor-c/pulls?q=is%3Apr+is%3Amerged+author%3Apetervdonovan+)
    - [reviewed 53 merged PRs](https://github.com/lf-lang/reactor-c/pulls?page=1&q=is%3Apr+is%3Amerged+reviewed-by%3Apetervdonovan)
  - Example code contribution: [task executor PR](https://github.com/lf-lang/reactor-c/pull/85), [PR showing speedup achieved by "C heuristic"/adaptive task scheduler](https://github.com/lf-lang/lingua-franca/pull/1207)
- Example of a recent Rust-related code contribution: [issue](https://github.com/cognitive-engineering-lab/argus/issues/62), [PR](https://github.com/cognitive-engineering-lab/argus/pull/65)

## Other

- Worked at Xronos Inc. from January 2024 to July 2025
  - Built a cloud service for observability in robotics applications, including front-end and backend development
  - Built interactive viewer for software architecture diagrams (images/docs available [here](https://docs.xronos.com/diagrams.html))
  - Helped to maintain Xronos's C++-based task scheduling framework and SDKs (OSS offering available [here](https://github.com/xronos-inc/xronos))
- [Publication list available at Google scholar](https://scholar.google.com/citations?user=46vBKvAAAAAJ&hl=en), including work done at UC Berkeley's cyber-physical systems lab
