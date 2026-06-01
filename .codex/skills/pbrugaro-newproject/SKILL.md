---
name: pbrugaro-newproject
description: Codex wrapper for MixtapeTools newproject. Use for scaffolding a new empirical research project with code, data, outputs, documents, decks, notes, and progress logs.
---

# Pbrugaro New Project

This skill adapts the MixtapeTools `newproject` scaffold for Codex.

## Source And Attribution

- Source fork: https://github.com/pablobrugarolas/MixtapeTools
- Upstream source: https://github.com/scunning1975/MixtapeTools
- Imported path: `external/mixtapetools/skills/newproject/`

Treat this as an external tool included in the Pbrugaro Research Suite.

## Communication Principle

When invoking this tool for the first time in a thread, tell Pablo that you are using the New Project scaffold from the research suite and explain why in one practical sentence.

## Codex Adaptation

The source instructions were written for Claude slash-command workflows and refer to `CLAUDE.md`. In Codex projects, translate that persistent guidance into `AGENTS.md` unless the project already has another convention.

Read the source protocol first:

1. `../../../external/mixtapetools/skills/newproject/README.md`

## Use When

- starting a new empirical research project
- standardizing folders for code, raw data, clean data, figures, tables, notes, documents, and logs
- creating a project scaffold that works with Stata-first data cleaning and optional R/Python analysis

## Pbrugaro Defaults

Use Stata as the default home for data cleaning and main reduced-form scripts when appropriate. Keep `data/raw/` read-only by convention and use project-local logs or checkpoints for continuity across Codex sessions.
