# Heartseekers Android (releases)

Public APK releases for the Heartseekers organiser app.

- Each release attaches one file: `heartseekers-vX.Y.apk` (e.g. `heartseekers-v1.0.apk`).
- The website (`https://heartseekers.in/app/version`) and the installed app's
  update checker both point at that asset URL:
  `https://github.com/Suru4dan/heartseekers-android-release/releases/download/v1.0/heartseekers-v1.0.apk`
- To ship a new version: build the APK, attach it to a new GitHub
  Release with tag `vX.Y`, then update `public/app/version` on the website.
  The app source lives in the private `heartseekers_android` repository.
