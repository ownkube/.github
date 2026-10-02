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
- Automatic TLS and a ready-to-share domain on Cloudflare's edge, with DDoS and bot protection included
- Managed Postgres with automatic backups, point-in-time recovery, and optional high availability
- Managed Valkey cache (Redis-compatible), one click
- Horizontal autoscaling on CPU and memory
- Live logs and CPU and memory metrics for every deployment
- Scheduled jobs on a cron, with run history and run-now
- One-click rollback to an earlier revision

### Pricing you can predict

Usage is metered per minute and drawn from a prepaid balance, so a mostly idle app barely registers. Plans start at $5 a month, which loads $5 of credit, and unused credit rolls over. Managed Postgres starts at $4 a month and a cache at $2 a month. Monthly budget caps and spending alerts keep the bill where you set it. [See pricing](https://ownkube.io/pricing).

### From your terminal or your coding agent

```sh
brew install ownkube/tap/okctl
okctl login
```

`okctl` covers clusters, environments, deployments, logs, and revisions, and every read command speaks `-o json`. You can also connect Claude Code, Cursor, Codex, and other coding agents to Ownkube over MCP: [ownkube.io/agents](https://ownkube.io/agents).

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
