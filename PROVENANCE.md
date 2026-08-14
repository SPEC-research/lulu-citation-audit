# Provenance

So that neither the delivered audit nor the audited document could be revised against the other during the right-of-reply window, both were fixed by SHA-256 hash in the public repository [SPEC-research/forward-test](https://github.com/SPEC-research/forward-test) (PROVENANCE.md, commit `335ff93`, pushed 2026-08-10, before delivery):

- Audit as delivered, `SPEC-Research-LULU-Citation-Audit-2026-08-10.pdf` (22 pages): SHA-256 `f2370426c19c0f743effdf777a89eaf285f95b5cffa69bee89b133661653fee3`
- Audited document, "The LULU Q4 FY25 Supplier Read-Through" (v2, 41 pages, as distributed by its authors): SHA-256 `473ad669f1c84daabe99dca04c289d2766552f81821d3f040f75c03e4c2ee463`

To verify: hash the PDF in this repository with `shasum -a 256` and compare against the line above and against the forward-test repository's PROVENANCE.md as it stood at commit `335ff93` (visible in that repository's public history). The audited document is not republished here; its hash lets anyone holding the authors' distributed v2 confirm it is the document this audit examined.
