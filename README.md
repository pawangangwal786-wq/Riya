# Riya AI (Android starter)

A small Android starter app for a virtual companion chat UI. It currently runs in **demo mode** with sample responses; it does not yet connect to a real AI service.

## Build an APK from your phone using GitHub

1. Upload all files/folders from this ZIP to your empty `Riya-AI` GitHub repository, keeping the folder structure.
2. Commit the files to the `main` branch.
3. Open the repository's **Actions** tab.
4. Select **Build Riya AI APK** and tap **Run workflow** (or wait for the push workflow).
5. Open the completed workflow run and download the `Riya-AI-debug-apk` artifact.
6. Extract the downloaded artifact ZIP to get `app-debug.apk`. Android may ask you to allow installing apps from your browser/files app.

## Important
- This is a starter APK project, not a complete production AI companion.
- The chat replies are simple local demo replies. Real AI requires a backend service and an API key stored securely on that backend. Do not put a private AI API key directly into an APK or public GitHub repository.
- Before public release, add privacy disclosures, secure backend integration, testing, and an appropriate app signing/release process.
