# Contributing

Thanks for considering contributing.

## Principles

- Each architecture must be **runnable** and **tested**.
- Documentation is part of the deliverable: every architecture has its own README.
- Prefer clarity over cleverness.

## Requirements for a new architecture

- Folder under `/architectures/<id>-<name>/`
- `README.md` explaining: purpose, trade-offs, diagram, how to run
- `src/` and `tests/` projects
- Must pass:
  - `dotnet build`
  - `dotnet test`

## Pull requests

- Keep PRs focused.
- Include a short description of what changed and why.
