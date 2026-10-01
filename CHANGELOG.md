# Changelog

## v1.1.0 — 2026-10-01

- New question bank from the latest web version: 60 questions, 20 each for
  Beginner, Intermediate, and Expert, plus an All Levels round (easy to hard).
- Shuffled answer order, myth busters for common credit myths, and a
  question-by-question review at the end of each round.
- Real app look: black launch screen with the big logo (no white box on
  Android 12+), new launcher icon sized for round, squircle, and square
  shapes, solid app bar, and About / Privacy / Credits panels.
- Android back button asks before quitting a round, returns to the level
  picker from results, and asks before exiting.
- Removed the social, fundraising, and "Play another game" links from the new
  web version; a content security policy blocks all network access.
- The `INTERNET` permission that Capacitor merges in is now stripped from the
  final manifest.
- Signed with a new key. Uninstall v1.0.0 before installing v1.1.0.
- Added GitHub Actions debug builds and a signed release workflow with
  `tools/validate-release.sh`.

## v1.0.0

- Initial GitHub-ready Android APK release.
- Added offline 50-question credit education quiz.
- Added randomized question rounds (10 questions per round).
- Added instant feedback, explanations, and credit tips.
- Added score tracking and final mastery rating.
- Added black-and-gold WGRALGO design language.
- Removed website navigation, social media, and fundraising bars from the
  APK interface.
- Removed the `INTERNET` permission &mdash; the app is fully offline.
- Replaced placeholder icon and splash with the official Credit Mastery
  Challenge logo (full-bleed adaptive icon on black; no white border).
- Bumped package to `org.wgralgo.creditmasterychallenge`,
  `versionName` `1.0.0`, `versionCode` `100`.
- Wired release signing config, ProGuard / R8 minification, and resource
  shrinking in `android/app/build.gradle`.
- Added GPLv3 LICENSE, PRIVACY.md, CONTRIBUTORS.md, and README.
