# Repository Standards

## Recommended baseline

Every substantive repository should include:

- `README.md`
- `LICENSE` when distribution terms are defined
- `CONTRIBUTING.md` or inherited organization guidance
- tests
- dependency metadata
- CI
- changelog or release notes for versioned software
- provenance notes for datasets or models

## Python

Recommended standards:

- Python 3.11+ unless compatibility requirements dictate otherwise;
- `pyproject.toml` for packaging/configuration;
- `ruff` for linting and formatting;
- `pytest` for tests;
- type checking for public or critical interfaces;
- deterministic seeds for numerical tests where applicable.

## Quantitative code

Numerical code should make conventions explicit:

- day-count conventions;
- calendars;
- compounding;
- currency;
- units;
- interpolation;
- tolerances;
- random seeds.

Tests should cover both identities/invariants and numerical examples.

## Model repositories

Model repositories should separate:

- model configuration;
- tokenizer/config assets;
- training configuration;
- evaluation;
- inference examples;
- model card;
- provenance and license notes.

Do not store secrets or unrestricted copies of licensed third-party datasets.
