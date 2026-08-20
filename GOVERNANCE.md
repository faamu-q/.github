# Governance

FAAMU repositories are maintained under a review-first model.

## Roles

### Maintainers
Maintainers are responsible for repository direction, access control, reviews,
releases and security decisions.

### Contributors
Contributors propose changes through issues and pull requests and are expected
to follow repository standards.

### Reviewers
Reviewers assess correctness, reproducibility, maintainability, security and,
where relevant, mathematical validity.

## Change control

Significant changes should be proposed through an issue or pull request before
they are adopted. Examples include:

- public API changes;
- model architecture or base-model changes;
- training-data changes;
- benchmark changes;
- licensing changes;
- release-policy changes;
- security-sensitive infrastructure changes.

## Merge policy

Repositories should prefer:

- protected default branches;
- pull-request review;
- required automated checks;
- no force pushes to protected branches;
- linear or otherwise auditable history.

Repository-specific rules take precedence when stricter controls are required.

## Releases

A release should have:

- an identifiable version or immutable revision;
- reproducible build or training metadata where applicable;
- a changelog or release notes;
- evaluation evidence appropriate to the artifact;
- known limitations;
- license and provenance checks.

## Conflicts of interest

Reviewers should disclose material conflicts and avoid being the sole approver
for changes where independent review is important.
