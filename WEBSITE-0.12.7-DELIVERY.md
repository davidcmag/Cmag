# 0.12.7: in-app browser confirmation fallback

The existing Confirm selected on website action now enables a native WebKit
fallback when downloaded HTML does not confirm the exact address or returns an
access challenge. It prefers checked profile URLs, uses fresh isolated browser
storage, bounds requests/time, supports cancellation and preserves original
Source plus separate SMTP/provider results. Only exact page text/mailto matches
confirm publication. Browser blocks/timeouts remain unconfirmed. Evidence marks
browser-rendered page attempts and successful browser confirmation.

The user-saved CPR page matches in the existing parser. An exact contact-anchor
fixture from that page verifies the new direct-miss -> browser-result path,
without claiming the saved page reproduces the app's original HTTP response.

Validation: 240 offline core tests pass; project references, Swift syntax and
shell syntax pass. ZIP CRC and all bundled SHA256SUMS entries pass. Actual macOS
compilation, native WebKit execution and live CPR confirmation are unverified
on this Linux builder. No paid provider or public mailbox checks were run.

Archive: EmailGrabber3-Mac-Browser-Confirmation-0.12.7.zip
SHA256: 39349313ae468558ceee6fa29e62ddc64d2fff9869f9362de84fd9bebae7545a
