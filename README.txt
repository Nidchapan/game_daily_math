DAILY MATH — OFFLINE iPAD HOME SCREEN APP (PWA)

This is an installable web app, NOT a signed native .ipa. No PC needed after it has been installed and cached successfully.

IMPORTANT: A local Wi-Fi HTTP address (http://192.168...) is NOT sufficient to register an offline service worker on iPad Safari. You must first serve this folder from an HTTPS URL.

FASTEST TEST (HTTPS HOSTING):
1. Upload the contents of this folder (index.html, sw.js, manifest.webmanifest, icons) to any static HTTPS hosting provider such as GitHub Pages or Netlify Drop. Do not upload the ZIP as-is unless the service unpacks it.
2. Open the HTTPS URL in Safari on iPad. Wait until the page loads.
3. Share > Add to Home Screen > Add (choose Open as Web App if offered).
4. Open Daily Math from the Home Screen once while online, then test with Wi-Fi disabled.
5. The app should now work without the PC. It will remain installed until removed or its website data is cleared.

NOTES:
- Requires a recent iPadOS with Safari web app support.
- Statistics are currently session-only, and are NOT persisted after closing/reloading.
- App update requires an internet connection to the HTTPS host.
- For a true iPadOS .ipa, use Capacitor + Xcode on a Mac; iOS signing rules apply.
