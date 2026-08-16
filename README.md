<p align="center">
  <img src="https://aicreatenow.com/images/azuretool-page-hero.jpg" alt="AI Creations Now Microsoft Azure Artifact Signing Tool" width="100%">
</p>

<p align="center">
  <a href="https://aicreatenow.com/azuretool.html"><img alt="Official product page" src="https://img.shields.io/badge/Official-Product%20Page-0B64C0?style=for-the-badge"></a>
  <a href="https://github.com/aicreatenowdom/Ai-Creations-Now-Microsoft-Azure-Artifact-Signing-Tool/releases/latest"><img alt="Latest release" src="https://img.shields.io/badge/Download-v1.0.21-0078D4?style=for-the-badge&logo=windows11&logoColor=white"></a>
  <a href="https://buy.stripe.com/6oUeVf77ZdRCfMEbka5kk04"><img alt="Optional donation" src="https://img.shields.io/badge/Optional%20Donation-$3%2B-635BFF?style=for-the-badge&logo=stripe&logoColor=white"></a>
</p>

<p align="center">
  <strong>A complete Microsoft Azure Artifact Signing workflow in one guided Windows GUI.</strong><br>
  Prepare · Connect · Select · Protect · Sign · Verify
</p>

---

## What it does

AI Creations Now Azure Signing Tool is a free portable Windows x64 application for developers and organizations that already have a Microsoft Azure Artifact Signing environment.

It streamlines the repetitive parts of a legitimate signing workflow:

- Checks supported 64-bit Windows and the required Microsoft components
- Reuses valid installed components and prepares missing prerequisites
- Opens Microsoft's normal browser authentication flow
- Discovers the subscriptions, Artifact Signing accounts, certificate profiles, and endpoint available to the connected identity
- Lets the user select a local Windows executable
- Creates and verifies an unsigned recovery backup before signing
- Applies Microsoft Azure Artifact Signing and a Microsoft timestamp
- Verifies the resulting Windows Authenticode signature
- Calculates pre-sign and post-sign SHA-256 values
- Creates a detailed local three-page PDF verification report

This application does **not** create an Azure subscription, complete Microsoft identity validation, issue a certificate, or assign Azure roles. The customer must already be authorized to use the selected Artifact Signing resources.

## Guided workflow

<p align="center">
  <img src="https://aicreatenow.com/images/azuretool-privacy.jpg" alt="Privacy and installation agreement" width="48%">
  <img src="https://aicreatenow.com/images/azuretool-readiness.jpg" alt="System readiness and prerequisite preparation" width="48%">
</p>

1. **Review the privacy and installation agreement.** Nothing is checked, installed, authenticated, selected, or signed until the local agreement is accepted.
2. **Prepare the computer.** The application checks Windows, Azure CLI, .NET, Visual C++, Microsoft signing tools, Artifact Signing Client Tools, and the Azure CLI Artifact Signing extension.
3. **Connect through Microsoft.** The first connection may use two browser checkpoints—one to identify the account/directory and another for tenant-specific authentication or MFA.
4. **Choose existing Azure resources.** Select the subscription, Artifact Signing account, active certificate profile, and endpoint Microsoft reports for the connected identity.
5. **Choose the executable.** Use the normal Windows file picker and review the backup and hash-protection plan.
6. **Sign and verify.** The activity log follows backup verification, Artifact Signing, timestamping, Authenticode validation, and report creation.
7. **Keep the PDF evidence.** The report records file details, hashes, publisher information, certificate data, timestamp, backup location, and recovery information.

<p align="center">
  <img src="https://aicreatenow.com/images/azuretool-resources.jpg" alt="Azure resource selection" width="62%">
</p>

## Microsoft account security

Microsoft handles the password and MFA pages. The application never asks for or stores the Microsoft password or MFA code.

By default, the application can keep its private Azure CLI authorization for the current Windows account so future launches normally return directly to the signing-resource page. The interface includes visible controls to:

- **Sign out of this program** — removes the application-owned cached authorization
- **Use another account / directory** — removes the cached authorization and remembered tenant information

On shared, public, or temporary computers, sign out before leaving. The saved session is a convenience feature, not a substitute for protecting the Windows account.

## Local privacy model

- The selected executable is not uploaded to AI Creations Now
- The unsigned backup, hashes, signed file, and PDF report remain on the local computer
- The application contains no AI Creations Now telemetry or analytics account
- Microsoft receives the authentication and signing-service communications required to provide Azure Artifact Signing
- Microsoft prerequisite packages can remain installed after the portable application is removed

See [PRIVACY.md](./PRIVACY.md) for the repository summary. The in-application agreement controls the actual first-run disclosure.

## System requirements

- Windows 10 or Windows 11 x64, or Windows Server 2016 or later with Desktop Experience
- Local administrator access for prerequisite preparation
- Internet access
- Eligible paid Microsoft Azure subscription
- Existing Microsoft Azure Artifact Signing account
- Active certificate profile
- Permission to sign with the chosen certificate profile

## Download and verification

**Release:** 1.0.21  
**File:** `AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe`  
**Size:** 162,974,672 bytes  
**SHA-256:**

```text
F34A2F9AE1D9589E83B865FEF12BD11085E591BA4626D6BF6325A7FA23372499
```

The release is a Microsoft Artifact Signing Authenticode-signed and timestamped Windows executable. Windows SmartScreen reputation may vary. Always compare the SHA-256 value and inspect the signature before running it.

[Verification instructions](./VERIFY_DOWNLOAD.md) · [Release notes](./RELEASE_NOTES.md) · [Latest GitHub release](https://github.com/aicreatenowdom/Ai-Creations-Now-Microsoft-Azure-Artifact-Signing-Tool/releases/latest)

## Source-code policy

This repository does not publish the proprietary application source code. The public repository contains product documentation, screenshots, release notes, privacy/security information, and the official compiled release asset only.

GitHub automatically presents “Source code” ZIP/TAR links for every release. Those auto-generated archives contain only this public documentation repository—not the proprietary Azure Signing Tool source.

## Support

See [SUPPORT.md](./SUPPORT.md). Security-sensitive matters must be reported privately under [SECURITY.md](./SECURITY.md).

---

**AI Creations Now Software Development**  
[Company website](https://aicreatenow.com/) · [Services](https://aicreatenow.com/services.html) · [Support](https://aicreatenow.com/faq.html) · **1-866-315-4750**

© 2026 AI Creations Now Software Development. All rights reserved. Microsoft, Windows, Azure, and other product names are trademarks of their respective owners. Their mention does not imply affiliation or endorsement.
