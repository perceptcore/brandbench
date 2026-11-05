# Contributing to BrandBench

Help make AI brand evaluation inspectable and repeatable.

## Current stage

This repository is at the documentation foundation stage. No benchmark runner, dataset, scoring implementation, or test suite has been released. Early contributions should improve the research questions, methodology, and planned data formats.

## Propose a change

Open a feature proposal explaining the decision being evaluated, the proposed method, and the evidence needed. Discuss substantial dataset collection or implementation work in an issue before starting it.

Useful early contributions include buyer scenarios, annotation rubrics, run metadata requirements, and methods for measuring variation across repeated runs.

## Submit a pull request

1. Make a focused change on a branch in your fork.
2. Explain the research or usability problem, the change, and how you checked it.
3. Write documentation in English and distinguish planned behavior from released functionality.
4. Check Markdown and relative links. For future code or results, document the setup and relevant reproducibility checks.

## Research standard

- State how questions and brands were selected. Avoid constructing a test to favor PerceptCore or a selected vendor.
- Keep brand mentions, recommendations, factual accuracy, and citation support separate.
- Record providers, model identifiers, dates, settings, and collection interfaces when available. Distinguish API observations from consumer product observations.
- Preserve reference-source dates, sample sizes, repeated-run conditions, and limitations.
- Label model-judged results and human annotations separately. Disclose relevant commercial relationships.
- Do not infer business growth, causation, or overall AI visibility from a small prompt sample.

Use synthetic or explicitly publishable examples. Do not submit private customer data, account information, credentials, or material you lack permission to redistribute. Propose licensing and provenance before contributing a dataset. Follow [SECURITY.md](SECURITY.md) for sensitive issues.

By submitting a contribution, you confirm that you have the right to share it and agree that your contribution is licensed under this repository's [MIT license](LICENSE). Any future dataset release requires an explicit provenance and licensing review.
