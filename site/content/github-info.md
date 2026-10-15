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

## Recent updates — October 2026

### GitHub Actions: Workflow lockfiles in public preview
*(Source: [GitHub Changelog, Oct 14](https://github.blog/changelog/2026-10-14-github-actions-workflow-lockfiles-in-public-preview))*

Tags and branches can silently move after you review a workflow, letting a later run execute different code. Workflow lockfiles pin each action to the exact commit you reviewed. Install the `gh actions-lock` CLI extension, run it to generate `.github/workflows/actions.lock`, and your runs stay tied to locked commits. Now in public preview for Free, Team, Enterprise Cloud, and Enterprise Cloud with data residency.

### GitHub Copilot: Gemini 4 Argon now generally available
*(Source: [GitHub Changelog, Oct 13](https://github.blog/changelog/2026-10-13-gemini-4-argon-in-github-copilot))*

Google's Gemini 4 Argon is available in the Copilot model picker for Pro+, Max, Business, and Enterprise plans. It targets complex coding, agentic, and reasoning tasks, outperforming previous Gemini models on every coding benchmark — with the largest gains in Copilot CLI. Select it in VS Code, JetBrains, Xcode, Visual Studio, Copilot CLI, the coding agent, or the Copilot app.

### GitHub Copilot: HydraFusion updates and new Max option
*(Source: [GitHub Changelog, Oct 14](https://github.blog/changelog/2026-10-14-hydrafusion-updates-and-new-max-option))*

HydraFusion (research preview) orchestrates multiple frontier models behind a single response. The updated pool now includes Claude Opus 5.5, GPT-6 Astra, GPT-6.1 Sol, and GPT-6 Luna. Reasoning effort is now tuned per stage — medium for drafting, high for review — making it more efficient without sacrificing depth. A new **HydraFusion Max** tier is also available in VS Code, the Copilot app, and CLI.

### Secret scanning: Anthropic keys blocked by default
*(Source: [GitHub Changelog, Oct 13](https://github.blog/changelog/2026-10-13-secret-scanning-blocks-anthropic-keys-by-default-adds-salesforce))*

GitHub secret scanning now blocks Anthropic API keys by default on push protection, and has added Salesforce to its partner list. No configuration needed — repos with push protection enabled are automatically covered.

### GitHub Actions: Secret scanning AI metrics in security overview
*(Source: [GitHub Changelog, Oct 13](https://github.blog/changelog/2026-10-13-code-scanning-ai-scan-metrics-in-security-overview))*

The security overview dashboard now shows AI Scan metrics for code scanning, giving teams visibility into how AI-powered analysis is performing across their organization.

---

## Recommended reading from the GitHub Blog

- **[How to teach Copilot about your codebase](https://github.blog/ai-and-ml/github-copilot/github-copilot-app-for-beginners-how-to-teach-copilot-about-your-codebase/)** — beginner-friendly guide to context files and custom instructions.
- **[Building Git infrastructure for agent-scale development](https://github.blog/engineering/architecture-optimization/building-git-infrastructure-for-agent-scale-development/)** — how GitHub is scaling Git itself for agentic workloads.
- **[ReviewBench: An open benchmark for AI code review](https://github.blog/ai-and-ml/github-copilot/reviewbench-an-open-benchmark-for-ai-code-review/)** — GitHub's open benchmark for evaluating AI-driven code review quality.

---

## Awesome Copilot community resources
*(Source: [awesome-copilot.github.com](https://awesome-copilot.github.com/))*

The community library for GitHub Copilot surfaces 383+ reusable items across:

| Category | Count | What it includes |
|----------|-------|-----------------|
| Agents | 222 | Custom agents with specialized skills |
| Instructions | 194 | Coding standards that steer Copilot output |
| Skills | 430 | Self-contained folders bundling instructions + resources |
| Plugins | 177 | Curated plugins that extend Copilot |
| Extensions | 49 | Interactive canvas extensions for the Copilot app |
| Learning Hub | 407 | Articles and guides |

Browse at [awesome-copilot.github.com](https://awesome-copilot.github.com/) to find reusable components for your own Copilot workflows.
