# Security Policy

## Supported release

The current public release is **1.0.21** for Windows x64.

## Verify every download

Expected SHA-256 for `AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe`:

```text
F34A2F9AE1D9589E83B865FEF12BD11085E591BA4626D6BF6325A7FA23372499
```

Use PowerShell:

```powershell
Get-FileHash ".\AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe" -Algorithm SHA256
```

Treat the file as official only when it comes from this repository's release assets or the official AI Creations Now download host.

## Reporting a vulnerability

Do not publish exploitable security details, credentials, access tokens, tenant secrets, or confidential customer information in a public issue.

Report security-sensitive matters privately to:

**info@aicreatenow.com**

Include the application version, Windows version, affected workflow stage, reproduction steps, and the SHA-256 of the file tested. Do not attach credentials or customer files.

## Security boundaries

- Microsoft handles password and MFA entry.
- The application never needs the user's Microsoft password or MFA code.
- A saved Azure session is sensitive and should be removed on shared systems.
- The application verifies downloaded prerequisite signatures and fails closed when preparation cannot be validated.
- The selected executable is not uploaded to AI Creations Now.
- Proprietary source code and signing secrets are not published in this repository.
