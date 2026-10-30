# Email Grabber 3 — address classification 0.12.8

Source: EmailGrabber3-Mac-Person-Classification-0.12.8.zip
SHA256: 9d78bc798b10143d4822e7accedfe34d9bb86a4bb8e8257e2ee32a5c59ffbf40
Extracts into EmailGrabber3-Mac-Audit/; previous archives are preserved.

Adds conservative Likely person / General inbox / Uncertain classifications,
readable reasons (hover Address type or Show evidence), Person addresses only
filtering, sortable classification column, and reviewed category removal using
existing address-based removal and Undo history. Matching recorded publication
excerpts can strengthen classification; mailbox verification remains independent.
Unfamiliar names and initials remain Uncertain without source name evidence.
Existing role exclusion membership, CSV behavior and saved-data schema are retained.
Category removal honors current visible filters and removes all copies of captured
addresses, as existing manual removal does. Filtering alone only hides rows.

248 portable tests passed using signature-verified Swift 6.0.3 on Linux, including
8 new regressions for classification, source excerpts, bulk removal, duplicate
addresses, Undo, persistence, export and sorting. SwiftUI syntax, project references,
shell syntax, ZIP integrity and all internal SHA256 checks passed.
Native Mac compilation, GUI interaction, native WebKit execution and live CPR
confirmation remain unverified. No public mailbox probes or paid verification.
Quit the older app before building/opening this version. Existing saved app data
is not cleared or migrated by the source build; retain backups as usual.
