# Report Generation Prompt

## Objective

Generate professional reports from analysed documents and user instructions.

Reports must be concise, technically accurate, structured, and suitable for business or marine/offshore engineering communication.

## Default Report Style

Use formal technical English.

Prefer:

- short paragraphs;
- clear headings;
- factual wording;
- no emotional language;
- no unsupported claims;
- concise conclusions;
- clear action ownership where known.

## Common Report Types

The agent may prepare:

- handover reports;
- work done reports;
- fault investigation reports;
- maintenance summaries;
- vendor clarification requests;
- procurement status reports;
- technical comparison reports;
- inspection summaries;
- risk and mitigation notes;
- meeting notes;
- timesheet comments;
- email drafts.

## Handover Report Rules

When preparing handover reports:

- summarise only operationally relevant information;
- include pending actions;
- include safety-related notes;
- include vendor/OEM follow-up;
- include open defects;
- include critical limitations;
- avoid unnecessary file references;
- avoid excessive detail unless needed.

Suggested structure:

```markdown
# Handover Report

## Overview

## Critical Items

## Work Completed

## Pending Work

## Technical Issues

## Vendor / OEM Follow-Up

## Safety and Operational Risks

## Recommended Next Actions
```

## Fault Report Rules

When preparing fault reports:

1. State the initial symptom.
2. State the timeline.
3. State troubleshooting performed.
4. State the root cause if confirmed.
5. State temporary actions.
6. State permanent corrective actions.
7. State remaining risks.

Suggested structure:

```markdown
# Fault Investigation Report

## Initial Reported Problem

## Timeline

## Troubleshooting Performed

## Findings

## Root Cause

## Corrective Action

## Current Status

## Recommendations
```

## Email Draft Rules

When preparing emails:

- keep the email concise;
- use polite professional tone;
- state the request clearly;
- include required technical details;
- avoid blame unless explicitly required;
- close with a clear action request.

## Risk and Mitigation Format

Use:

```markdown
**Risk:** <clear risk statement>

**Mitigation:** <clear mitigation or required action>
```

## Output File Naming

Recommended naming:

```text
handover_report_<vessel>_<YYYY-MM-DD>_v01.md
fault_report_<system>_<YYYY-MM-DD>_v01.md
technical_summary_<topic>_<YYYY-MM-DD>_v01.md
```

## Final Check

Before finalising any report, verify:

- names are consistent;
- dates are correct;
- units are correct;
- unresolved items are clearly marked;
- assumptions are listed;
- no confidential information is exposed unintentionally.
