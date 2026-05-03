# ChatGPT-Codex Connector Prompt Pack

This repository stores prompt files for a local document-analysis and report-generation agent.

## Important source note

The ChatGPT shared conversation link could not be opened from the current environment. Therefore, this repository-ready prompt pack is a clean assessed version based on the requested purpose: a safe local agent for reading, analysing, and processing documents on a PC.

Do not treat these files as a verbatim extraction from the shared ChatGPT conversation until the full shared-chat text is pasted or exported and reviewed.

## Purpose

The agent is intended to:

- read and analyse documents from explicitly allowed local folders only;
- generate technical summaries, reports, tables, and handover notes;
- save all outputs only to an approved output folder;
- avoid deletion or modification of source files;
- keep sensitive company, vessel, personal, credential, and commercial data out of public repositories.

## Prompt files

- `prompts/00_master_system_prompt.md` — main operating rules for the agent.
- `prompts/01_security_rules.md` — file access, data protection, and safety boundaries.
- `prompts/02_document_analysis_prompt.md` — rules for reading and analysing technical documents.
- `prompts/03_report_generation_prompt.md` — report-writing and output-format rules.
- `prompts/04_learning_and_memory_prompt.md` — controlled learning and preference handling.
- `prompts/05_quality_check_prompt.md` — final verification checklist before output.
- `assessment/prompt_assessment.md` — assessment of the prompt pack and improvement recommendations.

## Recommended loading order

```text
prompts/00_master_system_prompt.md
prompts/01_security_rules.md
prompts/02_document_analysis_prompt.md
prompts/03_report_generation_prompt.md
prompts/05_quality_check_prompt.md
```

Use `04_learning_and_memory_prompt.md` only if the agent has a controlled local memory mechanism.

## Security warning

Do not commit API keys, passwords, `.env` files, vessel documents, commercial quotations, certificates, crew data, client files, or confidential company documents to this public repository.
