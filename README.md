# CH32V003 RISC-V Exploration site

This directory is a dependency-free static site for GitHub Pages.

## Publish

Either make this directory the root of a dedicated GitHub Pages repository, or configure the repository's Pages source to deploy this folder through the chosen GitHub Actions workflow. The entry page is `index.html`; its two content pages are:

- `picorvd-port.html` — porting findings
- `benchmark.html` — benchmark record and limitations

All links and assets are relative, so the site works from a project page or custom domain without a configured base URL.

## Evidence boundary

The documentation compares `picorvd` with `old-unmodified-code/picorvd-master` and `coremark-main` with `old-unmodified-code/coremark-main`, normalizing line endings and omitting generated build output. CoreMark upstream source files had no content differences. The target-specific CoreMark layer is at `picorvd/example/coremark_port`.
