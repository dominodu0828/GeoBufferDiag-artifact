# GeoBufferDiag artifact — PVLDB 2027

Public artifact repository accompanying the GeoBufferDiag manuscript.

## Files

- [`submission/GeoBufferDiag_final_20261127.pdf`](submission/GeoBufferDiag_final_20261127.pdf) — manuscript PDF with this repository URL in the availability field.
- [`submission/GeoBufferDiag_source_20261127.zip`](submission/GeoBufferDiag_source_20261127.zip) — LaTeX source and figures for the same PDF.
- [`artifact/GeoBufferDiag-public-release-20261127.zip`](artifact/GeoBufferDiag-public-release-20261127.zip) — clean research artifact package, including benchmark code, frozen coordinate/label inputs, reference outputs, and selected evidence.

The evaluated street-view records are sourced from Baidu Maps; the satellite-derived workloads use So2Sat LCZ42. The authors confirmed that the evaluated derived records and their public release are permitted. The artifact package contains frozen coordinates, labels, and reference outputs; it does not redistribute raw street-view imagery or satellite image patches.

## Integrity

SHA-256 values for the submitted PDF and source archive are listed in [`SHA256SUMS.txt`](SHA256SUMS.txt). The research artifact ZIP has an internal `MANIFEST.json` and detached checksum.

The package excludes private cloud links, machine-specific absolute paths, and the earlier private-review archive.
