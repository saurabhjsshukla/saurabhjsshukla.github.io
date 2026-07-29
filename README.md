# saurabhjsshukla.github.io

## Overview

This repository contains the source for Saurabh Shukla's technical documentation and portfolio website.

The site is built with MkDocs Material and published through GitHub Pages.

## Purpose

The website acts as the public presentation layer for sanitized technical knowledge developed across personal learning repositories.

Content may include:

- Technical guides
- Architecture explanations
- Laboratory summaries
- Reusable runbooks
- Troubleshooting documentation
- Learning roadmaps
- Portfolio material

## Repository Structure

- .github/workflows — GitHub Actions deployment workflow
- docs — website pages and technical documentation
- docs/index.md — website homepage
- mkdocs.yml — MkDocs configuration and navigation
- create_structure.ps1 — repository-structure utility
- README.md — repository overview

## Documentation Areas

- Cloud
- Containers
- DevOps
- Monitoring
- NoSQL
- Operating systems and virtualization
- Relational databases
- Scripting and automation

## Local Preview

After installing the required Python and MkDocs dependencies, start the local development server with:

mkdocs serve

Open the local address displayed by MkDocs to review the website before publishing.

## Deployment

Changes pushed to the main branch are deployed through the configured GitHub Actions workflow.

The generated gh-pages branch may be recreated or force-updated by the deployment process.

## Content Workflow

1. Develop and validate technical material in the appropriate engineering repository.
2. Remove environment-specific, employer, customer, and confidential information.
3. Convert the material into a general reusable article or guide.
4. Add the sanitized documentation under docs.
5. Preview the site locally.
6. Review navigation, formatting, and links.
7. Commit and publish the approved content.

## Repository Standards

- Keep documentation technically accurate and clearly structured.
- Use sanitized examples rather than real environment configuration.
- Verify internal and external links before publishing.
- Keep MkDocs navigation synchronized with documentation files.
- Record meaningful changes in CHANGELOG.md.

## Security Boundary

Only sanitized personal technical material may be published.

Do not publish credentials, secrets, customer names, employer information, internal hostnames, private IP addresses, subscription identifiers, production logs, or proprietary documents.

Review SECURITY.md before publishing changes.

## Related Files

- CONTRIBUTING.md — contribution and documentation practices
- SECURITY.md — security and information-handling requirements
- CHANGELOG.md — repository change history
- mkdocs.yml — site configuration and navigation
