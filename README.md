# RISC-V Independent Study site

This is a dependency-free static site for GitHub Pages.

## Pages

- `index.html` - concise independent-study overview
- `research.html` - combined PicoRVD porting record and CH32V003 benchmark results

All assets and links are relative, so the site can be published from a dedicated Pages repository, a project Pages path, or a custom domain.

## Evidence boundary

The technical record compares `picorvd` with `old-unmodified-code/picorvd-master`, and `coremark-main` with `old-unmodified-code/coremark-main`, normalizing line endings and omitting generated output. The CoreMark workload source files had no content differences. The CH32V003-specific CoreMark layer is located in `picorvd/example/coremark_port`.
