# Divine Temple Blessing

A mobile web experience that:
- opens the phone camera after the visitor taps Enter Temple
- detects a person bowing using MediaPipe Pose
- rings a temple bell
- speaks a randomized divine blessing
- resets for the next visitor

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `.nojekyll`.
3. Open **Settings → Pages**.
4. Choose the `main` branch and `/ (root)` as the source.
5. Open the generated HTTPS URL on the phone.
6. Allow camera and microphone/audio permissions when prompted.

The page uses HTTPS-hosted MediaPipe libraries, so it is suitable for a secure static host such as GitHub Pages.

## Important
Camera access will not work reliably when the HTML is opened directly as a `content://` local file on Android. Use the HTTPS website URL.
