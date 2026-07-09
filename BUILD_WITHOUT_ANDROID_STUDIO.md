# Build APK Without Android Studio

Use a cloud build so your laptop does not need Android Studio.

## Option 1: GitHub Actions

1. Create a new GitHub repository.
2. Upload everything inside this folder:
   `vista-player-android-starter`
3. Open the repository on GitHub.
4. Go to **Actions**.
5. Select **Build Debug APK**.
6. Click **Run workflow**.
7. When it finishes, open the completed run.
8. Download the artifact named `vista-player-debug-apk`.
9. Extract the ZIP. The APK will be inside it.
10. Send the APK to your phone and install it.

## Phone Install

On Android, you may need to allow:

- Install unknown apps
- File manager/browser install permission

## Notes

- This builds a debug APK for testing.
- Internet is required for GitHub to download Gradle, Android Gradle Plugin, Android SDK packages, and Media3 dependencies.
- Dolby/DTS and other patent-sensitive software decoders are not enabled for distribution by default.
