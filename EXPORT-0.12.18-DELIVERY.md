# Email Grabber 3 — scoped export and remaining-results view 0.12.18

Source: EmailGrabber3-Mac-Export-View-Fix-0.12.18.zip
SHA256: 4aed4a8eca0d4756ae81b6c745e8fc34cd5f2683bf43781eaa4954e81cd572e4

Fixes the blank person-filter view after exporting people: successful export clears
category/search filters and shows remaining Included results. Shown and saved counts
are distinguished, with saved-record/Undo access when a view is empty. The quick
person export now respects the current list; Include Uncertain cannot add hidden
rows. Whole-project exports are separately labeled. The save dialog states exact
scope/category counts. Only exported addresses are removed after a successful write;
originals remain stored and Undo restores the last batch. Cancel/failure leaves state
and view unchanged. Exclusions, learning and CSV format remain intact.

305 portable tests passed, including mixed-category and filtered export transactions.
UI syntax, project references, shell syntax, ZIP and internal checksums passed. Native
Mac compilation and GUI execution remain unverified. The explicit model binding fix
is retained. No paid verification or public probes. Quit the older app first; saved
records and learning data are not cleared.
