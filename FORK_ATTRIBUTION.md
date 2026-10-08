# Attribution and fork changes

## Upstream project

This repository is a direct GitHub fork of [`storytold/photocraft`](https://github.com/storytold/photocraft). The fork was created from upstream `main` commit [`ec7302f`](https://github.com/storytold/photocraft/commit/ec7302f) on 2026-10-08 and incorporates upstream improvements through commit [`4526727`](https://github.com/storytold/photocraft/commit/452672765d91acef793bae654e6a29cf10fa5df2). The original project's authors and contributors retain copyright in their contributions.

The inherited source code is available under either the MIT License or Apache License, version 2.0, at the user's option. This fork retains `LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE`, and the third-party asset inventory in `ATTRIBUTION.md`. Third-party assets continue to be governed by their individual notices.

The upstream ArtCraft logo and mark files are not open source. Those image files were removed from this modified fork. The upstream trademark terms remain in `docs/brand/LICENSE-brand.txt` as a notice; this fork makes no use of the marks and is not endorsed by the ArtCraft Team.

## Changes made in this fork

- Added a GitHub Actions workflow that builds the existing Rust/WebAssembly app and publishes the static site to GitHub Pages.
- Added a Russian-language landing page with a clear live-demo link, source-project credit, setup steps, and a concise description of the fork's actual scope.
- Added this attribution record and removed the upstream ArtCraft logo and mark images as required for modified versions.
- Integrated upstream improvements to vector path editing, cross-document layer transfer, Smart Object conversion, image filters, export slices, title-bar controls and related reliability tests. These features remain based on and credited to PhotoCraft; this fork does not claim their original authorship.

The editor engine and its core capabilities are inherited from PhotoCraft. Changes specific to this fork are listed here and in the repository changelog.
