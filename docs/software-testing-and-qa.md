# Software Testing and QA

## Purpose

Structured prompts can help turn requirements and observed behavior into test cases, reproduction steps, and clear reports.

## Workflow

1. Define the feature, environment, and expected behavior.
2. Identify the main success path.
3. Add negative cases, boundary conditions, invalid inputs, and recovery paths.
4. Record prerequisites and test data without including secrets.
5. Execute each test and capture the actual result.
6. Minimize reproducible failures to the smallest reliable sequence.
7. Document impact, evidence, and unresolved questions.
8. Re-test after a change using the same steps.

## Review questions

- Can another person reproduce the test?
- Are expected and actual results separated?
- Are environment details sufficient?
- Does the report avoid unsupported conclusions?
- Are destructive steps clearly identified?
