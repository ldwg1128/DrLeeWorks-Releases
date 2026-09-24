# DrLeeWorks-Releases
Official software releases from [DrLeeWorks](https://drleeworks.com)

This repository is used only for distributing compiled software packages.
Source code is maintained separately.

## Software

- Shorts Player
- LCapture
- LBox
- More software will be added

Please use the **Releases** section to download the latest versions.

## Download & Security

Official builds are distributed through the **Releases** section of this repository.

Executables are code-signed by **DrLeeWorks** using a self-signed certificate. Because the certificate is self-signed, Windows may display a security or SmartScreen warning when running the software. If the file was downloaded from this official repository and its integrity has been verified, you may choose to run it manually.

The self-signed signature provides a basic means of detecting modification, but it does not provide the same identity verification as a certificate issued by a publicly trusted certificate authority.

For security, downloading DrLeeWorks software from unofficial mirrors or third-party websites is not recommended. Files obtained from other sources may have been modified or repackaged.

### Verify File Integrity

Each release provides the **SHA-256 hash** of the distributed ZIP file.

After downloading, open PowerShell in the folder containing the ZIP file and run:

```powershell
Get-FileHash ".\filename.zip" -Algorithm SHA256
