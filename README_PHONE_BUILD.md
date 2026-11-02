# CRYZIX RP — phone-only APK build package

You can use your Android phone to start the build. The APK is compiled on GitHub's cloud runner, not on your phone, so you do not need a computer.

## Build from an Android phone

1. Download and extract this ZIP using your phone's Files app.
2. In Chrome, sign in to GitHub and create a **new public or private repository** named `CryzixRP`.
3. Upload the extracted project contents to the repository. Make sure `.github/workflows/android.yml` is included (GitHub may hide dot-folders in some mobile file pickers; if it does, use GitHub's web editor to create `.github/workflows/android.yml` and paste the workflow content from this package).
4. Open the repository's **Actions** tab. If GitHub asks, enable Actions.
5. Choose **Build CRYZIX RP APK** and tap **Run workflow**. Alternatively, uploading/pushing to the `main` branch starts the workflow.
6. Wait for the workflow to finish with a green check.
7. Open that workflow run, scroll to **Artifacts**, and download `CRYZIX-RP-debug-APK`.
8. Extract the artifact ZIP and install `app-debug.apk`. If Android blocks it, allow your browser or file manager to install unknown apps.

## Important
- This produces a debug/test APK, not a Play Store release.
- Wi-Fi hotspot multiplayer is an early prototype and needs testing/refinement.
- Bluetooth multiplayer is not implemented yet.
- This is currently a simple 2D top-down prototype, not a finished 3D open-world game.
- Keep your GitHub account secure; never share your password or verification codes.
