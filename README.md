# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](https://github.com/awesome-copilot/awesome-copilot/graphs/contributors)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a community-driven fork of [github/awesome-copilot](https://github.com/github/awesome-copilot), extending the original with additional community contributions, agent workflows, and plugin marketplace integrations.

> **Personal fork note:** I'm using this primarily to track prompt libraries and agent workflows relevant to Go and TypeScript projects. Also collecting useful resources for CLI tooling and REST API design.

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Prompt Libraries](#prompt-libraries)
- [Agent Workflows](#agent-workflows)
- [Extensions & Plugins](#extensions--plugins)
- [Tools & Utilities](#tools--utilities)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom `.github/copilot-instructions.md` files to tailor Copilot behavior for your repository.

- [General Best Practices](.github/copilot-instructions.md) — Default instructions included in this repo.
- [Agentic Workflows](.github/agents/agentic-workflows.agent.md) — Instructions for multi-step agentic tasks.

## Prompt Libraries

Collections of reusable prompts for common development tasks.

- **Code Review** — Prompts for thorough, constructive code reviews.
- **Documentation** — Generate README files, docstrings, and API docs.
- **Testing** — Write unit tests, integration tests, and test plans.
- **Refactoring** — Improve code quality and maintainability.
- **Go-specific** — Prompts tailored for idiomatic Go: error handling, interfaces, goroutines. *(personal addition)*
- **TypeScript-specific** — Prompts for strict typing, generics, and async patterns. *(personal addition)*
- **REST API Design** — Prompts for OpenAPI specs, versioning, and consistent error responses. *(personal addition)*
- **SQL & Migrations** — Prompts for writing safe migrations and query optimization. *(personal addition)*

## Agent Workflows

Multi-step agentic workflows for complex tasks.

- [Agentic Workflows Agent](.github/agents/agentic-workflows.agent.md) — Automate end-to-end development tasks.
- [Actions Lock](.github/aw/actions-lock.json) — Pinned action versions for reproducible workflows.

## Extensions & Plugins

Copilot extensions and plugins available in the marketplace.

- [Marketplace Index](.github/plugin/marketplace.json) — Full index of available Copilot plugins.

## Tools & Utilities

- **awesome-copilot CLI** *(coming soon)* — Browse and install instructions/prompts from the command line.

## Learning Resources

- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [GitHub Copilot Extensions](https://github.com/features/copilot/extensions)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [Effective Go](https://go.dev/doc/effective_go)
- [Go by Example](https://gobyexample.com/) *(personal addition — great reference when writing Go-specific prompts)*
