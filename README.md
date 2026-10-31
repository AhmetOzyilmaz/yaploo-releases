# Yaploo downloads

Official Windows and macOS installers and checksums. Application source remains private.

Website: https://yaploo.vercel.app/#download

## Release status

The new desktop 1.3.0 packages are not published yet. Drafts and unsigned QA builds are not stable downloads. The website enables direct download links only for published stable packages with SHA-256 metadata.

Planned artifacts: Windows x64 Setup and Portable EXE; macOS Apple Silicon and Intel DMG. Each platform must pass its build, signing and smoke checks before publication.

## Verify a download

Compare the SHA-256 digest shown on the release asset and the website with your local file:

- Windows PowerShell: Get-FileHash <installer.exe> -Algorithm SHA256
- macOS: shasum -a 256 <installer.dmg>

Do not disable operating-system security checks for an unsigned or unverified package.

Mobile applications remain distributed through the App Store and Google Play links on the website.
