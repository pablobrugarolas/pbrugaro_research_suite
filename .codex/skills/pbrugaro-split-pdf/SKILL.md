---
name: pbrugaro-split-pdf
description: Codex wrapper for MixtapeTools split-pdf. Use for careful, staged reading of long academic PDFs by splitting, extracting structured notes, and preserving reusable text outputs.
---

# Pbrugaro Split PDF

This skill adapts the MixtapeTools `split-pdf` protocol for Codex.

## Source And Attribution

- Source fork: https://github.com/pablobrugarolas/MixtapeTools
- Upstream source: https://github.com/scunning1975/MixtapeTools
- Imported path: `external/mixtapetools/skills/split-pdf/`

Treat this as an external tool included in the Pbrugaro Research Suite.

## Communication Principle

When invoking this tool for the first time in a thread, tell Pablo that you are using the Split PDF tool from the research suite and explain why in one practical sentence.

## Codex Adaptation

The source instructions were written for Claude slash-command workflows. In Codex, use this skill as a staged PDF-reading workflow rather than a literal `/split-pdf` command.

Read the source protocol first:

1. `../../../external/mixtapetools/skills/split-pdf/README.md`

## Use When

- a paper is too long to read reliably in one pass
- Pablo wants structured extraction from a PDF
- notes should persist beside the PDF for future reuse
- a literature review needs careful paper-level evidence capture

## Output Preference

Preserve the original PDF. Write reusable notes or extracted text beside the source PDF or in a project-local build folder, following the source protocol.
