# Heartseekers Android

Public APK releases for the Heartseekers organiser app.

- Each release attaches one file: `heartseekers-vX.Y.apk` (e.g. `heartseekers-v1.1.apk`).
- The website (`https://heartseekers.in/app/version`) and the installed app's
  update checker both point at that asset URL:
  `https://github.com/Suru4dan/heartseekers-android/releases/download/v1.1/heartseekers-v1.1.apk`
- To ship a new version: build the release APK, attach it to a new GitHub
  Release with tag `vX.Y`, then update `public/app/version` on the website.
