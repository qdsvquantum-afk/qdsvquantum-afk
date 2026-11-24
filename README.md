# QDSV - Quantum Declarative Semantic Value

QDSV is a semantic model for quantum-oriented computation. It helps teams express problems from intent, state spaces, predicates, relations, rankings, distributions and evidence before deciding how execution should be represented.

```text
problem intent
-> semantic representation
-> typed operation graph
-> QDSV Operation Compiler v2
-> reversible IR / execution plan
-> execution route
-> evidence
```

## QDSV Stack

```text
QIntent
-> canonical ProblemSpec
-> QDSV Runtime
   -> QDSV Operation Compiler v2
   -> operation program + evidence
   -> QDSV Bridge -> OpenQASM / Qiskit artifacts and tested Braket LocalSimulator conversion

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
| QDSV Runtime | Public execution shell whose canonical engine is QDSV Operation Compiler v2. | https://github.com/qdsvquantum-afk/qdsv-runtime |
| QDSV Bridge | Capability-driven exporter from canonical operation programs to circuit artifacts or expert construction inputs. | https://qdsvquantum-afk.github.io/qdsv-bridge/ |
| Qruba | Visual platform for building auditable QDSV workflows. | https://qdsvquantum-afk.github.io/qruba/ |

## Product Capabilities

- Start from the problem instead of manually written circuits.
- Preserve semantic structure before backend-specific execution.
- Make semantic decisions, backend evidence and reliability visible.
- Provide SDKs, examples and public workflows for technical and commercial adoption.

## Developer Entry Points

```bash
pip install qdsv-qintent
pip install qdsv-bridge
pip install --pre qdsv-runtime
```

- QIntent PyPI: https://pypi.org/project/qdsv-qintent/
- Bridge PyPI: https://pypi.org/project/qdsv-bridge/
- Runtime GitHub: https://github.com/qdsvquantum-afk/qdsv-runtime
- Runtime PyPI: https://pypi.org/project/qdsv-runtime/
- Qruba Cloud: https://cloud.qruba.site/
- Public API: https://api.qdsv.cloud/api/qintent/spec

## Public Product Posture

QDSV Bridge is a built and technically tested public product with a versioned
contract, bounded capabilities, artifact digests and documented Qiskit
interoperability. It is available for technical adoption and commercial use
within the published capabilities and resource limits.

The public SDKs and services do not include CAP internals, concrete lowering
operands, backend selectors, QuEST/Aer/IBM adapters, private scoring formulas,
infrastructure secrets or production deployment configuration. Bridge delivers
portable artifacts; simulator, transpilation and QPU execution belong to the
consumer or to an authorized Qruba/QDSV workflow.

The public posture does not claim unlimited capacity, quantum advantage or a
provider-level SLA. Current capabilities, limits and execution boundaries are
discoverable through the running service's public capability endpoints.

## Contact

For product information, subscriptions, enterprise adoption, technical support and strategic partnerships:

https://qdsv.cloud/
