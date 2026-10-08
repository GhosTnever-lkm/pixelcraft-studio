# Changelog

Notable changes to PixelCraft Studio Community Edition are recorded here.

## 0.4.0 — 2026-10-08

This version improves the browser distribution of the PhotoCraft-based editor. It does not add
new image-editing tools beyond those inherited from the upstream PhotoCraft project.

- Detect the initial web UI language from the browser's ordered language preferences. Use the
  first supported catalog, then fall back to `navigator.language` and English.
- Keep the document's HTML `lang` attribute aligned with the active UI language for assistive
  technology and browser tooling.
- Update the localization guide, Simplified Chinese guide, UI design notes and roadmap to describe
  the web locale behavior accurately.
- Keep the upstream project attribution visible in the repository and the running browser app.

## 0.3.1 — 2026-10-07

- Publish the browser editor through GitHub Pages and correct the WebAssembly size limit used by
  its deployment workflow.
- Document the live editor, fork origin, supported support addresses and current Community/Pro
  status.
