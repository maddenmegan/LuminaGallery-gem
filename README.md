# Lumina Gallery v4.0 Pro (`com.lumina.gallery`)

AMOLED Black, 100% English Android Gallery engineered in Kotlin + Jetpack Compose + Material 3 for 17,000+ local media files.

## Automated Release APK Build (GitHub Actions)
Push this repository to GitHub (`main` or `master`) or trigger **Actions -> Build Lumina Gallery v4.0 Pro Release APK -> Run workflow**.
The workflow (`.github/workflows/build-apk.yml`) sets up JDK 17 + Gradle 8.11.1, generates or decodes your signing keystore, runs `gradle :app:assembleRelease`, and publishes `LuminaGallery-v4.0-Pro-release.apk` as an artifact.

Optional GitHub Repository Secrets for custom signing:
- `KEYSTORE_BASE64`
- `KEYSTORE_PASSWORD`
- `KEY_ALIAS`
- `KEY_PASSWORD`
