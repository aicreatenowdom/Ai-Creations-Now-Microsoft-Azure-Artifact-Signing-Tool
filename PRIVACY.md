# Privacy and Microsoft Account Security Summary

The complete privacy, installation, and account-security agreement is displayed inside the application before setup begins.

## Information handled locally

The application may process locally:

- selected file path and metadata;
- before/after SHA-256 values;
- unsigned backup location;
- Windows Authenticode status;
- certificate and timestamp information;
- local activity logs; and
- the generated PDF verification report.

The application does not upload the selected executable or its contents to AI Creations Now.

## Microsoft authentication

Microsoft provides the browser authentication and MFA screens. AI Creations Now does not receive or store the Microsoft password or MFA code.

Azure CLI may retain authorization material so the user can resume later. The application keeps its Azure CLI data in a program-owned location associated with the current Windows account. The visible **Sign out of this program** control removes the saved application session. **Use another account / directory** also clears the remembered tenant selection.

Anyone able to operate the same Windows account may be able to use an active saved Azure session. Sign out on shared or untrusted computers.

## Microsoft components

When missing, the application may download, verify, install, repair, or update disclosed Microsoft components, including Azure CLI, .NET, Visual C++, signing tools, Artifact Signing Client Tools, and the Artifact Signing extension. Those components can remain installed after the portable application is closed or deleted.

## Network communication

Network communication is required for:

- Microsoft component downloads;
- Microsoft account authentication and MFA;
- Azure resource discovery;
- Artifact Signing and timestamping; and
- Microsoft service verification.

The current product does not require an AI Creations Now telemetry account or advertising identifier.
