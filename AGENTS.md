# Pbrugaro Research Suite Instructions

This file adds repo-specific instructions for the Pbrugaro Research Suite. It assumes Pablo's global Codex instructions in `C:\Users\bruga\.codex\AGENTS.md` are active, especially the Stata-first, auditability, and PI/final-verifier principles.

## Core Principles

1. Follow Pablo's global Codex instructions first.
2. Use this repository as a suite of reusable research tools, not as a single research project.
3. Keep the main Codex session as the orchestrator when routing through suite skills.
4. Preserve worker-critic separation when using dittonomics-derived workflows.
5. Repo-local instructions beat generic suite defaults for this repository.

## First-Use Communication

When invoking a Pbrugaro Research Suite skill for the first time in a thread, briefly tell Pablo which tool is being used and why.

Example: "I am using the GTD tool from your research suite because this task is about turning a conjecture into a falsifiable claim."

## Tool Stack

- `pbrugaro_research_suite`: global entry point for the suite
- `clo-workflow`: workflow kernel, routing rules, artifacts, lifecycle checks
- `clo-ideate`: research-question ideation
- `clo-discover`: literature and evidence discovery
- `clo-strategize`: project strategy
- `clo-analyze`: analysis planning and code/report review
- `clo-write`: manuscript drafting
- `clo-review`: quality/referee-style review
- `clo-revise`: revision roadmap and task graph
- `clo-submit`: submission checks
- `clo-talk`: talks and presentations
- `pbrugaro-gtd`: hypotheses, insights, decisions, and warrant tracking
- `pbrugaro-referee2`: independent audit of completed empirical projects
- `pbrugaro-split-pdf`: staged academic PDF reading
- `pbrugaro-newproject`: empirical project scaffold

## Repository Map

- `.codex/skills/`: active Codex skill definitions and wrappers
- `.codex/agents/`: dittonomics-derived custom agent definitions
- `external/mixtapetools/`: vendored tools imported from Pablo's MixtapeTools fork
- `guide/` and `docs/`: inherited dittonomics documentation site materials
- `voice/`: optional writing-voice templates

## Git And Source Policy

- Keep `main` as the stable suite branch.
- Use short feature branches for imports or experiments, merge when accepted, then delete the branch.
- Treat `sebastianritterg/dittonomics` as upstream for the core suite.
- Treat `pablobrugarolas/MixtapeTools` as the source fork for imported MixtapeTools components.
- Imported external tools are vendored copies, not live submodules; update them deliberately.

## README Policy

Keep `README.md` concise and human-facing. Do not turn it into a full instruction manual. Put durable global behavior in `C:\Users\bruga\.codex\AGENTS.md`; put suite-specific behavior here; put detailed workflows in skills or references.
