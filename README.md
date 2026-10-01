# RISC-V Independent Study site

This is a dependency-free static site for GitHub Pages.

## Pages

- `index.html` - concise independent-study overview
- `research.html` - CoreMark and instruction-path measurements for Pico 2 RISC-V and CH32V003

All assets and links are relative, so the site can be published from a dedicated Pages repository, a project Pages path, or a custom domain.

## Evidence boundary

The technical record compares `picorvd` with `old-unmodified-code/picorvd-master`, and `coremark-main` with `old-unmodified-code/coremark-main`, normalizing line endings and omitting generated output. The CoreMark workload source files had no content differences. The CH32V003-specific CoreMark layer is located in `picorvd/example/coremark_port`.

The instruction-path section is based on the supplied `ch32v003-performance-test-*.md` and `rp2350-performance-test-*.md` evidence notes. It intentionally keeps timer-derived CH32V003 core periods separate from the Pico 2's captured `mcycle`/`minstret` measurements, and it does not present either group as a universal MIPS score.
