# Email Grabber 3 — classification tuning 0.12.11

Source: EmailGrabber3-Mac-Classification-Tuning-0.12.11.zip
SHA256: e9b5584b361268dd6f3fed6c113e71d2bc9ef68c40e1f9121059d39316aded35

Adds Classify selected… and per-address context menu corrections for Likely person,
General inbox and Uncertain. Use automatic classification reverses an override.
Corrections apply by exact address within the current project, survive saving,
reopening, recrawls, live batches and checkpoint merging, and override heuristics.
Classification reason is an explicit column. Improved organization terms and
surname-first names address the supplied examples. Initials require recorded
matching full-name evidence or manual correction. Clear starts a new project;
corrections do not become global rules for unrelated addresses or projects.

261 portable tests passed, including 9 new regressions for these workflows and
compatibility. SwiftUI syntax, project references, shell syntax, ZIP integrity and
internal checksums passed. Native Mac compilation and GUI/WebKit behavior remain
unverified. Verification, removals/Undo, existing crawl exclusions and CSV behavior
are preserved. Older saved projects still decode without migration. No paid
verification or public mailbox probes were run. Quit the older app before opening.
