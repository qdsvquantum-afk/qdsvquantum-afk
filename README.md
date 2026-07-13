# QDSV - Quantum Declarative Semantic Value

QDSV is a semantic model for quantum-oriented computation. It helps teams express problems from intent, state spaces, predicates, relations, rankings, distributions and evidence before deciding how execution should be represented.

```text
problem intent
-> semantic representation
-> typed operation graph
-> QDSV Operation Compiler v1
-> reversible IR / execution plan
-> execution route
-> evidence
```

## QDSV Stack

```text
QIntent
-> canonical ProblemSpec
-> QDSV Runtime Alpha
   -> QDSV Operation Compiler v1
   -> operation program + evidence
   -> QDSV Bridge -> OpenQASM / Qiskit / Braket artifacts

Qruba
-> visual orchestration over the same Runtime/Compiler path

QDSV
-> semantic model and private engine
```

## Public Ecosystem

| Project | Role | Link |
|---|---|---|
| QDSV | Foundational model and semantic layer. | https://qdsv.cloud |
| QIntent | Intent-first language and Python SDK. | https://qdsvquantum-afk.github.io/qintent/ |
| QDSV Runtime Alpha | Public execution shell whose canonical engine is QDSV Operation Compiler v1. | https://github.com/qdsvquantum-afk/qdsv-runtime |
| QDSV Bridge | Capability-driven exporter from canonical operation programs to circuit artifacts or expert construction inputs. | https://qdsvquantum-afk.github.io/qdsv-bridge/ |
| Qruba | Visual platform for building auditable QDSV workflows. | https://qdsvquantum-afk.github.io/qruba/ |

## What We Are Exploring

- Lowering the entry barrier to quantum-ready computation.
- Letting users start from the problem instead of manually written circuits.
- Preserving semantic structure before backend-specific execution.
- Making semantic decisions, backend evidence and reliability visible.
- Providing SDKs, examples and public demos that developers can test.

## Developer Entry Points

```bash
pip install qdsv-qintent
pip install qdsv-bridge
pip install --pre qdsv-runtime
```

- QIntent PyPI: https://pypi.org/project/qdsv-qintent/
- Bridge PyPI: https://pypi.org/project/qdsv-bridge/
- Runtime Alpha GitHub: https://github.com/qdsvquantum-afk/qdsv-runtime
- Runtime Alpha PyPI: https://pypi.org/project/qdsv-runtime/
- Qruba Cloud: https://cloud.qruba.site/
- Public API: https://api.qdsv.cloud/api/qintent/spec

## Public Preview Notice

The public SDKs are Developer Preview clients. Runtime Alpha exposes a safe operation-program passport, not the private QDSV compiler implementation. QIntent, Qruba and Bridge consume the same compiler authority and program digest. The public packages do not include CAP internals, concrete lowering operands, backend selectors, QuEST/Aer/IBM adapters, private scoring formulas, infrastructure secrets or production deployment configuration.

## Contact

For pilots, technical review, research collaboration or investment conversations:

https://qdsv.cloud/
