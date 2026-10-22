# Globe Teck

Open-source tools for safe AI agents, small-business hosting, and ops automation.

## Repositories

- [llm-redteam-harness](https://github.com/globe-teck/llm-redteam-harness): Small Python LLM eval & red-team harness: injection, jailbreak, PII-leak suites, pluggable adapters, latency metrics, CI gate
- [gemini-mcp-server](https://github.com/globe-teck/gemini-mcp-server): Tiny Python MCP stdio server for Google Gemini: retries, backoff, model fallback, mocked tests, CI
- [agent-email-safety](https://github.com/globe-teck/agent-email-safety): Sanitized write-up: protecting email-reading AI agents from prompt injection and code-mail leakage
- [agent-inbox-watcher](https://github.com/globe-teck/agent-inbox-watcher): Watch a folder inbox of markdown notes and wake a lead agent via webhook by urgency
- [agent-shell-secret-mask](https://github.com/globe-teck/agent-shell-secret-mask): PATH-first env/printenv wrappers that mask secret values in shared AI-agent shells, with a leak test
- [agent-box-oom-guard](https://github.com/globe-teck/agent-box-oom-guard): Priority-aware OOM guard for shared Linux boxes running multiple AI agents with browsers: swapfile, earlyoom guidance, MemAvailable watch, CDP-aware Chrome oom_score_adj ranking
- [offload-job-runner](https://github.com/globe-teck/offload-job-runner): Offload heavy jobs from memory-tight boxes to GitHub Actions: dispatch, wait, pull artifacts back. Credentials are never echoed.
- [cpanel-spam-filter-sync](https://github.com/globe-teck/cpanel-spam-filter-sync): Sync YAML spam rules into cPanel server-side email filters (UAPI), with dry-run and tests
- [site-checker](https://github.com/globe-teck/site-checker): Passive website checker (HTTP status and speed, TLS expiry, security headers, http-to-https redirect, broken links, optional Lighthouse). Outputs JSON and static before/after HTML reports. No dependencies, CI-tested, no load testing or fuzzing.
- [trust-store-audit](https://github.com/globe-teck/trust-store-audit): Audit Linux/macOS trust stores (system, keychain, certifi, Node, Java) for distrusted root CAs by SHA-256; safe removal with backup and undo.
- [encrypted-backup-rotation](https://github.com/globe-teck/encrypted-backup-rotation): 3-tier encrypted rotation of cPanel-style full backups: host, local, cloud; verify before delete

Website: https://globeteck.com
