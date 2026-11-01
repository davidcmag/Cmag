# Crawl waits 0.12.29

Source: EmailGrabber3-Mac-Crawl-Waits-0.12.29.zip
SHA256: db6d38e6cb18312235a15ee5efe800045f2cb9105b0062ac2bdb02672eab5345

Adds bounded, cancellable host waits with separate elapsed status; nonblocking crawl-network cancellation and monotonic download deadlines; and preservation of timed-out page/robots requests for the next explicit resume while other websites continue. Single-worker native crawls share the bounded gate. The Learning menu observes preference changes directly so its checkmarks refresh without waiting for the results pane. Existing saved data, removal-learning preference and all earlier source archives are preserved.

The exact GAO stall is not reproduced or proven fixed. 0.12.28 already had a 15-second caller-side download deadline; investigation found an unbounded host wait before that deadline, a pause-blocking cancellation callback, and discarded timeout pages. These are confirmed code paths, not proof of the user's specific trigger. Live GAO robots access was attempted but the environment proxy denied CONNECT with HTTP 403; no GAO server response was observed and environment settings were not changed.

Original baseline: 360 portable XCTest tests passed. Final build: 368 passed, including eight new regression tests covering slow continuous bytes, paused polling, Stop, elapsed reporting, bounded host delays, canceled leases and timeout/robots preservation and resume with one/five workers. Core build, SwiftUI syntax parse and Xcode project-reference validation passed. All 87 ZIP files verified byte-for-byte against prepared source; ZIP integrity and SHA256 manifest checked. Native Mac compilation, GUI and exact GAO behavior remain unverified. See CRAWL-WAITS-0.12.29.md inside the ZIP for findings and acceptance steps. No private sessions, learned profiles, caches, compiled app, paid verification or public SMTP probes included.
