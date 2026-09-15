# Changelog

## 1.0.11

Release status: published on GitHub Releases.

### Added

- Full Steam client support with the same 52 Official Looks and 279 optional Back Attachments.
- Automatic detection and manual selection for either supported game distribution.

### Improved

- Shared preview and Apply pipeline across GGG standalone and Steam.
- Independent recovery state for each installation and exact supported game build.
- Apply and Restore performance validated separately on both data layouts.

### Safety

- The same protected Community Edition binary serves both supported clients.
- Game files remain unchanged when the selected executable or index is not an exact supported build.
- GGG and Steam recovery copies cannot overwrite or replace each other.

## 1.0.10

Release status: published on GitHub Releases.

### Added

- 52 Official Looks backed by 43 complete armour cores.
- 279 optional Back Attachments in the Apply flow.
- Search, Clear and local preview support.
- Direct Restore Original workflow.

### Improved

- Apply and Restore performance on large standalone GGG installations.
- Clearer preview loading feedback.
- Clearer GGG-only and Steam unsupported guidance.
- Clearer unsigned-build and use-risk disclosures.

### Safety

- Game and launcher must be closed before any file change.
- Game and launcher must be closed before Apply or Restore Original.
- Users should run only a release marked compatible with their current game version.
