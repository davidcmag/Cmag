# SMTP 0.12.3: conservative classification, retries, and readable evidence

Recognize narrow explicit nonexistent-recipient 550/553 text without enhanced
codes, while keeping generic errors, lookup failures and policy blocks uncertain.
Distinguish cooldown-skipped addresses as Deferred/not-probed. Save retry times,
provide Retry inconclusive (SMTP) for due checks, and avoid one-second greylisting
retries. Retain up to eight earlier SMTP attempts and export their evidence.
Right-click an email to Show verification evidence and copy the readable trace.
The sidebar now explains why another active task disables SMTP verification.

186 portable XCTest tests pass (the previous 176 plus 10 robustness regressions).
No public mailbox probes or paid API calls were made. Xcode project references,
source syntax and build script syntax pass. The new Mac evidence window and
actual Mac build/tests remain unverified on this Linux host.

This does not manufacture Valid results for catch-all/gateway acceptance or
claim access to a commercial provider's delivery history. Full behavior and
limitations are in SMTP-CHECKER.md inside the source archive.

0.12.1's canonical TLS status and 0.12.2's Darwin.bind corrections are retained.
New optional fields remain readable from older projects. An older app may not
read new Deferred verdicts; retain a backup before using this development build.

Archive SHA256: `6ba81d2f6d755f9f53dbadce91336fcc3f96310e383d8c9a832161cd387d5d34`
