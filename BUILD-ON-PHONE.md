# Build PAATHU RUN APK using only your Android phone

GitHub's cloud computer builds the APK, so you do not need Android Studio or a PC.

1. Extract this ZIP on your phone using Files or an archive app.
2. In Chrome, sign in to GitHub and create a new repository named `paathu-run-android`. For the simplest setup on a free account, make it public. Do not initialize it with a README.
3. Open the empty repository and choose **Add file → Upload files**.
4. Upload all files and folders inside `PAATHU_RUN_Android`, including `.github/workflows/build-apk.yml`. If your phone's picker hides `.github`, enable hidden files or create the workflow file in GitHub's web editor using the included YAML.
5. Commit the files to the `main` branch.
6. Open **Actions** → **Build PAATHU RUN APK** → **Run workflow** → **Run workflow**.
7. Wait for the run to finish successfully. Open the completed run and find **Artifacts**.
8. Download `PAATHU-RUN-APK`, extract that artifact ZIP, and tap `app-debug.apk` to install it. If prompted, allow your browser or Files app to install unknown apps.

This creates a debug APK for personal use/testing, not a Play Store release. The app's WebView storage is separate from Chrome, so your browser test coins are not imported.
