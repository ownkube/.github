<div align="center">

# Ownkube

### A cloud for personal software.

One prompt to production.

[![Website](https://img.shields.io/badge/ownkube.io-FBBF24?style=for-the-badge)](https://ownkube.io)
[![Deploy my first app](https://img.shields.io/badge/Deploy_my_first_app-10B981?style=for-the-badge)](https://app.ownkube.io/login)
[![Docs](https://img.shields.io/badge/Docs-27272A?style=for-the-badge)](https://ownkube.io/docs)

</div>

---

Deploy your apps, Postgres, and Valkey cache in seconds. Connect a GitHub or GitLab repo, push, and get a live URL with HTTPS. You start without a cloud account or a config file. Apps draw from a prepaid wallet per minute, idle apps sleep, and unused credit never expires.

When a customer wants your app in their own cloud account, the same app moves there with no rewrite, and its logs, metrics, and health checks come with it.

Paste this into your coding agent:

```text
Fetch https://ownkube.io/prompt.md and follow it to deploy this repo on Ownkube.
```

Or use the CLI:

```sh
brew install ownkube/tap/okctl
```

Or start from the [Marketplace](https://ownkube.io/templates): n8n, Metabase, Grafana, Uptime Kuma, and more in one click, with managed Postgres and HTTPS wired in.

### Open source

| Repository | What it is |
|:---|:---|
| [ownkube-cli](https://github.com/ownkube/ownkube-cli) | `okctl`, the Ownkube CLI |
| [mcp](https://github.com/ownkube/mcp) | Hosted MCP server: deploy apps, Postgres, and Valkey from Claude Code, Cursor, Codex, or any MCP client |
| [keyseal](https://github.com/ownkube/keyseal) | Encrypted secrets in your repo, unlocked by your own key, rotated without a redeploy |
| [homebrew-tap](https://github.com/ownkube/homebrew-tap) | Homebrew tap for `okctl` |
| [kubernetes-events-exporter](https://github.com/ownkube/kubernetes-events-exporter) | Exports cluster events to 30+ sinks |

---

<div align="center">

[Docs](https://ownkube.io/docs) | [Pricing](https://ownkube.io/pricing) | [Marketplace](https://ownkube.io/templates) | [Agents](https://ownkube.io/agents) | [Blog](https://ownkube.io/blog) | [Changelog](https://ownkube.io/changelog)

</div>
