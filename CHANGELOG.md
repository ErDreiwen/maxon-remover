# What's changed

## 0.1.5 — Alpha · 30 October 2026

### Improved
- Revised portable-package instructions.
- Added review/results screenshots and the app logo to the project page.

### Fixed
- Size values sort numerically across KiB, MiB and GiB. The selected sort order persists after a scan.
- Closing Exclusions without changes preserves the current scan and selection.

Build 0.1.5.2 is unsigned. Removal behaviour is unchanged from 0.1.4.

## 0.1.4 — Alpha · 29 October 2026

Initial alpha release. Superseded by 0.1.5.

### Added
- Single-instance enforcement. Subsequent launches activate the existing window.
- Animated progress indicators during scan and removal operations.

### Improved
- Green completion state; amber for failed, partial or incomplete operations.
- Failed and partial removals remain listed with an error message.
- Single-click the selection header to clear all selected rows. Click truncated text to expand its row.
- Reduced selection-control contrast; added application icon and taskbar identity.

Personal folders, renamed backups and Adobe components are excluded from removal.

## Pre-release

Earlier development builds.

### 0.1.3 — 29 October 2026
**Improved:** Increased control inset, reduced fill contrast and adjusted glass shading.

### 0.1.2 — 29 October 2026
**Added**
- Double-click a location in either list to open it in File Explorer.
- Added default exclusions for Music, Pictures, Videos, public folders and OneDrive locations.

**Improved**
- Exclusions window resizes to fit its contents within screen bounds.
- Select-all indicator changes from pale blue to red when all removable items are selected.

### 0.1.1 — 29 October 2026
**Added**
- Click truncated text to expand its row. Expanded rows persist until a click outside the list.
- Double-click the first header cell to select all removable items.

**Improved**
- Long paths wrap across lines; clipboard copies retain the original path.
- Revised interface labels and exclusion descriptions.

### 0.1.0 — 29 October 2026
**Added**
- Installation detection, registered-product uninstallation and selected residual-file cleanup for supported Maxon products.
- Default exclusions for personal folders, renamed backups and Adobe components.
- Local reports, pre-removal scan validation and cancellation between removal items.
