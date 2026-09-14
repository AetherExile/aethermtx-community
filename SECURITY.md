# Security

## Verify every download

Download AetherMTX Community Edition only from this repository's GitHub Releases page. Compare the file's SHA-256 with both `SHA256SUMS` and the release notes before running it.

The signing status is stated in each release. A valid checksum confirms identity with the reviewed release asset; it does not create a code-signing claim.

Current release:

```text
bb1bb6c3490960d7bc6f1139fce89ad79d3a69a9641be23d24dfd073fd78a9c4  AetherMTX-Community-1.0.10.exe
```

## Supported use

- Windows x64 self-contained application.
- Standalone GGG installation only.
- Close the game and launcher before Apply or Restore Original.
- Use only a release marked compatible with your current game version.

These requirements do not make the application ban-proof or guarantee acceptance under Grinding Gear Games' Terms of Use.

## Reporting a vulnerability

Use GitHub private vulnerability reporting for this repository when available. Include the affected version, public EXE checksum, impact and the smallest safe reproduction.

Do not post working exploits, private user data, game files or unredacted local paths in a public Issue.

This repository does not distribute application source code. A public report does not authorize attempts against other users, services, accounts or infrastructure.

## Release integrity

Official release assets are versioned and are not replaced in place. A corrected binary receives a new version and checksum. Release executables are attached to GitHub Releases and are never committed to the Git tree.

If the GitHub asset, filename, size or checksum differs from the release notes, do not run it and report the discrepancy.

## Scope and limitations

AetherMTX Community Edition is an independent third-party utility. It is not affiliated with or endorsed by Grinding Gear Games. It changes game data and may violate the game's Terms of Use. Use is entirely at your own risk.
