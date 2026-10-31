# Email Grabber 3 — Mac learning-toggle compile fix 0.12.16

Source: EmailGrabber3-Mac-Binding-Fix-0.12.16.zip
SHA256: bbb3a20a63c54d3c20bc7e9de58896a32f0b56ed0d3a6b1331396df86788f774

Fixes the user-reported Mac compile error: cannot find '$model' in scope at the
learning toggle. ResultsPane uses a plain model reference, so the toggle now has
an explicit Binding(get:set:). The other projected bindings belong to ContentView's
ObservedObject. The reported build never reached application launch. Nonfatal
concurrency/deprecation warnings are separate and are not silenced with unsafe
annotations. All 0.12.15 features and saved-data/learning formats are retained.

300 portable tests passed, plus SwiftUI syntax, project-reference and shell checks.
Source audit confirms no projected model binding remains in ResultsPane. Archive
integrity and internal checksums passed. Full native Mac compilation and launch
of this correction remain unverified in Linux. Quit the older app before building.
No saved data is cleared; no paid verification or public mailbox probes were run.
