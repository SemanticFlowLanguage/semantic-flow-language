# Semantic Flow Language (SFL)

> A semantic execution model aligning human intent, AI reasoning, and runnable logic.

## Canonical Definition
**Semantic Flow Language (SFL)** is a **Semantic Execution Model** that represents logic as a **bidirectionally synchronized meaning graph**, ensuring that human intent, AI generation, and executable code remain aligned.

### Problem with Generative AI

Generative AI can produce plausible code, but it operates probabilistically, not logically. This means that AI outputs are based on patterns rather than reason, leading to potential inaccuracies in production systems. Without structure and verification, AI-generated code can drift away from human intent and fail in novel scenarios.

### SFL Solution

SFL provides a **semantic synchronization** mechanism that keeps **meaning** and **logic** aligned, preventing the drift that typically occurs in AI-driven development. It introduces a **bidirectional meaning graph** that ensures:
- **Intent** is clearly defined and human-readable.
- **Logic** is generated or verified to match the intent.
- **Invariants** ensure that the generated code adheres to predefined rules and constraints.
- **Verification** ensures that intent and logic are always synchronized.

SFL is designed to work across **visual programming environments** (like Node-RED) and **text-based systems**, making it a flexible foundation for building trustworthy AI-powered tools.

### Core Principles
- **Human-Defined Intent:** Every action in the system has a clear, human-readable purpose.
- **Semantic Integrity:** The intent and logic are bidirectionally synchronized and verifiable.
- **Verification:** Each step in the process is validated to ensure it aligns with the original intent and rules.

### Core Documents

The Semantic Flow Language (SFL) is defined across three foundational documents:

- [**Concept**](./docs/concept.md) — Defines the core structure, goals, and dual-layer approach of SFL.  
- [**Philosophy**](./docs/philosophy.md) — Explains the reasoning behind SFL: the problem with probabilistic AI and the need for human-centered semantic control.  
- [**Specification**](./docs/specification.md) — Details the formal semantics, syntax, and verification model for SFL implementations.

Together, these documents describe how SFL maintains semantic alignment between **human intent**, **AI generation**, and **runnable logic** — creating a new paradigm for AI-assisted software design.

### Current Implementation: Node-RED

The first implementation of SFL is available as a **Node-RED** extension:  
**[Node-RED – Semantic Flow Language (node-red-semantic-flow-language)](https://github.com/SemanticFlowLanguage/node-red-semantic-flow-language)**

![SFL Node-RED Demo](./assets/sfl-demo.gif)

This project demonstrates the core idea of intent ↔ logic synchronization, with a visual interface that lets developers track changes and ensure alignment between code and meaning. It serves as the first real-world example of how SFL works in practice.

### Future Vision

SFL is designed to be platform-agnostic, and future versions will extend to other environments, such as:
- **Graph-based editors** (e.g., GrapesJS)
- **IDE plugins**
- **Command-line tools** for semantic linting and verification

## Related Projects

- **System Topology Manifest (STM)**  
  Declarative inventory of systems, applications, and signals.  
  https://github.com/SystemTopologyManifest/system-topology-manifest

- **System Architecture Manifest (SAM)**  
  Derived architecture constraints and guardrails composed from STM output.  
  https://github.com/SystemArchitectureManifest/system-architecture-manifest

## Runtime Layer

This system uses **MOCA (Memory-Oriented Cognitive Architecture)** as a runtime and integration layer.

MOCA is independently usable and is not specific to this project.

https://github.com/MemoryOrientedCognitiveArchitecture/memory-oriented-cognitive-architecture

### Contributing

We welcome contributions to expand and improve the Semantic Flow Language project. If you’re interested, please check out the **[contributing guidelines](./CONTRIBUTING.md)** for more information.

### Contact

- **Author:** William Shostak (https://github.com/wshostak)

### License

This project is licensed under the **ISC License** — see the **[LICENSE](./LICENSE.txt)** file for more details.

Copyright (c) 2025 William Shostak
