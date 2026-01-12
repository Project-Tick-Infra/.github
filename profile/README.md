# Project Tick

**Disciplined open-source software focused on long-term maintainability, reproducible builds, and infrastructure that does not rot over time.**

Project Tick is not a collection of random repositories.
It is an opinionated effort to build and maintain software the way open-source projects *should* be maintained, even years later.

---

## Why Project Tick Exists

Many open-source projects fail for the same reasons:

* unclear technical direction
* rushed architectural decisions
* neglected CI, packaging, and release infrastructure
* undocumented changes and silent breakage

Project Tick exists to counter those failure modes.

We make decisions explicit, document them, automate everything that can be automated, and deliberately favor long-term correctness over short-term convenience.

---

## What We Build

**ProjT Launcher** is the flagship project.

It is a cross-platform launcher designed around strict architectural boundaries, reproducible builds, and maintainable workflows rather than feature churn.

In addition, Project Tick hosts:

* infrastructure and tooling repositories
* packaging and distribution tooling
* policy and documentation projects (handbooks, guidelines)
* supporting libraries maintained as controlled forks when necessary

Every repository exists for a clear reason and follows the same standards.

---

## Core Principles

* Long-term maintenance is more important than short-term velocity
* Architecture and boundaries are enforced, not implied
* Automation and CI/CD are first-class requirements
* Reproducible builds are non-negotiable
* Upstream projects, licenses, and contributor intent are respected
* Decisions are documented and traceable

If a change cannot be justified long-term, it does not land.

---

## Contributions

Project Tick is open to contributions, but not permissive by default.

* Pull requests are required
* DCO / Signed-off-by is mandatory
* Reviews focus on correctness, maintainability, and architectural impact
* Not every contribution will be accepted

Feedback is technical, direct, and professional.
We value sustainable codebases over fast merges.

---

## Infrastructure & Packaging

Infrastructure is treated as part of the product.

* CI/CD is required, not optional
* Linux, Windows, and macOS are supported deliberately
* Packaging considerations start early, not after the fact
* Reproducibility and determinism are core goals

Nix and Flatpak are common reference ecosystems, not afterthoughts.

---

## Licensing

Each repository is licensed individually.

We favor GPL-compatible open-source licenses and expect contributors to respect both the letter and the intent of those licenses.

---

## Scope and Expectations

Project Tick is **not** a general-purpose platform and does not aim to move fast at the cost of stability.

We build fewer things, but we maintain them properly.

---

## Contact

Technical discussion happens through issues and pull requests.
Decisions, changes, and rationale are expected to be public and reviewable.
