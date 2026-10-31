# Email Grabber 3 — direct person export and group removal 0.12.14

Source: EmailGrabber3-Mac-Quick-Cleanup-0.12.14.zip
SHA256: 7b1fa3b716f7dc8c7f178ac7a98e05c5ebb50283557fc62dcc25c9979f2c1a58

Adds Export person list to the main window, exporting included Likely person results
across the project without requiring individual or group review. Include Uncertain
optionally retains unresolved possible people; this local preference is remembered.
General inboxes, excluded, removed and rejected records are omitted in both modes.
Original records, manual corrections, CSV schema and verification remain unchanged.

Adds Remove group and Undo removal inside Review assistant. Removal honors checked
addresses, exceptions, current eligibility and count confirmation, using the existing
address-based removal history. It creates no broad pattern removal rule. Undo restores
the last removal batch, keeping earlier removals. Existing group classification Undo
and remembered classification rules remain separate.

282 portable tests passed, including 5 new removal/export regressions. UI syntax,
project references, shell syntax, ZIP integrity and internal checksums passed.
Native Mac compilation and GUI/WebKit execution remain unverified. No paid credits
or public mailbox probes. Quit the older app before opening; saved data is retained.
