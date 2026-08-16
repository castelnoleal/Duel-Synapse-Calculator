# Duel Synapse Calculator — Android APK

This is an offline Android WebView app built from the original Duel Synapse V1.0 HTML.

## GitHub phone build

Upload the **contents of this folder** to the root of your GitHub repository. Make sure `.github/workflows/build-apk.yml` is present.

Then open **Actions → Build Duel Synapse Calculator APK → Run workflow**.

When the run finishes, open it and download the artifact **Duel-Synapse-Calculator-APK**. The artifact contains `Duel Synapse Calculator.apk`.

The app bundles `app/src/main/assets/index.html`, so the Duel Synapse interface itself does not require an internet connection.
