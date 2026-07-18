# MolCrafts

## 🌟 Vision

Molecular and materials science is full of brilliant ideas trapped between
formats, scripts, folders, notebooks, cluster jobs, datasets, and half-remembered
decisions. Discovery should compound: a structure, a run, a model, a result —
handed to the next person or agent with its scientific context still alive.

MolCrafts is building a next-generation open foundation for collaborative science.
Scientists turn ideas into runnable studies; builders turn methods into tools
others can trust, reuse, and extend; AI agents join the same shared ground —
so research stays open, FAIR, and reproducible, and the frontiers of knowledge
keep moving.

## 📜 Manifesto

> MolCrafts is an open foundation for molecular and materials science.
>
> We bring methods, data, and workflows onto common ground.
>
> We keep scientific work open, FAIR, and reproducible.
>
> We help researchers go further, with less repetition.
>
> MolCrafts exists to extend the frontiers of knowledge.

## 🧰 Ecosystem

#### 🧬 Molecular core

| Project | Role |
|---------|------|
| [molpy](https://github.com/MolCrafts/molpy) | Python toolkit for molecular workflows: parsing, building, editing, typing, analyzing, packing, and simulation I/O |
| [molrs](https://github.com/MolCrafts/molrs) | Rust core for molecular data structures, I/O, conformer generation, force fields, trajectory analysis, Python bindings, and WASM |
| [molpack](https://github.com/MolCrafts/molpack) | Packmol-grade molecular packing in Rust, with a Packmol-compatible CLI plus Rust and Python APIs |
| [molnex](https://github.com/MolCrafts/molnex) | Layered molecular ML framework for training, representations, potential composition, and reference model families |
| [molrec](https://github.com/MolCrafts/molrec) | Backend-neutral atomistic record contract for frames, trajectories, observables, status, metrics, and metadata |

#### 🧪 Workflow, execution, and data

| Project | Role |
|---------|------|
| [molexp](https://github.com/MolCrafts/molexp) | Agent-assisted experiment platform with typed workflow graphs, tracked runs, artifact lineage, FastAPI, and a React UI |
| [molq](https://github.com/MolCrafts/molq) | Unified job queue for local execution and HPC schedulers including SLURM, PBS, and LSF |
| [molhub](https://github.com/MolCrafts/molhub) | Dataset access layer for molecular benchmarks, custom datasets, and uploads to public repositories |

#### 🖥️ Interfaces and visualization

| Project | Role |
|---------|------|
| [molvis](https://github.com/MolCrafts/molvis) | Interactive 3D inspection, editing, measurement, and trajectory playback for the web, VSCode, and Jupyter |
| [molplot](https://github.com/MolCrafts/molplot) | Unified scientific charting — one Vega-Lite spec, two renderers (web + matplotlib) |
| [molmcp](https://github.com/MolCrafts/molmcp) | MCP server and graph-based codebase discovery for exposing MolCrafts capabilities to AI agents |

#### 🧱 Shared libraries

| Project | Role |
|---------|------|
| [molcfg](https://github.com/MolCrafts/molcfg) | Layered configuration with source tracking, validation, profiles, interpolation, and thread-safe access |
| [mollog](https://github.com/MolCrafts/mollog) | Structured Python logging with stdlib-compatible APIs, JSON/Rich formatting, context propagation, and Logfire support |
| [molqrc](https://github.com/MolCrafts/molqrc) | High-quality QR code generator library in Rust |

## 🤝 Contributing

MolCrafts grows through real scientific needs. Bring a dataset that should be
easier to use, a workflow that should be easier to reproduce, a format that
should be easier to read, a benchmark that should be trusted, or a tool idea
that would save researchers from repeating the same work again.

Start from the package closest to the problem you care about. Issues, examples,
documentation, benchmarks, parser support, scheduler integrations, dataset
loaders, and visualization workflows all move the ecosystem forward.

For agent-assisted development across the stack, start with
[molcrafts-harness](https://github.com/MolCrafts/molcrafts-harness).

## 🐾 Meet Moko

Our mascot **Moko** is still here, digging through the layers of molecular and
materials science with us: records, datasets, experiments, visualizations,
agents, and every tunnel that helps a good idea reach the surface.

Website: [molcrafts.org](https://molcrafts.org)

## ❤️ Sponsor

<p align="left">
  <a href="https://claude.com/contact-sales/claude-for-oss">
    <img src="https://raw.githubusercontent.com/MolCrafts/.github/master/profile/assets/claude.svg" alt="Claude" height="40"><br>
    Claude for Open Source Project
  </a>
</p>
