# Email Grabber 3 — pattern classification 0.12.12

Source: EmailGrabber3-Mac-Pattern-Classification-0.12.12.zip
SHA256: 81d962773d9913b0800d501e59475125218f8be7d15d7bd60d4c23ed934ebec7

Replaces the small name whitelist gate with independent structural/name signals.
Separated names (either order, including middle initials) do not require dictionary
membership. Joined names and single-name handles use a bundled Census-derived
vocabulary as supporting evidence. Full-name patterns allow short numeric suffixes.
Explicit role/organization signals take priority over spelling patterns; manual
corrections still win. Ambiguous initials and unsupported handles remain Uncertain.
Reasons distinguish inference from verified identity. Existing rows reclassify on
display without recrawl, deletion or migration. Verification, CSV, original crawl
role exclusions, saved evidence and removal/Undo behavior are retained.

264 portable tests passed, including a 139-case mixed expected-routing evaluation
(45 likely-person, 63 general, 31 uncertain). Curated examples are not an accuracy
claim for the user's full dataset. UI syntax, native project resource references,
shell syntax, ZIP integrity and internal checksums passed. Data license/provenance
and upstream hashes are bundled. Native Mac compilation, GUI/WebKit execution and
live CPR confirmation remain unverified. No public mailbox probes or paid credits.
Quit the older app before opening this version.
