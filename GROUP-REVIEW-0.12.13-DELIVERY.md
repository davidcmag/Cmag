# Email Grabber 3 — grouped review and export fix 0.12.13

Source: EmailGrabber3-Mac-Group-Review-0.12.13.zip
SHA256: 1517843dd22bbdaa171647f6307e64609b18a80fc191264c437bbf1e37955706

Adds Review assistant… for unresolved included addresses in the current list.
Groups show samples and counts, with full inspection and unchecked exceptions.
Confirmed group decisions mark Person, General inbox or Uncertain without deletion.
Optional remembered pattern rules apply to new matching addresses in this project,
respecting exceptions and individual corrections. Undo group decision reverses the
batch and its remembered rule, including later matches, preserving later manual
edits. Session/checkpoint metadata preserves rules and Undo history; older projects
remain compatible. Undo is available from the main window and assistant.

Fixes Export all ignoring current filters and letting crawler Excluded rows through.
Export CSV… has explicit Current list / All included (all address types) / All accepted
scopes. Every scope omits excluded statuses, rule exclusions and removed addresses;
Current list preserves filters and ordering. CSV schema/evidence are unchanged.

277 portable tests passed, including 13 new group/export regressions and the existing
139-case classifier evaluation. UI syntax, project references/resources, shell syntax,
ZIP integrity and internal checksums passed. Native Mac compilation and GUI/WebKit
execution remain unverified. No paid credits or public mailbox probes were used.
Quit the older app before opening this version; source build does not clear saved data.
