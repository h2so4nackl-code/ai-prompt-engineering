# Example: Troubleshooting a CLI Failure

This is an illustrative prompt framework, not a record of a specific incident.

```text
Goal:
Help diagnose a CLI command that exits unsuccessfully.

Expected behavior:
[Describe the expected result]

Actual behavior:
[Describe what happened]

Environment:
- Operating system: [value]
- CLI version: [value]
- Command: [sanitized command]
- Exact error: [sanitized output]
- Recent changes: [value or none known]

Requirements:
1. Separate confirmed observations from hypotheses.
2. Rank hypotheses by the available evidence.
3. Begin with read-only diagnostic checks.
4. Explain what each check would confirm or rule out.
5. Flag any command that changes system or user data.
6. Do not assume missing environment details.

Output:
- Evidence summary
- Ranked hypotheses
- Diagnostic sequence
- Verification criteria
- Missing information
```
