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

## Recent Updates

### GitHub Copilot Coding Agent — Now Generally Available
*Source: [GitHub Changelog](https://github.blog/changelog/)*

The Copilot Coding Agent is now GA for GitHub Copilot Individual, Business, and Enterprise plans. Assign an issue to Copilot and it opens a pull request autonomously. New in this release:

- **Works on human-created PRs** — Copilot can continue work on existing pull requests, not just new ones it opens itself.
- **Runs on self-hosted runners** — The coding agent now supports self-hosted GitHub Actions runners for teams with custom environments.
- **Progress tracking & session management** — Monitor agent sessions directly in the GitHub UI; also available on GHES 3.22+.
- **JetBrains IDE support (Preview)** — The coding agent is now accessible inside JetBrains IDEs.

---

### GitHub Copilot: More AI Shortcuts on GitHub.com
*Source: [GitHub Changelog](https://github.blog/changelog/)*

- **Commit message generation (GA)** — Copilot suggests commit messages in the GitHub web editor. Available on GHES 3.20+.
- **Code scanning alert fixes** — Assign code scanning alerts directly to Copilot for an automated fix suggestion (Preview).
- **MCP server allowlists** — Admins can now manage and allowlist MCP servers used by Copilot in JetBrains, Eclipse, and Xcode (Preview).

---

### GitHub Actions: New Features for Large Workflows
*Source: [GitHub Changelog](https://github.blog/changelog/)*

- **300+ jobs with UI filtering (Preview)** — Workflows with hundreds of jobs are easier to navigate with new filtering in the Actions run view. Available on GHES 3.21+.
- **`${{ if }}` conditional operator (GA)** — A cleaner syntax for branching logic inside workflow expressions.
- **`workflow_dispatch` returns `runID` (GA)** — The API now returns the run ID immediately when triggering a workflow, making chaining and tracking programmatic triggers much easier.
- **New 1 vCPU hosted runner (Preview)** — A smaller, cost-effective runner for lightweight CI tasks.
- **Actions Runner Controller 0.15.0 (GA)** — Kubernetes-based self-hosted runners are now generally available for all plans.

---

### Security & Compliance Updates
*Source: [GitHub Changelog](https://github.blog/changelog/)*

- **Secret scanning metadata & ownership checks (Preview)** — GitHub can now determine ownership and severity of leaked secrets for faster triage.
- **Dependabot alert assignment (GA)** — Assign Dependabot alerts to individual developers. Available on GHES 3.21+.
- **Open source license compliance detection (Preview)** — Track open source license usage across repositories to stay compliant.
- **Managing low-quality issue comments (GA)** — New controls help maintainers suppress spam and noise from issue threads.

---

### Enterprise AI Budget Controls
*Source: [GitHub Changelog](https://github.blog/changelog/)*

- **Premium requests & feature-level budgeting (GA)** — Enterprise admins can set per-feature AI budgets to manage costs. Available on GHES 3.20+.
- **Enterprise agent control plane (Preview)** — Policy controls for governing AI agent behavior at scale across an organization.

---

### Explore: Awesome Copilot
*Source: [awesome-copilot.github.com](https://awesome-copilot.github.com/)*

The community-curated **Awesome Copilot** catalog (39,000+ stars) is a go-to resource for extending GitHub Copilot:

| Resource | What it is |
|----------|-----------|
| [Agents](https://awesome-copilot.github.com/agents) | 220+ specialized agents (debugging, TDD, Terraform, security scanning, and more) |
| [Skills](https://awesome-copilot.github.com/skills) | 400+ self-contained skills like `conventional-commit`, `github-actions-hardening`, `code-tour` |
| [Plugins](https://awesome-copilot.github.com/plugins) | Curated bundles such as `pr-review`, `security-best-practices`, `devops-oncall` |
| [Learning Hub](https://awesome-copilot.github.com/learning-hub) | Guides covering agents, skills, MCP integration, and agentic workflows |

**Quick install:** `copilot plugin install <plugin-name>@awesome-copilot`

**Highlights worth trying:**
- `github-actions-expert.agent.md` — CI/CD workflow authoring guidance.
- `sast-sca-security-analyzer.agent.md` — SAST + SCA vulnerability analysis.
- `pr-review` plugin — Automated pull request review workflow.
- `context-engineering` plugin — Prompting best practices for Copilot.
