# Changelog

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
