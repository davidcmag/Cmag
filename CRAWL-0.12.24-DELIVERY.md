# Crawl queue recovery 0.12.24

Source: EmailGrabber3-Mac-Crawl-Recovery-0.12.24.zip
SHA256: 0717879f2df07b3477e0298cc1e049287dedbea6e7969bd7cdc1ecff5ee3063d

Prevents contact-crawl expansion into named people-search/gaming traps, deduplicates language/profile-pagination variants, lowers adaptive article/archive priority, and repairs restored frontiers after archiving the legacy checkpoint. Displays first 2,000 queued URLs with full pending count; batches large checkpoint writes with replayable ancestry and forced stop/batch commits. Adds Saving progress activity, separate new/duplicate counts and app version in header.

334 portable tests passed; synthetic 697,513-URL replay retained the original record and byte-identical checkpoint backup, fetched the one useful page and skipped all trap requests. Repair/crawl took 1.15 seconds on Linux (not a Mac/UI benchmark). Native build/GUI remain unverified. Existing saved records, learning, removals and source archives are preserved; no uploaded user data, paid verification or public SMTP probes. See CRAWL-0.12.24.md in the archive for recovery semantics and limitations.
