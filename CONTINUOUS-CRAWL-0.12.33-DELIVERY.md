# Continuous crawl 0.12.33 — bundle 54

Archive: EmailGrabber3-Mac-Continuous-Crawl-0.12.33.zip
SHA256: 67da3d841e2b18abf2abaf44938c7d4eb6a73b67a207542953740fe19df4b8f5

Direct descendant of 0.12.32 delivery a9145015ea62bc8b651affbdaf5bf08bf33974e6. Address/link extraction timeouts now defer the unvisited page and continue healthy queued work. Temporary network/robots/host-wait failures automatically retry with per-page 30/60/120/240/300-second capped backoff. Deferred-only frontiers display a cancellable countdown, not exhaustion or an implicit requirement to Resume. Optional retry metadata survives restart, including directory context and partial rows. Replay avoids duplicate same-source rows even with duplicate stripping disabled. Explicit limits and checkpoint errors retain their meaning; no settings or saved learning/removal/review behavior reset.

393 portable XCTest tests passed, with zero failures. Core build, Linux SwiftUI syntax parse and Xcode project-reference validation passed. Tests cover one/five workers, healthy-page continuation, link timeout retry, partial rows, DNS interruption/restart, retry backoff/cap, Stop/Pause, selected limits, robots recovery and prior regression suites. Native Mac build/GUI and live directory behavior remain unverified. Synthetic timeout fixtures do not reproduce the exact reported live page. Organization-website scheduling improvement remains outstanding.

Archive integrity passed; all 91 files matched prepared source and all 90 SHA256SUMS entries verified. ZIP comparison with 0.12.32 showed only expected source/tests/version/docs/log/manifest changes, one added acceptance document, no removed files or private sessions/profiles. Old source archives preserved.

Mac: Save, Stop and quit the previous app without Clear. Download and verify this ZIP, extract into a fresh directory, then run bash build-mac.sh and open dist/EmailGrabber3.app. See CONTINUOUS-CRAWL-0.12.33.md inside the source archive for behavior, tests and acceptance checks.
