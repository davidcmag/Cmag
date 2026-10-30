# Email Grabber 3 — title classification correction 0.12.9

Source: EmailGrabber3-Mac-Person-Classification-0.12.9.zip
SHA256: b240ff2ff033155764b50a66b453e46030088f7c30fa414ee0806e3c917c8d0b

Fixes Executive Director, Deputy Director and Development Director role inboxes
incorrectly appearing under Person addresses only. Recognizes title inboxes before
name evidence; capitalized job titles/shared-inbox terms are not treated as names.
Actual matching staff names still support person classification. Exact-address
excerpt checks reject longer-domain substring matches. Existing saved rows are
reclassified on display without recrawling, deleting or migrating data. Crawl role
exclusions, verification, removal history/Undo and CSV behavior are unchanged.

252 portable tests passed, including regressions for the reported title inboxes,
unknown titles, title aliases, category review/filtering, genuine staff names beside
titles, and address boundaries. SwiftUI syntax, project references, shell syntax,
ZIP integrity and internal checksums passed. Native macOS compilation, GUI/WebKit
execution and live CPR confirmation remain unverified. No public mailbox probes
or paid verification were run. Quit the older app before building/opening this one.
