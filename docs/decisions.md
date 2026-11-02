# Decisions

All decisions here are tentative.

## Language: Rust

Tack is written in Rust.

## Storage: one SQLite file, no registry

All data lives in a single SQLite database file. Nothing is written to the registry or to system files.

## First target OS: Windows

Assumption, TBD. Always-on-top and borderless behavior differ per OS, see [platform-notes.md](platform-notes.md).

## UI approach: undecided

Candidates:

- **Tauri (webview):** Markdown, images, GIFs, and Bangla shaping come easily; bigger footprint.
- **Pure-Rust UI (iced or egui):** smaller, but complex-script and RTL text support must be tested first.

First experiment: render a Bangla string and an RTL string in a throwaway window in each candidate before choosing.

## Cut from scope for now

- Network transfer
- Email transfer
- Group Policy
- Public API
