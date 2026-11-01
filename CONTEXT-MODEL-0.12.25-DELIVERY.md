# Local context model preview 0.12.25

Source: EmailGrabber3-Mac-Context-Model-Preview-0.12.25.zip
SHA256: fbcb58903b23c0e647ab269a7202cc9c5f60df0ea25d23f052f7040bd0b3edf7

Actual trained logistic-regression starter using address fragments and saved surrounding text, with local Swift inference and no Python/app network dependency. Opt-in via Learning -> Use trained context model (preview); off by default because evidence is preliminary. Only unresolved addresses with valid published context are eligible; corrections and learned decisions win. Retains visible context for link-only observations without inventing recipients. Includes reproducible synthetic corpus, trainer and exported model; no user project/context/feedback is uploaded or used in training.

341 portable tests passed, with feature parity, held-out samples, guards, rollback, no self-training and link-context capture. Synthetic test: 1 correct/7 abstentions/0 wrong out of 8; separate assistant-reviewed convenience pilot: combined classifier 10 correct/6 Uncertain versus baseline 5 correct/11 Uncertain, no introduced wrong labels. These small biased evaluations do not establish representative accuracy, so this is a preview, not a broadly validated replacement or a full language model. Model weights do not automatically retrain from corrections; existing local feedback learning remains active. Native Mac build/GUI unverified here. Prior archives, records, learning and removals are preserved.
