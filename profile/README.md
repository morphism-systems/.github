# Morphism Systems

Categorical governance for AI agent fleets.

Morphism is a mathematical governance framework that uses category theory — Cech cohomology for drift detection, Banach fixed-point contraction for self-healing, and information-theoretic entropy for compliance measurement — to provide formally guaranteed convergence to compliance for software and AI agent systems.

## What we build

- **Governance engine** (Python) — category theory core with sheaf-theoretic drift detection, contraction-based healing, and machine-checkable proof witnesses
- **Web dashboard** (Next.js) — real-time kappa, entropy trends, drift status, and audit trail
- **CLI** — `morphism init`, `morphism audit`, `morphism heal` for developer workflows
- **MCP server** — expose governance tools to AI agent fleets via Model Context Protocol
- **SDK** — embeddable client for third-party platform integration

## Key properties

| Property | Guarantee |
|----------|----------|
| Drift detection | First cohomology H1(F) detects global inconsistency across governance domains |
| Self-healing | Contraction mapping with kappa < 1 converges to unique compliant fixed point (Banach) |
| Entropy monotonicity | Every admissible transition satisfies E(s') <= E(s) + epsilon |
| Proof witnesses | Each governance check produces a machine-checkable verification record |

## Links

- [morphism.systems](https://morphism.systems)
- [Documentation](https://github.com/morphism-systems/morphism/tree/main/docs)
- [Discussions](https://github.com/morphism-systems/morphism/discussions)
