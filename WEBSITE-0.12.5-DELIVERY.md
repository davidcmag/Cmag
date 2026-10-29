# Email Grabber 3 0.12.5: capture evidence during discovery

Capture exact page-text/mailto publication evidence from the response already
being processed by the crawler, without another HTTP request. Parse publication
matches once per page and retain stronger/newer evidence on later duplicates.
Original Source URLs and duplicate counts stay unchanged. New-row evidence is
live immediately; later duplicate upgrades are checkpointed and visible when
the crawl finishes/stops, preserving the existing append-only display buffer.
Adaptive crawling now recognizes singular /author/ paths.

If a fresh source check misses an address, follow promising same-site contact/
profile links, prefer its last known positive page, and consider common author/
people/staff paths for personal dotted mailbox names. Never guess an address or
accept a name alone: an exact email match is required on the retrieved page.
Keep the original Source and record the actual confirming page URL. Follow-up
is bounded to seven page checks/35 seconds per email and the existing batch
budget, with checked-page audit details in the evidence window and CSV.

234 portable tests pass, including the screenshot-style index-to-author-profile
fixture, discovery evidence without refetch, duplicate evidence upgrades in
adaptive mode, linked profile priority, bounded misses, and prior regressions.
Project references and source/script syntax pass. No paid API/public mailbox
calls were made. Live CPR and actual Mac build/UI remain unverified here.

Full details: WEBSITE-CONFIRMATION.md inside the ZIP. Keep the previous app and
a saved-data backup. Publication does not guarantee mailbox delivery.

Archive SHA256: `895bfb4e1ee3854d9fc7b5520b394775f151493efd9ade1ffee6602fa90c9967`
