# Contact-text names 0.12.38 — bundle 59

Archive: EmailGrabber3-Mac-Contact-Text-0.12.38.zip
SHA256: 59d1fdc5e442b9879f554597816fb1eb8448e8bd47719976551f3459db8e4e83

Direct descendant of delivered 0.12.37 commit 1e84d149031ee2f038e4e3ba741d29f3110ebb28. General bounded paragraph/address matching now associates a corroborated exact email with its published full name without requiring heading tags. Honorifics, narrative/mailing-address contact columns and full given-name/surname-initial handles work. Repeated mentions are deduplicated; competing matching names, multiple recipients, hidden names, mismatched links and unsafe bounds abstain. Generic contact labels are not person names. No per-person, site, industry or reference-vocabulary hardcoding was added for the reported examples.

Name-check version 6 allows existing unresolved records to be checked again immediately with Sort this list automatically. Source-first sorting and historical fresh-source leads remain. Manual/exact choices, shared-inbox classification, mismatch export holds, learning/removal state, record IDs and pending crawl work remain preserved. No Clear, full recrawl or learning reset is required.

439 portable XCTest tests passed with zero failures. Core build, Linux syntax parse and Xcode project references passed. A separate private diagnostic runs all three newly supplied complete HTML files through both the matcher and the same sorting coordinator used by the UI: all three named records resolve in three source fetches with IDs preserved. Earlier uploaded-page diagnostics also pass. Uploaded files, identifying data and private diagnostics are excluded from the release; public tests use synthetic records. Native Mac build/GUI and live retrieval remain unverified. Unsupported or ambiguous evidence may still remain Uncertain. Organization-site crawl scheduling remains outstanding.

ZIP integrity, all 101 files and all 100 SHA256SUMS entries verified. Comparison against 0.12.37 contains only expected matcher/test/project/version/docs/log/manifest changes, no removals. Scans found no supplied identifying data or attachment paths in new archive contents. All prior archives preserved.

Mac: Save, Stop and quit the previous app without Clear. Download/verify the ZIP, extract into a fresh directory, run bash build-mac.sh and open dist/EmailGrabber3.app. Confirm 0.12.38 and rerun Sort this list automatically on unresolved records. See CONTACT-TEXT-0.12.38.md inside the source ZIP for validation, limits and acceptance steps.
