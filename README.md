# D365FO TFVC Repository Template

[![source: GitHub](https://img.shields.io/badge/source-GitHub-181717?style=flat-square)](https://github.com/Oglaf/D365-TFVC-Repository-Template)
[![stack: D365FO + TFVC](https://img.shields.io/badge/stack-D365FO%20%2B%20TFVC-2563EB?style=flat-square)](https://github.com/Oglaf/D365-TFVC-Repository-Template/tree/master)
[![license: not declared](https://img.shields.io/badge/license-not%20declared-64748B?style=flat-square)](#license)

Minimal D365FO TFVC repository scaffold containing a main/Metadata ignore file; build and project configuration are not yet supplied.

## Technology stack

D365FO + TFVC. Use the tracked manifests and platform-specific setup documentation for exact requirements.

## Project architecture

This is a small repository scaffold, not a runnable application. The only tracked scaffold file is `main/Metadata/.tfignore`; a `main/Projects/` directory is not currently tracked.

## Getting started

Clone the repository and review `main/Metadata/.tfignore`. Configure your own Azure DevOps TFVC workspace and D365FO model/project mappings before using it as a template. GitHub stores this template; it does not itself provide a TFVC server.

## Project structure

- [`main/`](main/)
- [`main/Metadata/.tfignore`](main/Metadata/.tfignore) — tracked TFVC ignore rules.

## Key features

- A main/Metadata directory convention.
- A TFVC ignore-rule starting point.

## Development workflow

No GitHub Actions workflow is tracked. Root Azure Pipelines YAML, where present, is separate and was not changed by this GitHub Actions policy.

## Coding standards

Keep TFVC ignore rules scoped to generated files; do not hide model source or required metadata.

## Testing

No application, CI workflow, build definition or automated tests are tracked. Validate ignore rules and workspace mappings in a disposable D365FO workspace after adding real project configuration.

## Contributing

Keep changes focused, document prerequisites and the checks actually performed, and review the diff before publication. Use non-production environments and fictional data for any explicitly approved live checks.

## License

No repository license is declared. Do not assume open-source reuse or redistribution rights.
