# Removal recovery 0.12.27

Source: EmailGrabber3-Mac-Removal-Recovery-0.12.27.zip
SHA256: eff41e3088ef33fa5522a401ec79a1e5572610931b5f64748b7f3b1d73f9e3a9

Protects same-project removal history against older checkpoint/session recovery. Adds an atomic private per-project removal journal with monotonically advancing edit timestamps, including Undo/Restore. Reopening/resuming chooses the newest same-project removal state. Other projects stay independent; existing originals, learning, histories and prior archives remain available. Manual removal immediately refreshes Included. Resume no longer merges unrelated project rows.

351 portable tests passed, including six removal recovery regression tests. UI syntax/project references validated; native Mac build and GUI remain unverified. The stale-checkpoint hazard was found in code; the user's exact reported Mac sequence has not been reproduced. No claim that every possible recurrence is resolved. See the source's REMOVAL-RECOVERY-0.12.27.md for behavior and Mac acceptance steps.
