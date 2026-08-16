# Verify the Windows Download

## Expected release

```text
File: AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe
Size: 162,974,672 bytes
SHA-256: F34A2F9AE1D9589E83B865FEF12BD11085E591BA4626D6BF6325A7FA23372499
Product version: 1.0.21.0
Publisher: Dominick Strippoli
```

## PowerShell hash verification

Open PowerShell in the folder containing the download:

```powershell
Get-FileHash .\AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe -Algorithm SHA256
```

The returned hash must exactly equal:

```text
F34A2F9AE1D9589E83B865FEF12BD11085E591BA4626D6BF6325A7FA23372499
```

## Windows Authenticode verification

```powershell
Get-AuthenticodeSignature .\AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe |
    Format-List Status, StatusMessage, SignerCertificate, TimeStamperCertificate
```

You can also right-click the executable, choose **Properties**, open **Digital Signatures**, select the signature, and choose **Details**.

## SignTool verification

When Windows SignTool is installed:

```powershell
signtool verify /pa /all /v .\AI_Creations_Now_Azure_Signing_Tool_v1.0.21_x64.exe
```

Do not run the file when the SHA-256 differs from the published value or Windows reports that the signature is invalid.
