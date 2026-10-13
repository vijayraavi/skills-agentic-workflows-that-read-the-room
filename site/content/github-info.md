# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

---

## Recent updates

### GitHub Copilot coding agent (GitHub Blog)

GitHub Copilot now includes a **coding agent** that can open pull requests autonomously. Assign an issue to Copilot and it will create a branch, write code, run checks, and open a draft PR for review. Available on Copilot Pro+, Team, and Enterprise plans.

> Source: [github.blog](https://github.blog/)

### GitHub Copilot in GitHub Actions workflows (GitHub Changelog)

Copilot can be invoked inside GitHub Actions using the agentic workflows runtime. Workflows describe tasks in natural language and delegate them to a Copilot-powered agent step, keeping automation close to the code.

> Source: [github.blog/changelog](https://github.blog/changelog/)

### MCP support in GitHub Copilot (GitHub Changelog)

GitHub Copilot supports the **Model Context Protocol (MCP)**, letting you connect external tools and data sources—databases, APIs, custom services—directly to Copilot's context. Useful for workflows that reach beyond the repository.

> Source: [github.blog/changelog](https://github.blog/changelog/)

### Awesome Copilot workflows (Awesome Copilot)

The community-maintained [Awesome Copilot](https://awesome-copilot.github.com/) site curates ready-to-use agentic workflow examples: PR reviewers, issue triagers, release note generators, and security scanners. A practical starting point for automating GitHub tasks with Copilot.

> Source: [awesome-copilot.github.com](https://awesome-copilot.github.com/)

### Custom instructions for Copilot (GitHub Changelog)

Add a `.github/copilot-instructions.md` file to give Copilot persistent context—preferred languages, code style, architectural guidelines—so every suggestion stays consistent with project conventions.

> Source: [github.blog/changelog](https://github.blog/changelog/)

### GitHub Actions: required workflows via rulesets (GitHub Blog)

Repository admins can enforce **required workflows** through branch rulesets, ensuring CI checks always run before a merge regardless of the target branch's workflow files. Simplifies compliance across forks and monorepos.

> Source: [github.blog](https://github.blog/)
