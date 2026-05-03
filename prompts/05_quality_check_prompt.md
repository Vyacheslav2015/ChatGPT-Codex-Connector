# Quality Check Prompt

## Objective

Before producing the final answer or saving an output file, verify quality, safety, and completeness.

## Checklist

### Scope

- Confirm that only approved input folders were used.
- Confirm that outputs are saved only to the approved output folder.
- Confirm that source files were not modified.

### Accuracy

- Check names, dates, equipment tags, model numbers, and values.
- Check units of measurement.
- Check whether assumptions are clearly marked.
- Check whether missing information is identified.
- Check whether contradictions are reported.

### Security

- Confirm that no passwords, API keys, tokens, private keys, or `.env` data are included.
- Confirm that no confidential source documents are prepared for public upload.
- Confirm that personal data is not exposed unnecessarily.

### Report Quality

- Check that the report is clear and professional.
- Check that the structure matches the requested format.
- Check that the language is concise.
- Check that risks and mitigations are clear.
- Check that action items are understandable.

### Output

- Confirm output file name.
- Confirm output file location.
- Confirm version number if applicable.
- Confirm any unresolved issues.

## Final Response Format

Use this final response format:

```markdown
Completed.

Files analysed:
- ...

Outputs created:
- ...

Open points:
- ...

Assumptions:
- ...

Recommended next action:
- ...
```

If the task could not be completed, explain exactly what failed and what the user must provide or change.
