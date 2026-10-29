# Email Grabber 3: optional SMTP checker development candidate

Source: EmailGrabber3-Mac-SMTP-Development-0.12.0.zip

Reconstructed from the failed-workspace design handoff on 0.11.13. The previous
ZIPs remain unchanged. This is a testable source candidate, not a Mac release.

176 portable XCTest tests pass, including scripted SMTP/DNS, real local socket
I/O and cancellation, conservative verdicts, evidence persistence, CSV exports
and the original 128 regressions. No public mailboxes or paid API were contacted.

macOS compilation, native certificate-rejection test and GUI checks remain
unrun. On your Mac extract this ZIP, read SMTP-CHECKER.md, and run:

```sh
bash verify-mac.sh
open EmailGrabber3.xcodeproj
```

Press Command-R only after the Xcode tests pass. The script backs up existing
application data first. Keep your earlier app and source until acceptance passes.

New source files: MailboxVerification.swift, MailRouting.swift,
SMTPSocketWire.swift, DisposableDomainData.swift. SMTP uses target-first RCPT
checks plus two random controls, verified TLS by default, no DATA/VRFY/EXPN/AUTH,
and public numeric destinations on port 25. Separate SMTP and ZeroBounce records
and CSV columns preserve comparison evidence; provider calls still require your
explicit in-app confirmation and can consume credits.

Archive SHA256: `1abf041b16e83775752a8185edbafdf1947d5773ea8be58a9171b8e90ff743d8`
