---
name: pbrugaro-referee2
description: Codex wrapper for MixtapeTools referee2. Use for independent referee-style audits of completed empirical research projects, including code review, replication readiness, output automation, econometric credibility, and cross-language replication planning.
---

# Pbrugaro Referee 2

This skill adapts the MixtapeTools `referee2` protocol for Codex.

## Source And Attribution

- Source fork: https://github.com/pablobrugarolas/MixtapeTools
- Upstream source: https://github.com/scunning1975/MixtapeTools
- Imported path: `external/mixtapetools/skills/referee2/`

Treat this as an external tool included in the Pbrugaro Research Suite.

## Communication Principle

When invoking this tool for the first time in a thread, tell Pablo that you are using the Referee 2 audit tool from the research suite and explain why in one practical sentence.

## Codex Adaptation

The source instructions were written for Claude slash-command workflows. In Codex, use this skill as a structured audit protocol rather than a literal `/referee2` command.

Read the source protocol first:

1. `../../../external/mixtapetools/skills/referee2/README.md`

## Use When

- a project is close to complete and needs an independent audit
- code, tables, or figures need referee-style scrutiny
- a replication package needs readiness checks
- empirical claims need implementation and econometric stress-testing

## Guardrails

Do not modify the author's analysis code during a Referee 2 audit unless Pablo explicitly asks for fixes. Prefer findings, line references, replication checks, and a written audit report.
