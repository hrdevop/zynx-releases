# Security Policy

## Supported Versions

Only the latest release of ZynxTerminal receives active security patches.

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |
| < 0.1.0 | :x:                |

## Reporting a Vulnerability

We take the security of ZynxTerminal seriously. If you discover a vulnerability or security risk (e.g. credential leakage, shell escape, or sandbox bypass):

1. **Do not create a public issue.**
2. Send a report with technical details and reproduction steps to: **security@usezynx.com** or open a [GitHub Private Vulnerability Report](https://github.com/hrdevop/zynx-releases/security/advisories/new).
3. We will acknowledge receipt within 48 hours and work with you on a resolution and coordinated disclosure.

## Security Guarantees in ZynxTerminal
- **OS Credential Isolation**: Passwords and SSH keys are stored in the Windows Credential Manager (DPAPI), never in plaintext configuration files.
- **AI Command Safety Guard**: Destructive commands (`rm -rf`, `git push --force`, `dd`, `mkfs`) require explicit typed confirmation before execution.
- **No Silent Telemetry**: ZynxTerminal collects zero telemetry by default and never transmits terminal output to external providers without explicit user consent.
