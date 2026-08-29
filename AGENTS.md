# evento-globolo — evgl-sidecar.rs

Canonical `evgl-sidecar.rs` for [`evento-globolo`](https://github.com/evento-globolo).

Inherits shared runtime from [`ores-otel/ores-otel-sidecar.rs`](https://github.com/ores-otel/ores-otel-sidecar.rs)
via zed-pkg (`ores-otel/ores-otel-sidecar`) and Cargo git.

- GitHub organization: https://github.com/evento-globolo
- This repository: https://github.com/evento-globolo/evgl-sidecar.rs
- Linear project: https://linear.app/denman/project/githubcomevento-globolo-4daaf1952e29
- GitHub org project: https://github.com/orgs/evento-globolo/projects/1
- Package / service name: `evgl-sidecar`
- Auth: github.com/shared-auth
- Sync: github.com/opto-sync
- Telemetry: github.com/ores-otel
- Flags: github.com/flags-2-env
- Packages: github.com/zed-pkg
- Never use React/JSX or webviews.
- Resolve git conflicts semantically; never rebase, stash, or reset.

## Functional programming conformance

This repository carries an FP conformance ratchet. Before you land a change:

```sh
python3 tools/fp-conformance/fp_conformance.py .
```

CI compares your findings against `tools/fp-conformance/budget.json` and fails
only when a rule's count *increases*. Do not raise the budget to get green — fix
the new violations. When you clear a class of violation, lower the budget in the
same commit with `--write-budget`.

The principles, the rule codes and the remedy for each are in `FP-GUIDELINES.md`.
