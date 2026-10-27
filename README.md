# Hey, I'm Brad

Kubernetes platform lead in Nova Scotia. I got here the way most of us do — because production was on fire, not because someone wrote a curriculum. I build things, run my own platform, and write for engineers who need something working, not just studied.

---

## Invariant Platform

**[invariant-platform.io](https://invariant-platform.io)** — a small, security-first Kubernetes platform that re-asserts its own posture every night, from outside itself, and whose only repair is a rebuild from a declaration. Every property it claims is one it checks; the nightly check is published on the site, findings included.

- **210 numbered decisions** in a register — nothing deleted, wrong ones superseded by a later number that says why.
- **18 invariants** re-asserted every morning by a read-only identity on the hosts beneath the cluster, and paged when one stops holding.
- **Rebuilt, never repaired.** A node that is wrong is destroyed and built again from the declaration; the tool that does that on a Tuesday is the one that would rebuild the estate after a fire.
- **Nothing reaches it unsigned.** The cluster pulls a signed artifact from one named workflow; the provisioner itself is a signed release, installed by version, that refuses to change the fleet unless it is one.

**[github.com/bradpenney/substrate](https://github.com/bradpenney/substrate)** — the provisioner: one static Rust binary that provisions, verifies and rolls the cluster from a declaration. Public, with signed releases.

Everything on bradpenney.io that says "in production" was tried here first.

---

## The Writing

**[bradpenney.io](https://bradpenney.io)** is a connected set of learning sites for platform engineers and developers, arranged three ways:

- **[Pathways](https://www.bradpenney.io/pathways)** — one goal, several sites, in the order you need them.
- **[Deep Dives](https://www.bradpenney.io/deep-dives)** — one topic, start to finish, inside a site you already know.
- **[Day One](https://www.bradpenney.io/day-one)** — the first things you need on the first day.

| Site | Topic |
|------|-------|
| [linux.bradpenney.io](https://linux.bradpenney.io) | Enterprise Linux |
| [containers.bradpenney.io](https://containers.bradpenney.io) | Containers — Podman and Docker |
| [k8s.bradpenney.io](https://k8s.bradpenney.io) | Kubernetes |
| [gitops.bradpenney.io](https://gitops.bradpenney.io) | GitOps / Flux |
| [networking.bradpenney.io](https://networking.bradpenney.io) | Networking |
| [cs.bradpenney.io](https://cs.bradpenney.io) | Computer Science |
| [python.bradpenney.io](https://python.bradpenney.io) | Python |
| [tools.bradpenney.io](https://tools.bradpenney.io) | Developer Tools |

Linux + Containers + Kubernetes is the deploy stack. Networking + Kubernetes + GitOps is platform engineering. Python ties it together.

---

## Homelab

**[github.com/bradpenney/homelab](https://github.com/bradpenney/homelab)** — the self-hosted stack that came before the platform: Nextcloud in place of Google Drive and iCloud, Home Assistant, Traefik, and [Wanderer](https://wanderer.to/) for trail tracking. Public, with a real disaster-recovery runbook. It is being migrated onto Invariant Platform app by app; what has moved runs behind the same boundaries as everything else there.

---

## Projects and Open Source

| Project | Role |
|---------|------|
| [Docket](https://github.com/bradpenney/docket) | Author — a project-based task manager with a TUI, a web interface and a REST API, in Rust. |
| [firestoned](https://github.com/firestoned) | Admin / maintainer — OpenAPI and AsyncAPI specs from one JSON Schema; Kubernetes-native BIND9 DNS tooling (Python + Rust). |
| [finos/5-spot](https://github.com/finos/5-spot) | Contributor — a Rust controller that schedules physical machines on and off by time window. Not a maintainer. |
| [flux9s](https://github.com/dgunzy/flux9s) | Reviewer — a k9s-style terminal UI for Flux resources. |

---

## Off the Keyboard

Trails in Nova Scotia in a side-by-side UTV, logged at **[trails.bradpenney.io](https://trails.bradpenney.io)** — self-hosted Wanderer, now running on Invariant Platform. Same principles, different workload.

Two hobby sites, separate from the professional ecosystem but built to the same standard: **[electronics.bradpenney.io](https://electronics.bradpenney.io)** (microcontrollers, circuits, breadboards) and **[cnc.bradpenney.io](https://cnc.bradpenney.io)** (G-code, CAD/CAM and machine control on my own X-Carve).

---

## Tech

![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Flux](https://img.shields.io/badge/-Flux-5468FF?style=flat&logo=flux&logoColor=white)
![Podman](https://img.shields.io/badge/-Podman-892CA0?style=flat&logo=podman&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![MkDocs](https://img.shields.io/badge/-MkDocs-526CFE?style=flat&logo=materialformkdocs&logoColor=white)

---

## Find Me

- [bradpenney.io](https://bradpenney.io)
- [invariant-platform.io](https://invariant-platform.io)
- [LinkedIn](https://linkedin.com/in/bradpenney)
