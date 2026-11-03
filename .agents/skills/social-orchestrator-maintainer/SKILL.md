---
name: social-orchestrator-maintainer
description: Maintain the standalone Falvorn Social Orchestrator repository with verified release gates and safe approval controls.
---

# Social Orchestrator Maintainer

- Treat this repository as independent of `Falvorn-AI`; do not mix branches, source directories or release tags.
- Read `AGENTS.md`, README and docs before any code change.
- Run `pytest -q` and `python -m compileall -q app`; record actual results, date and limitations in CHANGELOG.md.
- Do not claim live Instagram/LinkedIn/YouTube/DM support is proven unless an authorized real-provider test passed.
- Keep secrets out of source and logs; dry-run and human approval are mandatory release gates.
- Separate demo/simulation features from connected operations.
- Preserve copyright ownership by Md Najmul Hossain.
- Do not merge, push or deploy without the user's explicit instruction.
