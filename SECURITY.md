# Security Policy

## Reporting a vulnerability

Please report suspected vulnerabilities privately. Do **not** open a public issue.

- Email: security@supram.ai
- Or use GitHub's private vulnerability reporting on the affected repository
  (Security tab → Report a vulnerability).

Include: affected repository and version, a description, reproduction steps or a proof of
concept, and the potential impact. We will acknowledge receipt and keep you updated on the fix.

## Scope

- The `supram-oss` protocol reference (documents and templates).
- The commercial Supram CLI, Gateway, and Server binaries and services.

## Please do not

- Test against systems you do not own or have permission to test.
- Access, modify, or exfiltrate data that is not yours.
- Disclose a vulnerability publicly before a fix is available.

## Handling secrets

Secrets belong in the platform secret store or GitHub Secrets/Environments, never in the
repository. If you believe a secret has been committed, report it immediately and rotate it.
