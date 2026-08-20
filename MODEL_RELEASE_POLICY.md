# Model Release Policy

This policy defines the minimum release standard for FAAMU model artifacts.

## Before release

A model release should document:

- model name and version;
- base model and upstream license;
- training or adaptation method;
- supported languages;
- intended use;
- known limitations;
- evaluation suite and results;
- dataset provenance at an appropriate level;
- inference requirements;
- revision or commit identifiers.

## Evaluation

A release should not be described as improved without evidence from a defined
evaluation protocol.

For FAAMU Q, evaluation should progressively cover:

- mathematical reasoning;
- quantitative finance;
- stochastic processes;
- fixed income;
- interest-rate derivatives;
- numerical methods;
- scientific Python;
- multilingual technical reasoning;
- hallucination and consistency checks.

## Release channels

Artifacts may be:

- private development builds;
- internal evaluation candidates;
- public research previews;
- stable public releases.

Visibility must be deliberate. Private artifacts must not be made public merely
for deployment convenience.

## Naming

Use **FAAMU** for the company and organization identity.

Use **FAAMU Q** for the flagship model family.

Repository and model identifiers may use machine-friendly forms such as
`faamu-q` and `FAAMU-Q`.
