# Support — Azure Signing Tool

## Before requesting help

Confirm that the computer meets these requirements:

- 64-bit supported Windows edition
- Administrator access
- Internet connectivity
- Eligible Azure subscription
- Existing Artifact Signing account
- Completed identity validation
- Active certificate profile
- Artifact Signing Certificate Profile Signer role

The application can prepare missing Microsoft prerequisites, but it cannot create an Azure subscription, perform identity validation, issue a certificate profile, or grant Azure roles.

## Common questions

### Why did Microsoft open two browser sign-ins?

On a first connection, Azure CLI may first identify the Microsoft account and Azure directory, then require a second tenant-specific authentication or MFA checkpoint. Complete every Microsoft prompt that opens. Each `Login successfully` browser tab can be closed immediately.

### Why does the application open without another login later?

The program can retain its private Azure CLI session for the current Windows account. Use **Sign out of this program** to remove the saved authorization. Use **Use another account / directory** to remove both the session and remembered tenant.

### Why did Windows SmartScreen appear?

SmartScreen reputation is separate from file integrity. New or low-volume downloads can be warned about even when their SHA-256 is correct. Download only from the official GitHub release or AI Creations Now host and verify the published SHA-256.

### Why did setup stop?

The program fails closed when a Microsoft prerequisite cannot be downloaded, verified, installed, or rediscovered. Retry after checking the internet connection, Windows Update state, administrator access, and security software logs.

### Where are the backup and report?

The interface shows the exact backup and report locations. The unsigned recovery copy is hash-verified before signing begins, and the final PDF contains recovery information.

## Public issue guidance

A GitHub issue may include:

- application version;
- Windows edition and build;
- failed stage or component;
- sanitized error text;
- installer exit code; and
- steps that reproduce the problem.

Never post:

- passwords or MFA codes;
- Azure access/refresh tokens;
- private tenant secrets;
- confidential filenames or customer data;
- home addresses or government identification; or
- private signing material.

For private support, use the contact information on [AICreateNow.com](https://aicreatenow.com/).
