# .NET Architectures Catalog

A practical catalog of .NET architectural patterns with ready-to-run examples, documentation, and conventions.

## Architectures

| # | Architecture | Use when | Link |
|---|-------------|----------|------|
| 01 | Layered (N-Tier) | Simple to medium CRUD systems, smaller teams | `architectures/01-layered` |
| 02 | Clean Architecture | Strong separation, testability, long-term maintainability | `architectures/02-clean-architecture` |
| 03 | DDD + CQRS | Complex domains with rich business rules | `architectures/03-ddd-cqrs` |
| 04 | Vertical Slice | Feature-based development, fast iteration | `architectures/04-vertical-slice` |

## How to choose

See: `docs/how-to-choose.md`

## Goals

- Each architecture is **functional** (not pseudo-code).
- Each example includes **unit + integration tests**.
- Each architecture has a dedicated **README** explaining decisions and trade-offs.

## License

MIT
