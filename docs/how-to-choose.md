# How to Choose a .NET Architecture

This repository contains multiple .NET architectures, each optimized for different constraints.

## Quick guidance

- **Layered (N-Tier)**: best for simple CRUD systems and smaller teams.
- **Clean Architecture**: best when you want strict separation, testability, and long-term maintainability.
- **DDD + CQRS**: best for complex domains with many business rules and evolving requirements.
- **Vertical Slice**: best for product teams shipping fast with feature-based organization.

## What to consider

1. **Domain complexity**: Is the business logic simple or rich?
2. **Team size and experience**: Can the team maintain advanced patterns?
3. **Time-to-market**: Do you need to ship quickly?
4. **Longevity**: Is this a long-lived platform?
5. **Operational complexity**: Are you ready for messaging, eventual consistency, etc.?

## Rule of thumb

Start simple. Add complexity only when you have strong reasons.
