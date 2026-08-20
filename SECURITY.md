# Security Policy

## Reporting a vulnerability

Do not open a public issue for vulnerabilities, leaked credentials, private
model artifacts, restricted datasets or other security-sensitive findings.

Use GitHub's private vulnerability reporting feature when it is enabled for the
affected repository. If private reporting is not available, contact the
repository maintainers through the private channel listed in that repository.

## Scope

Security reports may include:

- credential or secret exposure;
- unsafe deserialization or code execution;
- dependency vulnerabilities;
- authorization or access-control flaws;
- model-serving vulnerabilities;
- data leakage;
- prompt or tool paths that expose restricted information;
- supply-chain risks.

## Secrets

Never commit API keys, tokens, private keys, passwords, connection strings or
restricted Hugging Face credentials.

Secrets must be stored through approved secret-management mechanisms such as
GitHub Actions secrets, environment variables or deployment-provider secret
stores.

## Supported versions

Individual repositories define their own supported versions. Security fixes are
normally applied to actively maintained branches and releases.
