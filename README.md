# On-Call Log — installable app package (PWA)

Host these files on any HTTPS static host (GitHub Pages, Netlify Drop, Vercel), then:
- iPhone: open the URL in Safari -> Share -> Add to Home Screen
- Android: open in Chrome -> menu -> Install app
- Mac: Safari -> File -> Add to Dock, or Chrome -> Install page as app

Data is stored encrypted on that one device/browser only (no sync). Use the export icon for backups.
When you first set a passcode the app shows a one-time recovery code. If you forget your passcode, tap "Forgot passcode?" on the lock screen, enter the code and choose a new passcode; your logged calls are kept. Store the code somewhere safe: anyone with the code and the device can open the log, and if both passcode and code are lost the data cannot be recovered. Existing users are shown a new recovery code the first time they unlock after updating.
Not an App Store / Play Store build.
