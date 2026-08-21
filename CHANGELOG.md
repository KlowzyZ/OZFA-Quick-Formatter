# Changelog

All preserved public releases of OZFA Quick Formatter are listed here. Downloadable executables and their SHA-256 checksum files are available from [GitHub Releases](https://github.com/KlowzyZ/OZFA-Quick-Formatter/releases).

## [3.0.1] - 2026-08-20

- Added a new high-resolution application icon designed for OZFA Quick Formatter.
- Embedded multi-size Windows icon resources for clear display in Explorer, the taskbar, and the title bar.
- Kept disk formatting behavior and safety protections unchanged from v3.0.0.
- Published as an update-test release for the built-in GitHub update checker.

## [3.0.0] - 2026-08-20

- Rebuilt the application as a native C# WinForms portable EXE.
- Removed the PowerShell window and launcher files.
- Added an embedded application icon and automatic Administrator request.
- Preserved automatic disk arrival and removal detection.
- Strengthened Windows, boot, system, and application disk protection.
- Added a second live disk identity and safety check immediately before formatting.
- Added strict post-format verification for GPT, one partition, NTFS, `Yeni Birim`, and the assigned drive letter.
- Preserved settings, completion sound, operation logs, About, and GitHub update checks.
- Added SHA-256 verification for downloaded release files.

[3.0.1]: https://github.com/KlowzyZ/OZFA-Quick-Formatter/releases/tag/v3.0.1
[3.0.0]: https://github.com/KlowzyZ/OZFA-Quick-Formatter/releases/tag/v3.0.0
