# Directory names 0.12.34 — bundle 55

Archive: EmailGrabber3-Mac-Directory-Names-0.12.34.zip
SHA256: 0f9e13e73582a8f1f571a3961eb98ceab725c24e3e31dbbee3f2bb853de00b5d

Based directly on delivered 0.12.33 commit 6e86b01a155e33575d8dba99fc851e14287c8867. General table-row inference associates names with email text in separate cells, even when email links point back to a directory instead of mailto. Labeled Name/Email columns support opaque handles; headerless rows require corroborating name-shaped handles. Multiple recipients, conflicting names, mismatched links, hidden/malformed/nested structures and uncertain boundaries abstain. Existing shared-inbox and saved-feedback/correction priorities remain.

The publication/name/browser size limit now matches the crawler's bounded 3 MB limit. New name-check version 2 allows immediate rechecking of old unresolved records through Sort this list automatically. Current checks keep the 24-hour cooldown; manual choices remain respected. No Clear, learning reset or full crawl restart is required. In-place upgrade tests preserve saved record IDs and learning evidence.

404 portable XCTest tests passed with zero failures. Core build, Linux syntax parse and Xcode project-reference validation passed. The complete supplied HTML was tested separately and its reported person/address association and neighboring association now resolve correctly. The uploaded file and private diagnostics are excluded from the archive; public fixtures use synthetic example.org data. Native Mac build/GUI and live retrieval remain unverified. Continuous crawling, general directory traversal, learning, removal recovery and prior tests remain passing. Organization-site scheduling improvement remains outstanding.

Archive integrity, all 93 packaged files and all 92 SHA256SUMS entries verified. Compared with 0.12.33, only expected matcher/check-version/test/project/version/docs/log/manifest changes are present; no files removed and no uploaded identifying data added. Previous archives preserved.

Mac: Save, Stop and quit the previous app without Clear. Download/verify the new ZIP, extract into a fresh directory, run bash build-mac.sh and open dist/EmailGrabber3.app. For existing unresolved results, choose Sort this list automatically to recheck source pages with the new matcher. See DIRECTORY-NAMES-0.12.34.md inside the ZIP for limits and acceptance steps.
