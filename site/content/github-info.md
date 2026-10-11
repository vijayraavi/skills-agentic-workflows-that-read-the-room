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

## What's new on GitHub

### GitHub Copilot: Agent mode and coding agent

GitHub Copilot now supports **agent mode** in VS Code and other editors, letting Copilot autonomously plan and execute multi-step coding tasks — writing code, running terminal commands, and iterating on test results without constant prompting.

The **Copilot coding agent** (formerly Copilot Workspace) takes this further: assign a GitHub issue to Copilot and it opens a pull request with a proposed fix. You review and merge when ready.

> Source: [github.blog/changelog](https://github.blog/changelog/)

### GitHub Copilot for pull requests

Copilot can now generate **pull request summaries** automatically. When you open a PR, Copilot analyzes the diff and drafts a description — saving time and improving review quality.

Enable it per repository under **Settings → Copilot → Pull request summaries**.

> Source: [github.blog/changelog](https://github.blog/changelog/)

### GitHub Actions: Reusable workflows and required workflows

- **Reusable workflows** let you call one workflow YAML from another, reducing duplication across repositories.
- **Required workflows** (org-level) enforce a standard CI job on every repository in an organization without editing each repo's `.github/workflows/` folder.

> Source: [docs.github.com](https://docs.github.com)

### GitHub Models: Prototype with AI directly on GitHub

**GitHub Models** gives developers free access to frontier AI models (including GPT-4o, Llama, Mistral, and others) directly from github.com. Use the playground to experiment, then drop a model into your app via the Azure AI inference SDK.

Try it at [github.com/marketplace/models](https://github.com/marketplace/models).

> Source: [github.blog](https://github.blog/latest/)

### Awesome Copilot workflows

The [Awesome Copilot workflows](https://awesome-copilot.github.com/) community catalog lists reusable GitHub Agentic Workflows you can drop into your own repository. Highlights include:

- **Code review workflows** — automated PR feedback powered by Copilot.
- **Release note generators** — draft changelogs from merged PRs.
- **Dependency update reviewers** — summarize Dependabot PRs with AI context.

> Source: [awesome-copilot.github.com](https://awesome-copilot.github.com/)

### Tips for faster GitHub collaboration

1. **Draft pull requests** signal work-in-progress without requesting reviews prematurely.
2. **Branch protection rules** with required status checks prevent broken code from landing on `main`.
3. **Merge queues** serialize concurrent PRs, running CI once and merging atomically.
4. **Discussions** keep longer-form conversations out of issues and code reviews.
