# Security Policy

## Purpose

This repository contains personal learning material, technical documentation, laboratory exercises, sample configurations, and automation examples.

It must not contain real credentials, private keys, access tokens, passwords, customer information, corporate information, or production configuration data.

## Reporting a Security Concern

Do not publish sensitive security information in a public GitHub issue.

Use one of the following methods:

1. Use GitHub Private Vulnerability Reporting when it is enabled for this repository.
2. Contact the repository owner through the contact information provided on the GitHub profile.

Include:

- The affected file or component.
- A clear description of the concern.
- Steps required to reproduce the issue, when applicable.
- Recommended remediation, when known.

## Sensitive Information

The following content must never be committed:

- Passwords and authentication secrets.
- API keys and access tokens.
- Private keys, certificates, wallets, or keystores.
- Cloud subscription or tenant identifiers tied to real environments.
- Customer names, internal hostnames, or corporate network details.
- Production database exports, logs, or configuration files.
- Personally identifiable information.
- Proprietary employer or customer material.

## Example Configuration

Use sanitized example files such as:

- `.env.example`
- `config.example.yml`
- `parameters.example.json`
- `inventory.example.ini`

Real local configuration files should be excluded through `.gitignore`.

## Disclaimer

The examples in this repository are intended for personal learning and laboratory use. Review, test, and adapt them before use in any production environment.
