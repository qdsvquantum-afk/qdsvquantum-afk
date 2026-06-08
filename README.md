# QDSV - Quantum Declarative Semantic Value

QDSV is a semantic model for quantum-oriented computation. It helps teams express problems from intent, state spaces, predicates, relations, rankings, distributions and evidence before deciding how execution should be represented.

```text
problem intent
-> semantic representation
-> execution route
-> evidence
```

## Public Ecosystem

| Project | Role | Link |
|---|---|---|
| QDSV | Foundational model and semantic layer. | https://qdsv.cloud |
| QIntent | Intent-first language and Python SDK. | https://github.com/qdsvquantum-afk/qintent |
| QDSV Bridge | Semantic-to-circuit bridge for controlled problem families. | https://github.com/qdsvquantum-afk/qdsv-bridge |
| Qruba | Visual platform for building auditable QDSV workflows. | https://github.com/qdsvquantum-afk/qruba |

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
```

- QIntent PyPI: https://pypi.org/project/qdsv-qintent/
- Bridge PyPI: https://pypi.org/project/qdsv-bridge/
- Qruba Cloud: https://cloud.qruba.site/
- Public API: https://api.qdsv.cloud/api/qintent/spec

## Public Preview Notice

The public SDKs are Developer Preview clients. They do not include the private QDSV Runtime, CAP internals, backend selectors, private lowering, QuEST/Aer/IBM adapters, infrastructure secrets or production deployment configuration.

## Contact

For pilots, technical review, research collaboration or investment conversations:

https://qdsv.cloud/
