# Riya AI — Android starter project

A simple Android virtual companion chat UI. This starter uses local demo replies and does not yet connect to a real AI model.

## Build APK using GitHub on your phone
1. Extract this ZIP on your phone.
2. Upload the **contents** of this folder to the root of your GitHub repository, preserving all folders (especially `app/` and `.github/workflows/`). Do not upload only the ZIP.
3. Commit the files to the `main` branch.
4. Open the repository's **Actions** tab. Choose **Build Riya AI APK** and tap **Run workflow** if it has not started automatically.
5. When the run completes successfully, open it and download the `Riya-AI-debug-apk` artifact ZIP.
6. Extract that ZIP to get `app-debug.apk`.

## Notes
- GitHub Actions installs Gradle 8.9 and Java 17; a Gradle wrapper JAR is not required for this workflow.
- This is a starter project, not a complete production AI girlfriend app. Replies are local demo responses. Real AI requires a secure backend; never put a private AI API key in the APK or public repository.
