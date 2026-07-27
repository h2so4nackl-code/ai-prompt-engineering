# Case Study: Structured AI Response Evaluation

> Fictional and anonymized educational scenario. It does not describe a customer, employer, or real project.

## Objective

Evaluate whether an AI assistant can explain a fictional account-recovery policy accurately, clearly, and without inventing unsupported exceptions.

## Evaluation setup

The evaluator receives:

- A short fictional policy document
- A user question about recovering access without the usual verification method
- A candidate AI response
- Predefined evaluation criteria

The policy document is treated as the only source of truth. The evaluator does not assume rules that are not stated in it.

## Method

1. Preserve the original question, policy text, and candidate response.
2. Break the policy into individual verifiable requirements.
3. Compare each response claim with the relevant policy statement.
4. Label findings as supported, unsupported, contradictory, or missing.
5. Review instruction following, clarity, completeness, and uncertainty separately.
6. Identify the smallest correction needed for each material issue.
7. Re-evaluate the revised response using the same criteria.

## Evaluation record

| Criterion | Question | Evidence to capture |
| --- | --- | --- |
| Accuracy | Does every policy claim match the supplied source? | Source statement and corresponding response text |
| Completeness | Are all required recovery steps included? | Missing or covered requirements |
| Clarity | Can the user understand the next safe action? | Ambiguous or actionable wording |
| Uncertainty | Does the answer acknowledge unavailable information? | Unsupported certainty or explicit limitation |
| Safety | Does the answer avoid bypassing identity verification? | Unsafe instruction or appropriate boundary |

## Analysis approach

The main risk is a fluent answer that introduces a plausible but unsupported exception. The review therefore prioritizes claim-level evidence over general writing quality. Style improvements are considered only after factual and safety issues are resolved.

## Deliverable

The final evaluation contains an evidence-based issue list, required corrections, unresolved questions, and a revised response outline. It does not assign fabricated performance scores or claim benchmark results.

## Reusable lesson

Define the source of truth and evaluation criteria before reviewing an AI response. This reduces subjective judgment and makes revisions easier to verify.
