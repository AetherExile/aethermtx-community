# Public content manifest

This file is the authoritative allowlist for the AetherMTX Community Edition distribution repository. The repository is docs/releases-only and must never receive application source or private release material.

## Allowed repository paths

The Git tree may contain only these paths:

```text
README.md
FAQ.md
SUPPORT.md
SECURITY.md
CHANGELOG.md
DISTRIBUTION-NOTICE.md
PUBLIC-CONTENT-MANIFEST.md
assets/aethermtx-mark.png
assets/back-attachment-preview.png
assets/community-gallery.png
assets/community-hero.png
assets/community-hero-ownedcore.png
assets/community-stage.png
assets/skill-effects.png
.github/ISSUE_TEMPLATE/bug.yml
.github/ISSUE_TEMPLATE/config.yml
```

## Approved image assets

| Path | Bytes | SHA-256 | Classification |
| --- | ---: | --- | --- |
| `assets/aethermtx-mark.png` | 948694 | `c607f0dc1f61565609cc263a1dfa4afcfaf2af31fd197ef9f7851dda5a2f51df` | AetherMTX mark |
| `assets/back-attachment-preview.png` | 1069346 | `efe6f128f644df64c7c869c1a423588e0995f7265144bf0acc349b76621b9fd2` | Public Aesir preview inside AetherMTX UI |
| `assets/community-gallery.png` | 582404 | `df6dc7dbaca0f1c8b9428cb71ab57318baa20dcec694852528d0811a8f68319c` | Public AetherMTX 1.1.0 complete look gallery |
| `assets/community-hero.png` | 1614894 | `bf9578eca617a07e7af4ede7108a74cf6bda220a56f506ea7d15cd3834ce0853` | Owner-approved AetherMTX hero |
| `assets/community-hero-ownedcore.png` | 264498 | `23eeb818667a992939e2a2d5da926bdb02a9218513b4ae250cadaf270ba216ba` | Compact AetherMTX hero for OwnedCore |
| `assets/community-stage.png` | 2652189 | `eb2eac08d594bfdc14b5e11878ef6ee26c4f3e9a4545b019f46da55cb8b7535a` | Aether Exile background |
| `assets/skill-effects.png` | 290025 | `47fdda0113581e0f122b7863cb2971aad7740f16a3b3787fe6824b2aac11f04c` | Public AetherMTX 1.1.0 Skill Effects browser |

The product screenshots may show cosmetic imagery only inside substantial AetherMTX application chrome. They contain no raw extracted asset, Character Select view, local path or account data.

## Release assets

Release executables and their checksums are uploaded only after final review and are never committed to the Git tree.

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `AetherMTX-Community-1.1.1.exe` | 177814479 | `2e3ec1055d6b7cc6c05ebe9ab9a9baea87c3b50c031af32463250d98fffd79bf` |

## Review rule

Every proposed commit must be compared against this exact allowlist before it is pushed. Every image must match the recorded byte length and SHA-256. Any other path or changed image requires Owner review.

Owner content review is complete. Initialize and push only the exact allowlisted tree above; all future commits remain subject to the same fail-closed review.
