# SMTP candidate 0.12.1: Mac compile correction

Supersedes 0.12.0, whose first actual Mac build failed because Swift does not
import the errSSLServerAuthCompleted C macro alias. The source now uses Apple's
canonical SecBase.h enum constant errSSLPeerAuthCompleted (-9841). Certificate
trust, hostname verification and no-downgrade policy are unchanged.

176 portable tests pass after this correction. Project references and syntax
checks pass. An actual corrected Xcode build, native TLS test and GUI checks
remain unverified; run bash verify-mac.sh on the Mac before using the app.
No public mailbox or paid provider request was made.

Archive: EmailGrabber3-Mac-SMTP-Development-0.12.1.zip

SHA256: `93ceddae35384421b3eda16c044d67cd87a01a1169fe3fbb1b308d820295f4fc`
