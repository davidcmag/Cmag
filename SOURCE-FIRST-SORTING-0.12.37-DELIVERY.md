# Source-first sorting 0.12.37 — bundle 58

Archive: EmailGrabber3-Mac-Source-First-Sorting-0.12.37.zip
SHA256: 0d471e7b82d8d7992051b8530941bbe43cfa2a2c069d9ba3ebc6e06be7337f0a

Direct descendant of delivered 0.12.36 commit 118ee62d0bd09d591cac5df8ffe16b2f82b654c6. Automatic sorting now uses a portable source-first coordinator before deeper profile follow-ups. Parsed rendered directories are reused across their addresses; freshly checked same-site name evidence can resolve another record while retaining its original Source. Historical publication URLs are fresh-retrieval leads rather than being discarded or treated as current proof. Browser person sorting waits beyond email-only DOM snapshots and runs readiness inspection off the UI thread.

Optional attempt/completion metadata and name-check version 5 distinguish partial checks from completed checks. Unattempted source groups are prioritized on the next pass; source-only/budget-incomplete attempts do not start a false 24-hour cooldown. Existing page/browser/time limits remain. Summaries report limited/incomplete work explicitly. Manual/exact choices, learning/removal state, mismatch export holds, IDs and the pending crawl queue remain preserved.

431 portable XCTest tests passed with zero failures. New tests run the same coordinator used by the UI, including 50 existing records resolved from one source HTTP fetch and one rendered-page fetch, healthy-source fairness, historical fresh checks, same-site reuse, budget continuation, DOM readiness and Stop. Core build, Linux syntax parse and Xcode project-reference validation passed. Private diagnostics against supplied HTML passed, including the actual full-name page with an excerpt-derived synthetic response for another historical source. This is not a reproduction of the entire live Mac run. Uploaded pages, identifying data and private diagnostics are excluded. Native Mac build/GUI, browser timing and live retrieval remain unverified.

Archive integrity, all 99 files and all 98 SHA256SUMS entries verified. Comparison with 0.12.36 contains only expected coordinator/checker/UI/test/project/version/docs/log/manifest changes; no files removed. Scan found no uploaded identifying data or attachment paths in new archive contents. All old archives preserved. Organization-site crawl scheduling remains outstanding.

Mac: Save, Stop and quit the previous app without Clear. Download/verify the ZIP, extract into a fresh directory, run bash build-mac.sh and open dist/EmailGrabber3.app. Confirm 0.12.37, then rerun Sort this list automatically on unresolved records. No Clear, full recrawl or learning reset is required. See SOURCE-FIRST-SORTING-0.12.37.md inside the ZIP for evidence, limits and Mac acceptance.
