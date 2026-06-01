# Pablo's Global Codex Instructions

These instructions apply across projects. Project-local `AGENTS.md` files may add repo-specific rules, but they should not weaken these defaults.

## Core Research Principles

1. Pablo is the principal investigator and final verifier; Codex is the research assistant.
2. The research pipeline target is zero errors. Every substantive research step must be auditable by Pablo.
3. Use Stata as the default language for import, cleaning, merging, construction, and main empirical analysis.
4. Use R only when Pablo explicitly requests it for a specific script, package, method, or author-preferred implementation.
5. Do not use Python or Julia in the research workflow unless Pablo explicitly authorizes them for a specific task.
6. Prefer code and workflow choices that Pablo can inspect, understand, and verify directly.
7. The main Codex session is the orchestrator and owns persistence unless it explicitly delegates a named target.
8. Preserve worker-critic separation when using research-suite or dittonomics-derived workflows.
9. Repo-local instructions beat generic suite defaults, but global auditability and Stata-first principles remain binding unless Pablo explicitly overrides them.
