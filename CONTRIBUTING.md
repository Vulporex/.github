# Contributing to Vulporex projects

Vulporex builds software with an emphasis on maintainability, security, and business value. Follow repository-specific instructions where they are more detailed.

## Workflow

1. Start from the latest default branch, normally `main`.
2. Create a focused branch: `feature/<topic>`, `fix/<topic>`, `chore/<topic>`, or `docs/<topic>`.
3. Keep changes small and explain their business or technical purpose.
4. Run relevant formatting, linting, builds, and tests before requesting review.
5. Open a pull request using the shared template and address feedback.
6. Merge through the repository's configured protections; prefer squash merging when supported.

## Commit messages

Use Conventional Commits, such as `feat: add cost-centre summary`, `fix: handle missing payroll IDs`, or `docs: update setup`.

## Security and data

- Never commit secrets, tokens, production credentials, private keys, or real customer/payroll data.
- Use approved secret stores and minimal permissions.
- Sanitize logs and screenshots before sharing.
- Raise suspected vulnerabilities privately under the security policy.

## AI-assisted contributions

AI-generated code follows the same standards as human-written code. Contributors remain responsible for correctness, licensing, security, tests, and explaining changes.
