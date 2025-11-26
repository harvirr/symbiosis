# Symbiosis Framework v1.0 — 20 November 2025

**An Engineering Standard for Safe, Economic, and Governable Hybrid Intelligence**

Deterministic Proto-Standard · Normative Draft · Apache 2.0  
Canonical repository of the Symbiosis standard.

**Download the full specification** → [symbiosis-framework-v1.0-2025-11-20.pdf](https://github.com/user-attachments/files/23664424/symbiosis-framework-v1.0-2025-11-20.pdf)

**Key Artifacts**
- Canonical Ontology → [diagrams/canonical-ontology.mmd](diagrams/canonical-ontology.mmd) ([SVG](https://mermaid.ink/svg/...))  
- Operational Trace → [diagrams/operational-trace.mmd](diagrams/operational-trace.mmd)  
- Reference Implementation → [symbiosis_core/engine.py](symbiosis_core/engine.py) (fully runnable, real LLM calls, cost tracking, MCP contracts)

This is the Kubernetes of human–AI coordination.

v1.0 replaces v0.9 entirely. All future development is v1.x.
📜 Symbiosis Framework v1.0a: The Sovereign Manifesto

This document serves as the public declaration of the Symbiosis Framework, a deterministic engineering standard for creating auditable, safe, and governable hybrid human–AI systems.

I. The Core Problem: Shadow AI and Unauditable Autonomy

Current ad-hoc AI deployment (Shadow AI) produces systems with unbounded autonomy and unreconstructable lineage. This obscures human accountability and violates core safety principles.

The Framework replaces the "Human-in-the-Loop" (HITL) fallacy with System-in-the-Loop architecture, making safety and economics mandatory runtime controls.

II. The Four Irreducible Axioms (The Invariants)

Symbiosis is founded on four non-negotiable invariants that must be upheld by architecture, code, and governance:

    Human Primacy: The human operator is the sole origin of sovereign intent and final bearer of regret and accountability.

Constraint Supremacy: Hard constraints (C) —legal, safety, economic—SHALL override all optimization goals or agent proposals.

Layer Integrity: The Four-Layer Architecture (Human, Engine, Agentic, Governance) must partition responsibilities. No layer may bypass an adjacent layer.

Lineage Recoverability: Every system action MUST be reconstructable to the Intent (I), Constraints (C), Task Graph (TG), and Economic Pass decision.

III. The Control Plane (Governance & Metrics)

The system enforces governance through executable code and canonical metrics:

    The Governance Kernel (GK): The isolated logic that compiles policy into machine-enforceable rules and pins policy versions (Pᵥ) to every episode.

Regret Boundary (RB) & Autonomy Bands (AB): Autonomy is graded by irreversibility (RB). The system grants AB rights (AB0–AB3) only when the operator is certified and the task is reversible (or auditable).

The Economic Circuit (EC): Enforces Economic Viability by checking cost, Compute Saturation (CS), and Queue Latency (QL) before executing any task.

IV. The Human & Ethical Covenant

The system operates under the Non-Punitive Covenant:

    Safety Telemetry Only: Human-side metrics (HSS and SCP) are classified exclusively as safety telemetry. They SHALL NOT be used for HR, ranking, or disciplinary purposes.

    Skill is Earned: The SETC Certification (Operator, Practitioner, Auditor) is the required licensing proof. Rights are earned through stability, not enthusiasm.

Getting Started (The First Steps)

    Read the Canon: Begin with the full Framework text (/docs/framework.md) to internalize the axioms and the Four-Layer Architecture.

    Get Certified: Proceed to the SETC Repository (/harvirr/setc) to start the Operator curriculum and run your first Symulator scenario.

    Contribute: The core model is Open Core. Join the community to harden the next version of the standard.
