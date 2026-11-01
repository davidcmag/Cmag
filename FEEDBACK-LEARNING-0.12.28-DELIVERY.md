# Feedback learning 0.12.28

Source: EmailGrabber3-Mac-Feedback-Learning-0.12.28.zip
SHA256: e290d1548c93985ea29fb0eea456ee56ed911bd49ace59b01f8fc079462948e7

Expands local feedback learning beyond exact addresses and handle formats: explicit Person/General corrections teach recurring phrases around published addresses. Requires three distinct corrected mailboxes across two domains and at least two matching supported phrases; conflicting feedback abstains, explicit choices win, predictions never train themselves. Learning → Teach useful examples prioritizes conflicts and partly supported/unfamiliar wording, with deduplication and domain diversity. Ordinary removal now hides without asserting General inbox; teaching General on removal is explicit opt-in. Existing learning/removal history and 0.12.27 recovery remain intact.

360 portable tests passed, including nine new feedback/review tests. SwiftUI syntax and project references validated; native Mac build/GUI still unverified. Tests use synthetic fixtures and are not a representative accuracy measurement. No private uploaded session or local learned profile included. Prior source archives preserved. Full details and Mac acceptance steps in FEEDBACK-LEARNING-0.12.28.md inside the source ZIP.
