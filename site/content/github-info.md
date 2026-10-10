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

## Latest updates

### GitHub Copilot

**Copilot coding agent (GitHub Changelog)**
GitHub Copilot now includes an agentic coding mode that can open pull requests autonomously. Assign an issue to Copilot or trigger it from a comment, and it will plan, write code, and submit a PR for review — all without leaving GitHub.
_Source: [github.blog/changelog](https://github.blog/changelog/)_

**Copilot in the CLI**
`gh copilot suggest` and `gh copilot explain` let you ask natural-language questions right in the terminal. Install with `gh extension install github/gh-copilot`.
_Source: [docs.github.com](https://docs.github.com/en/copilot/github-copilot-in-the-cli)_

**Multi-model support (GitHub Changelog)**
Copilot Chat now lets you pick the underlying model (GPT-4o, Claude Sonnet, Gemini, and others) per conversation so you can match the model to your task.
_Source: [github.blog/changelog](https://github.blog/changelog/)_

---

### GitHub Actions

**Agentic workflows with `gh-aw`**
GitHub Agentic Workflows (`gh-aw`) extend Actions with a declarative AI-agent layer. Workflows can spin up Copilot-powered agents that read context, call tools, and write back to the repository — all inside the standard Actions runtime.
_Source: [awesome-copilot.github.com](https://awesome-copilot.github.com/)_

**Reusable workflow improvements**
Calling workflows stored in other repositories is now simpler: `uses: owner/repo/.github/workflows/workflow.yml@ref` supports passing secrets and outputs back to the caller, making shared automation easier to maintain.
_Source: [docs.github.com](https://docs.github.com/en/actions/sharing-automations/reusing-workflows)_

---

### Collaboration & code review

**Pull request merge queue (GitHub Changelog)**
Enable a merge queue on protected branches so that PRs are tested together before merging. This prevents "works on my machine" failures when multiple PRs land at the same time.
_Source: [github.blog/changelog](https://github.blog/changelog/)_

**Code scanning with CodeQL (GitHub Blog)**
CodeQL default setup now auto-detects your language and runs without a workflow file. It also supports scanning pull requests from forks, which is useful for open-source maintainers.
_Source: [github.blog](https://github.blog/latest/)_

---

## Useful starting points

| Topic | Where to go |
|---|---|
| Learn Git basics | [docs.github.com/get-started](https://docs.github.com/en/get-started) |
| Copilot docs | [docs.github.com/copilot](https://docs.github.com/en/copilot) |
| Actions docs | [docs.github.com/actions](https://docs.github.com/en/actions) |
| GitHub Changelog | [github.blog/changelog](https://github.blog/changelog/) |
| GitHub Blog | [github.blog/latest](https://github.blog/latest/) |
| Awesome Copilot workflows | [awesome-copilot.github.com](https://awesome-copilot.github.com/) |
