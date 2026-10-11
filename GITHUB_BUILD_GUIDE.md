# JARVIS Android Project — GitHub Actions Ready

This version includes `.github/workflows/build-apk.yml`.

## Build on GitHub
1. Create a GitHub repository.
2. Upload all files/folders from this project to the repository root.
3. Open the **Actions** tab.
4. Select **Build JARVIS APK**.
5. If the workflow is available, press **Run workflow**.
6. When it finishes successfully, open the workflow run and download the artifact named **JARVIS-debug-APK**.
7. Extract the downloaded artifact and install `app-debug.apk` on your Android phone.

The workflow uses JDK 17 and Gradle 8.9 and builds the debug APK with `:app:assembleDebug`.
