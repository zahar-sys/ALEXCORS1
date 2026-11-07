# Repository Guidelines

## Project Structure & Module Organization

This directory currently contains no application code, tests, assets, or dependency manifests. No framework or language has been selected. Keep this guide aligned with the actual layout as the project develops.

When adding the initial implementation, group application code in `src/`, tests in `tests/`, and static resources in `assets/` unless the chosen framework requires another layout. Document setup and architecture in `README.md`. These paths are proposed conventions, not existing directories.

## Build, Test, and Development Commands

No build, test, or development commands are currently configured. Do not assume commands such as `npm test` or `make build` work.

When introducing tooling, provide reproducible commands for dependency installation, local development, production builds, and tests. Record the exact commands and required runtime versions in `README.md`, and commit the appropriate dependency lockfile.

## Coding Style & Naming Conventions

No formatter, linter, or indentation standard exists yet. Select language-appropriate tooling with the first implementation and commit its configuration. Use consistent indentation, descriptive names, and the selected language's naming conventions. Keep modules focused and avoid mixing unrelated responsibilities.

## Testing Guidelines

No testing framework or coverage threshold is configured. Add tests alongside new behavior once a framework is selected. Use descriptive test names that identify the behavior and expected result. Cover important success paths, validation failures, and regressions; document how contributors run the suite.

## Commit & Pull Request Guidelines

This directory has no Git history, so no existing commit convention can be inferred. Use short, imperative subjects, such as `Add product catalog`, and keep commits focused.

Pull requests should explain the change, reference relevant issues, and state what validation was performed. Include screenshots for visible interface changes and identify any setup or configuration changes.

## Security & Configuration

Keep credentials and local environment files out of version control. Provide placeholder configuration examples when needed, and exclude generated output and installed dependencies through `.gitignore` when introducing tooling.
