# corpus-ssa-poms-v3 — SSA POMS per-section mirror (stub-excluded)

Round-3 mirror of the Social Security Administration Program Operations
Manual System (POMS), scraped from secure.ssa.gov public POMS pages
(https://secure.ssa.gov/apps10/poms.nsf/) on 2026-10-04. One file per
POMS section, path <part>/<section-id>.txt, header lines recording the
section title, effective dates, transmittal number and source URL.

v3 excludes the 9,715 title-only stub files (<500 bytes: POMS pages that
render only a section title with no body) carried by v2. On a lexical
(BM25) index a title-only stub whose entire text is the query's terms is
an unbeatable length-norm match, so stubs crowded the real sections out
of every top-5 (G7 round-2 evidence: DI 10105.070 stub beat DI 10105.005B,
which holds the actual 5-month-waiting-period clause). 25,227 content
files remain; no content was edited.

US government work: public domain (17 USC 105). Scraped 2026-10-04;
this mirror is pinned, not living — see the manifest in the XERJ corpus
hub for the exact commit.
