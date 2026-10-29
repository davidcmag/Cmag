# Email Grabber 3 0.12.4: fresh website confirmation

Select an email, then Confirm selected on website. Or right-click a row and
choose Confirm on website. The sidebar's Confirm next 100 on website processes
unchecked rows. Website-only checks require no EHLO, sender identity or API key.
SMTP actions now also revisit saved source pages. Results are separate in the
Website column: Published by organization, Published on source, Not found on
page, Page unavailable, No website source, or Cancelled.

Fresh requests check exact static page text/mailto recipient links and record
source/final URL, fetch date, HTTP status, match method and excerpt. Rechecks do
not reuse a previous batch's cache. Up to three historical website findings are
retained. Current unavailable results do not masquerade as fresh confirmation.
Exclusions, removals, SMTP/provider evidence and acceptance status are preserved.
Website evidence/history appear in Show verification evidence and CSV exports.

221 portable XCTest tests pass: the previous 186 plus 35 website regressions,
including native HTTP streaming fixture integration, cancellation, negative
matches, query reflection, cookie/cache policy, redirects, error responses,
history, compatibility and exports. Xcode source/test membership, project
references and source/script syntax were checked. No public mailboxes or paid
API were contacted. Actual Mac build/UI and live CPR page behavior remain
unverified; this environment cannot access CPR. This is a development source
candidate. Publication on a page is not a mailbox-delivery guarantee.

Full instructions/limits: WEBSITE-CONFIRMATION.md inside the ZIP.
Keep a saved-data backup and the previous app before trying this candidate.

Archive SHA256: `d8752940f3b90f994fee1cb351a3b878faa202f5bcb525d4b072e6035b0790bd`
