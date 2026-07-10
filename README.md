# QDSV - Quantum Declarative Semantic Value

QDSV is a semantic model for quantum-oriented computation. It helps teams express problems from intent, state spaces, predicates, relations, rankings, distributions and evidence before deciding how execution should be represented.

```text
problem intent
-> semantic representation
-> runtime execution layer
-> execution route
-> evidence
```

## QDSV Stack

```text
QIntent
-> QDSV Runtime Alpha
-> QDSV Bridge
-> OpenQASM / Qiskit / Braket artifacts

Qruba
-> visual human interaction layer

QDSV
-> semantic model and private engine
```

## Public Ecosystem

| Project | Role | Link |
|---|---|---|
| QDSV | Foundational model and semantic layer. | https://qdsv.cloud |
| QIntent | Intent-first language and Python SDK. | https://qdsvquantum-afk.github.io/qintent/ |
| QDSV Runtime Alpha | Lightweight execution layer that ties QIntent and Bridge into reproducible workflows. | Developer preview package in preparation |
| QDSV Bridge | Semantic-to-circuit bridge for controlled problem families. | https://qdsvquantum-afk.github.io/qdsv-bridge/ |
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
# coming next
pip install qdsv-runtime
```

- QIntent PyPI: https://pypi.org/project/qdsv-qintent/
- Bridge PyPI: https://pypi.org/project/qdsv-bridge/
- Runtime Alpha: early developer preview, local package validated; public repository/package in preparation.
- Qruba Cloud: https://cloud.qruba.site/
- Public API: https://api.qdsv.cloud/api/qintent/spec

## Public Preview Notice

The public SDKs are Developer Preview clients. Runtime Alpha is a public execution shell, not the private QDSV semantic engine. The public packages do not include CAP internals, backend selectors, private lowering, QuEST/Aer/IBM adapters, private scoring formulas, infrastructure secrets or production deployment configuration.

## Contact

For pilots, technical review, research collaboration or investment conversations:

https://qdsv.cloud/
