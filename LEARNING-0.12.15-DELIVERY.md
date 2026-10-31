# Email Grabber 3 — local learning and source sorting 0.12.15

Source: EmailGrabber3-Mac-Local-Learning-0.12.15.zip
SHA256: 68340db73161e0dbad64cab4f4b8e404583eb17acaa343be3c8db4dcefc17d5c

Adds on-device feedback learning from explicit Person/General corrections and new
removals marked not a person. Exact examples are remembered; broader lexical patterns
need three distinct handles and no Person counterexamples. Domains and predictions
are never lessons. Undo removes its corresponding feedback; local reset is available.
The private local profile persists across projects without sending data to a service.

Adds bounded automatic source-name sorting, with page reuse and same-site follow-ups.
Person association needs a named exact email link or a valid Schema.org Person pair;
loose capitalized excerpts are no longer name proof. Reported county/area accounts
and collective phrases are safeguarded, and ambiguous acronyms remain reviewable.
Progress/counts and Stop are available. No SMTP probes or paid credits are used.

Successful exports remove only exported addresses from current results, suppress
later duplicates and support Undo removal. Cancelled/failed saves do not alter the
list. Export removals never teach negative feedback. CSV/exclusions/verification and
original records remain intact. Optional metadata keeps older saves compatible.

300 portable tests passed, including source, learner, Undo and transactional export
regressions. UI syntax, native project references/resources, shell syntax, ZIP and
internal checksums passed. Native Mac compilation and GUI/WebKit behavior remain
unverified; no live CPR confirmation or public mailbox probes were performed.
Quit the older app before opening this version; original saved data is retained.
