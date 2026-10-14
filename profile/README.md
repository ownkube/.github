<div align="center">

# Ownkube

### A cloud for personal software.

Ship like a giant. Stay lean like a startup.

[![Website](https://img.shields.io/badge/ownkube.io-FBBF24?style=for-the-badge)](https://ownkube.io)
[![Deploy my first app](https://img.shields.io/badge/Deploy_my_first_app-10B981?style=for-the-badge)](https://app.ownkube.io/login)
[![Docs](https://img.shields.io/badge/Docs-27272A?style=for-the-badge)](https://ownkube.io/docs)

</div>

---

Ownkube deploys your apps and databases in seconds. Connect a GitHub or GitLab repo, push to main, and get a live URL with TLS on a ready-to-share domain. There is no cloud account to set up and no config to write.

### What ships today

- Builds from source on every push, from your Dockerfile or detected automatically when there isn't one
- Automatic TLS and a ready-to-share `ownkube.app` domain for every web app
- Sleep and wake: idle apps, databases, and caches scale to zero and wake on the next request or connection
- Managed Postgres, with 7-day backups and point-in-time recovery on paid plans and standby replicas on Team
- Managed Valkey cache (Redis-compatible), one click
- Marketplace of open-source apps like n8n, Metabase, Directus, and Umami, deployed in one click with their database wired in
- Horizontal autoscaling on CPU and memory
- Live logs, CPU and memory metrics, request rate, p95 latency, and metric alerts for every deployment
- A data tab to browse tables and keys and run queries against your database or cache
- Shell and SSH into a running app, from the dashboard or with `okctl ssh`
- Scheduled jobs on a cron, with run history and run-now
- One-click rollback to a recent build

### Pricing you can predict

Usage is metered per minute and drawn from a prepaid balance, so a mostly idle app barely registers and a sleeping one costs nothing for compute. Start on Pay as you go by topping up from $5, with no subscription. Plans start at $5 a month, load that much credit each cycle, and unlock higher limits. Unused credit rolls over. Managed Postgres starts at $4 a month and a cache at $2 a month. Monthly budget caps and spending alerts keep the bill where you set it. [See pricing](https://ownkube.io/pricing).

### One prompt to production

Paste this into your coding agent from inside your repo:

```text
Fetch https://ownkube.io/prompt.md and follow it to deploy this repo on Ownkube.
```

Your agent deploys through the Ownkube MCP server and `okctl`. You sign in, connect GitHub, and approve the deploy. Claude Code, Cursor, Codex, and other coding agents are supported: [ownkube.io/agents](https://ownkube.io/agents).

Prefer the terminal yourself:

```sh
brew install ownkube/tap/okctl
okctl login
```

`okctl` covers projects, environments, deployments, logs, alerts, and marketplace apps, plus `okctl ssh` for shells and `okctl connect` for `psql` and `valkey-cli`. Every read command speaks `-o json`.

When you want it, the same app runs in your own AWS account with no rewrite, logs and metrics included. GCP and Azure are coming soon.

### Open source

| Repository | What it is |
|:---|:---|
| [ownkube-cli](https://github.com/ownkube/ownkube-cli) | `okctl`, the Ownkube command-line interface |
| [homebrew-tap](https://github.com/ownkube/homebrew-tap) | Homebrew tap for `okctl` |
| [kubernetes-events-exporter](https://github.com/ownkube/kubernetes-events-exporter) | Maintained fork that exports cluster events to 30+ sinks |

---

<div align="center">

[Deploy my first app](https://app.ownkube.io/login) | [Docs](https://ownkube.io/docs) | [Pricing](https://ownkube.io/pricing) | [Blog](https://ownkube.io/blog) | [Changelog](https://ownkube.io/changelog)

</div>
