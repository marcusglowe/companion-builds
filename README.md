# companion-builds

Codemagic build configurations for the Anything Companion desktop app.

These workflows build Expo/React Native apps in the cloud. Each build downloads its source from a `PROJECT_SOURCE_URL` — the repo itself only holds the workflow definitions.

## Workflows

- `ios-companion-build` — Expo prebuild → xcodebuild → signed .ipa
- `android-companion-build` — Expo prebuild → Gradle → .apk
