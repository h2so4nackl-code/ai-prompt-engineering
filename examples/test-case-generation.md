# Example: Generating Workflow Test Cases

```text
Feature or workflow:
[Describe the workflow]

Environment:
[State the platform, version, and prerequisites]

Known requirements:
[List verified requirements]

Task:
Create test cases covering the primary path, negative cases, boundary conditions, interruption points, and recovery behavior.

Constraints:
- Do not invent undocumented requirements.
- Mark assumptions explicitly.
- Keep test data free of private or production information.
- Separate setup, action, expected result, and cleanup.

Output columns:
- Test ID
- Purpose
- Preconditions
- Steps
- Expected result
- Evidence to capture
- Cleanup or recovery
```
