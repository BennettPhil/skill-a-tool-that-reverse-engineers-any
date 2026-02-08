---
name: a-tool-that-reverse-engineers-any
description: A tool that reverse-engineers any legacy codebase (COBOL, Fortran, VB6, Delphi, etc.) and produces a modern...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: A tool that reverse-engineers any legacy codebase (COBOL, Fortran, VB6, Delphi, etc.) and produces a modern equivalent in the language of your choice with full test coverage, architecture documentation, data migration scripts, API compatibility layer for existing integrations, and a phased migration plan with effort estimates.

# Context
Must handle codebases up to 10 million LOC and produce reports suitable for executive stakeholders.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: starter-builder description: A minimal, focused builder that generates clean Agent Skills from a single idea prompt. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.