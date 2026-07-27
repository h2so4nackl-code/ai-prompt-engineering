# AI Prompt Engineering

A practical knowledge base for designing, testing, and improving prompts used in AI evaluation, technical QA, troubleshooting, documentation, software testing, and workflow optimization.

The material is based on hands-on use of generative AI tools and focuses on repeatable methods rather than collections of isolated prompts. The examples are model-agnostic and designed to be adapted to real tasks without exposing private or sensitive information.

## Overview

Effective prompt engineering is a structured process: define the task, provide relevant context, set boundaries, specify the expected output, evaluate the result, and refine one variable at a time.

This repository provides:

- Practical prompt design principles
- Repeatable evaluation and testing workflows
- Troubleshooting and documentation methods
- Adaptable examples for common technical tasks
- Reusable templates for consistent prompt development

## Quick Start

If you're new to this repository, I recommend exploring the content in this order:

1. [Prompt Design Principles](docs/prompt-design-principles.md)
2. [AI Response Evaluation](docs/ai-response-evaluation.md)
3. [Technical Troubleshooting](docs/technical-troubleshooting.md)
4. [Software Testing & QA](docs/software-testing-and-qa.md)
5. [Practical Examples](examples/)
6. [Reusable Templates](templates/)

## Who Is This Repository For?

This repository is intended for:

- AI Evaluators
- Technical QA Testers
- Prompt Engineers
- Technical Writers
- AI Enthusiasts
- Anyone building reliable AI-assisted workflows

## Why prompt engineering matters

AI responses can sound confident while being incomplete, inconsistent, or incorrect. A well-designed prompt makes the objective and evaluation criteria explicit, which improves clarity, testability, and repeatability.

Prompt engineering does not replace verification. It creates a better process for identifying assumptions, checking evidence, reproducing results, and deciding whether an output is useful for its intended purpose.

## Prompt design principles

1. **Define the outcome.** State what a successful response must accomplish.
2. **Provide relevant context.** Include only the information needed to perform the task.
3. **Set clear constraints.** Identify scope, exclusions, safety requirements, and stopping conditions.
4. **Specify the output format.** Request a structure that makes the response easy to review and reuse.
5. **Separate facts from assumptions.** Ask the model to label uncertainty and missing information.
6. **Make verification explicit.** Define how claims, commands, or results should be checked.
7. **Iterate methodically.** Change one important variable at a time and compare the results.
8. **Protect sensitive data.** Never include credentials, private keys, personal data, or confidential content.

See [Prompt design principles](docs/prompt-design-principles.md) for a detailed checklist.

## Practical workflows

- [AI response evaluation](docs/ai-response-evaluation.md): assess accuracy, instruction following, clarity, completeness, consistency, and uncertainty.
- [Technical troubleshooting](docs/technical-troubleshooting.md): move from symptoms and evidence to testable hypotheses and verified actions.
- [Software testing and QA](docs/software-testing-and-qa.md): generate test coverage, reproduce failures, and document expected versus actual behavior.
- [Technical documentation](docs/technical-documentation.md): turn verified workflows into clear, audience-appropriate instructions.

The [examples](examples/) demonstrate how these methods can be applied, while the [templates](templates/) provide reusable starting points. The [case studies](case-studies/) show how to apply the methodology to fictional, anonymized scenarios.

## Common mistakes

- Starting with a vague objective
- Providing large amounts of irrelevant context
- Combining unrelated tasks in one prompt
- Leading the model toward a preferred conclusion
- Treating fluent output as verified output
- Asking for claims without requesting evidence or uncertainty
- Changing several prompt variables at once
- Omitting expected behavior, environment details, or constraints
- Sharing secrets or private information in prompt context
- Reusing generated commands without reviewing their effects

## Best practices

- Begin with a simple baseline prompt before adding complexity.
- Define evaluation criteria before reviewing the answer.
- Use consistent test cases when comparing prompt versions or AI tools.
- Record the prompt, relevant context, result, and observed limitations.
- Distinguish expected behavior from actual behavior in technical testing.
- Include negative cases, edge cases, and recovery paths.
- Ask for clarification when required information is missing.
- Verify important claims with authoritative sources or direct testing.
- Keep reusable prompts modular and easy to update.
- Review every final output for privacy, safety, and factual accuracy.

## Repository Highlights

- Practical prompt engineering guidance
- Repeatable evaluation workflows
- Technical troubleshooting methods
- Software testing patterns
- Documentation best practices
- Reusable templates
- Model-agnostic examples

## Repository structure

```text
ai-prompt-engineering/
|-- README.md
|-- LICENSE
|-- .gitignore
|-- case-studies/
|   |-- case-study-ai-evaluation.md
|   |-- case-study-bug-analysis.md
|   `-- case-study-documentation.md
|-- docs/
|   |-- ai-response-evaluation.md
|   |-- prompt-design-principles.md
|   |-- software-testing-and-qa.md
|   |-- technical-documentation.md
|   `-- technical-troubleshooting.md
|-- examples/
|   |-- documentation-review.md
|   |-- response-evaluation.md
|   |-- test-case-generation.md
|   `-- troubleshooting.md
`-- templates/
    |-- bug-reproduction-template.md
    |-- documentation-template.md
    |-- response-evaluation-template.md
    |-- structured-prompt-template.md
    `-- workflow-test-template.md
```

## Future improvements

- Add more sanitized, practical examples
- Expand evaluation criteria for different task types
- Add checklists for comparing prompt versions
- Document lightweight automation for repeatable evaluations

## Contributing

Suggestions, corrections, and improvements are welcome.

If you have ideas that improve prompt engineering, AI evaluation, documentation, or testing workflows, feel free to open an issue or submit a pull request.

## Disclaimer

The examples in this repository are intended for educational purposes and demonstrate general prompt engineering practices.

Always validate AI-generated outputs before using them in production or high-stakes environments.

## License

This project is available under the [MIT License](LICENSE).
