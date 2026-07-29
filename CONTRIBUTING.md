# Contributing

This repository is maintained as a personal technology-learning laboratory.

## Contribution Principles

- Keep changes technically accurate and clearly documented.
- Use sanitized laboratory examples.
- Do not include employer, customer, or production information.
- Do not include passwords, tokens, private keys, or credentials.
- Test scripts and configuration files before committing.

## Recommended Workflow

1. Create a branch from main.
2. Make focused changes.
3. Validate the changes.
4. Review the Git diff.
5. Check for sensitive information.
6. Commit with a clear message.
7. Push the branch or submit a pull request.

## Commit Messages

Use clear messages such as:

- Add PostgreSQL replication lab
- Document Oracle RAC health checks
- Fix PowerShell path validation
- Update Azure ARM template examples

Avoid vague messages such as update, changes, test, final, or latest.

## Lab Documentation

A learning lab should document:

- Objective
- Prerequisites
- Architecture
- Implementation steps
- Validation
- Troubleshooting
- Cleanup
- Lessons learned
- References

## Security Review

Before committing, verify that no credentials, customer data, corporate data, internal hostnames, production IP addresses, subscription IDs, tenant IDs, or sensitive logs are present.

## Generated Files

Do not commit virtual environments, caches, temporary files, logs, build output, credentials, or machine-specific settings.
