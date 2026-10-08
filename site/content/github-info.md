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

### GitHub Copilot coding agent (formerly Copilot Workspace)
> Source: [GitHub Blog](https://github.blog/latest/)

GitHub Copilot can now act as a full coding agent directly inside GitHub. Assign an issue to Copilot, and it opens a pull request with working code, tests, and a summary of what it changed. You can review, comment, and iterate without leaving the GitHub UI.

**Practical tip:** Use the `copilot-setup-steps.yml` file in `.github/` to pre-install project dependencies so the agent has a ready environment when it spins up.

---

### Copilot extensions and MCP support
> Source: [GitHub Changelog](https://github.blog/changelog/)

GitHub Copilot now supports Model Context Protocol (MCP) servers inside GitHub Actions agentic workflows. Agents can call external tools—databases, APIs, internal services—using the standard MCP interface without custom glue code.

**Practical tip:** Declare MCP servers in your workflow's `with:` block. The agent runtime connects automatically; no extra auth wiring is needed for GitHub-hosted MCP servers.

---

### Agentic workflows in GitHub Actions
> Source: [GitHub Blog](https://github.blog/latest/) · [Awesome Copilot Workflows](https://awesome-copilot.github.com/)

GitHub Actions now supports agentic workflows: steps that embed an AI agent capable of reading code, calling tools, and writing outputs back to the repository or pull request. Common patterns include automated code review, changelog generation, and issue triage.

Community-maintained examples are catalogued at [awesome-copilot.github.com](https://awesome-copilot.github.com/), covering PR summarizers, security scanners, and release note generators.

**Practical tip:** Keep agent prompts focused and supply explicit stop conditions. Broad open-ended prompts tend to over-call tools and inflate costs.

---

### Pull request auto-merge improvements
> Source: [GitHub Changelog](https://github.blog/changelog/)

Auto-merge now respects required status checks more reliably across merge queues. If a check is added after auto-merge is enabled, GitHub re-evaluates eligibility automatically—no need to re-enable auto-merge on each PR.

---

### GitHub Actions: reusable workflows and `concurrency`
> Source: [GitHub Blog](https://github.blog/latest/)

Reusable workflows now fully support the `concurrency` key, letting callers cancel in-progress sibling runs when a newer commit is pushed. This is especially useful for CI pipelines where only the latest run matters.

```yaml
concurrency:
  group: ${{ github.workflow }}-${{ github.ref }}
  cancel-in-progress: true
```

---

### GitHub Models: experiment with AI models in the browser
> Source: [GitHub Blog](https://github.blog/latest/)

GitHub Models (github.com/marketplace/models) lets you compare and prompt foundation models—including GPT-4o, Claude, and Llama variants—directly in the browser with no API key setup. Use the playground to prototype prompts before wiring them into Actions or Copilot extensions.

---

## Useful references

| Topic | Link |
|---|---|
| Copilot coding agent docs | https://docs.github.com/copilot/using-github-copilot/using-copilot-coding-agent |
| GitHub Actions docs | https://docs.github.com/actions |
| GitHub Changelog | https://github.blog/changelog/ |
| GitHub Blog | https://github.blog/ |
| Awesome Copilot Workflows | https://awesome-copilot.github.com/ |
