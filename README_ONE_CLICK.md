# A.K Journal — One-Click APK Build

This package contains the A.K Journal Android project plus an automatic GitHub Actions
workflow that builds the APK for you.

## No-code method

1. Create/sign in to a GitHub account.
2. Create a new repository (for example: `AK-Journal`).
3. Upload ALL files from this folder to the repository.
4. Open the repository's **Actions** tab.
5. Open **Build A.K Journal APK**.
6. Press **Run workflow**.
7. Wait for the build to finish.
8. Open the completed workflow run.
9. Under **Artifacts**, download **A-K-Journal-APK**.
10. Extract the downloaded artifact and install the `.apk` on your Android phone.

The workflow builds a debug APK automatically. You do not need Android Studio or
Android SDK installed on your phone or computer.

## Important

GitHub Actions is doing the Android build remotely. The APK produced by this workflow
is a debug build intended for personal installation/testing.
