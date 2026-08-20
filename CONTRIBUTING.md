# Contributing to FAAMU

Thank you for your interest in contributing.

FAAMU repositories may have different visibility, licensing and contribution
rules. Always read the repository-specific README, LICENSE and contribution
notes before submitting work.

## Principles

Contributions should prioritize:

1. technical correctness;
2. reproducibility;
3. clear assumptions;
4. deterministic or documented evaluation where possible;
5. appropriate tests;
6. traceable data and model provenance;
7. concise documentation.

## Development workflow

1. Open or reference an issue when the change is non-trivial.
2. Create a focused branch.
3. Keep changes scoped to one problem.
4. Add or update tests.
5. Run the relevant checks locally.
6. Open a pull request with a clear technical description.
7. Address review comments before merge.

## Quantitative and research contributions

For pricing, stochastic modelling, risk or empirical research changes:

- state the mathematical assumptions;
- define notation where needed;
- cite the source of formulas or datasets when applicable;
- distinguish theoretical identities from numerical approximations;
- include tolerances for numerical tests;
- document units, calendars, compounding and conventions;
- avoid look-ahead bias and untraceable data transformations.

## Model and evaluation contributions

For model, prompt, dataset or evaluation changes:

- identify the base model or upstream dependency;
- record dataset provenance and license;
- document train/evaluation splits;
- avoid benchmark contamination;
- report evaluation settings;
- separate measured results from interpretation;
- never fabricate metrics.

## Pull requests

A pull request should explain:

- what changed;
- why it changed;
- how it was tested;
- any mathematical, data, security or compatibility implications.

By contributing, you agree to follow the Code of Conduct and repository
licensing terms.
