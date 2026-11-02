# Email-link mismatches and multi-part names 0.12.36 — bundle 57

Archive: EmailGrabber3-Mac-Link-Mismatches-0.12.36.zip
SHA256: 59d06dacc77275c1e3c5c0ca5a28b3a4f510cdd2235f6f22abbc4f548ec5d26d

Direct descendant of delivered 0.12.35 commit 43e44b30192ec3d6245c35a9eeeea00ae69ebdbc. Displayed-email/mailto disagreement now preserves both addresses as evidence, retains the displayed contact with a warning and holds conflicting destinations from contact rows in ordinary/accepted/person/current-list CSV exports and normal copying until explicit export approval. Classification does not approve a hold. Context-menu approval/revocation is dated and survives stale project/checkpoint snapshots. Exclusions, removals, exact feedback and saved manual choices retain priority. Follow-up checks and request failures cannot silently erase observed conflicts; destinations cannot borrow the displayed person's name. CSV evidence retains warnings/pairs and only exported rows are removed.

Generic contact-card corroboration also supports an earlier component of a multi-part published name, preserving short final surnames. Name-check version 4 enables old unresolved checks to be refreshed. Existing mismatch records require Confirm selected on website; unresolved names use Sort this list automatically. No Clear, learning reset or full recrawl is needed.

423 portable XCTest tests passed with zero failures. Core build, Linux syntax parse and Xcode project-reference validation passed. Private local diagnostics against all three supplied HTML files passed, including the mismatched link and additional multi-part-name card. Uploaded files, actual identifying data and private diagnostic tests/logs are excluded from this release. Native Mac build/GUI and live-site retrieval remain unverified. Continuous crawling and prior general table/card, classification, feedback/removal recovery and frontier regressions pass. Organization-site scheduling remains separate outstanding work.

Verified ZIP integrity, all 97 packaged files and all 96 SHA256SUMS entries. ZIP comparison shows only expected source/tests/UI/project/version/docs/log/manifest changes, no removals, and scans found no supplied identifying data or attachment paths in new content. Previous archives preserved.

Mac: Save, Stop and quit the previous app without Clear. Download/verify the ZIP, extract into a fresh directory, run bash build-mac.sh and open dist/EmailGrabber3.app. See EMAIL-LINK-MISMATCH-0.12.36.md inside for evidence, limits and existing-record instructions. Right-click a held destination to inspect evidence or explicitly approve it for export; approval is not contact/delivery verification.
