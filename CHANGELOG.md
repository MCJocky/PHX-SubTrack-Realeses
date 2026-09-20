# Changelog

## 0.9.5 Beta

### Update system and onboarding

- Added a daily background check for new GitHub releases.
- Added a manual update check in Settings.
- Added an update notice with a direct link to the published APK.
- Updated the tutorial for first-time installations.
- Kept the tutorial available from Settings at any time.

### Categories

- Added category visibility controls while ensuring at least one category remains visible.
- Added custom categories with a name, color, symbol, and configurable order.
- Added editing and sorting for custom categories.
- Added safe deletion with reassignment when a custom category contains subscriptions.
- Kept hidden category data intact and restored it when the category becomes visible again.
- Migrated existing subscriptions to stable internal category IDs without losing data.

### Subscription overview

- Added partial-name search with trimmed, case-insensitive matching.
- Kept category filters and sorting active while searching.
- Added a clearer empty-search message and a conditional clear button.
- Hid the upcoming billing summary while a search is active.
- Made subscription cards more compact.
- Removed the redundant monthly average from monthly subscriptions.
- Kept monthly averages for quarterly, half-yearly, and yearly subscriptions.
- Refined the compact next-billing presentation.

### Interface

- Renamed the upcoming billing information to **Next due**.
- Made the next-due element flatter and visually distinct from interactive subscription cards.
- Applied the updated presentation consistently across supported themes and languages.

### Validation

- Verified migration from existing data and behavior on a new installation.
- Verified category visibility, editing, deletion, reassignment, language changes, and theme changes.
- Verified lists, totals, charts, search, budget calculations, and next-due information.
- Verified the full updater path from an installed 0.9.4 build to the published 0.9.5 APK.

