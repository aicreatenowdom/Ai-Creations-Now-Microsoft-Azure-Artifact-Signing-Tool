# Privacy and Local Data Summary

## Before setup begins

The application presents a local Privacy, Installation & Microsoft Account Security Agreement before system inspection, prerequisite installation, Microsoft sign-in, file selection, or signing begins.

## Microsoft authentication

Microsoft handles password and MFA pages. AI Creations Now Azure Signing Tool does not ask for or store the Microsoft password or MFA code.

The application may retain a protected Azure CLI authorization cache for the current Windows account so future launches can continue without repeating browser authentication. The user can remove it through the visible **Sign out of this program** control. A separate account/directory option removes both the authorization and remembered tenant information.

## Local files

The application reads only the local executable explicitly selected by the user for that signing workflow. It creates a local unsigned backup, calculates hashes, performs signing through Microsoft, verifies the signed result, and generates a local PDF report.

AI Creations Now does not receive the selected executable, its contents, the local backup, or the generated PDF report.

## Microsoft components

The application can detect, install, repair, or update required Microsoft components, including Azure CLI, .NET, Visual C++, Artifact Signing Client Tools, signing tools, and the Azure CLI Artifact Signing extension. These components can remain installed after the portable application is deleted.

## Network communication

Internet communication is required for Microsoft package retrieval, Microsoft authentication, Azure resource discovery, Artifact Signing, and timestamping. The application does not require an AI Creations Now telemetry account.

## Shared computers

A saved authorization can be used by someone who can operate the same Windows account. Sign out before leaving a shared, public, temporary, or otherwise untrusted computer.

The complete in-application agreement and current official website privacy information control where they provide more detail.
