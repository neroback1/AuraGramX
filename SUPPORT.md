# Support & troubleshooting

[← Back to AuraGramX](README.md)

## Notifications arrive late

1. Allow AuraGramX notifications in Android settings and check the individual chat is not muted.
2. Check that the notification category you need has not been disabled.
3. Allow background data and, where available, unrestricted battery usage for AuraGramX.
4. On devices with a separate auto-start setting, allow the app to start in the background.
5. Check the connection and whether a configured proxy is reachable.
6. If you force-stopped the app, open it again. Force-stop and manufacturer restrictions can prevent background reception.

A persistent background-service notification is separate from message alerts. If Android lets you hide its category, change only that category; disabling all AuraGramX notifications also hides message alerts. Delivery during Doze or aggressive power saving varies by device.

## An update is not detected

Compare the full build numbers, not only `12.10.0`. Check your network, open the official [@AuraGramx channel](https://t.me/AuraGramx) and confirm a newer APK has actually been published. You can download that APK manually.

The updater depends on the release post format and the update logic in the installed version. A malformed post or an older updater can prevent detection. Report both the installed build and the release post link; do not assume that a public APK post guarantees detection by every old build.

## Android will not install an update

Check available storage, Android compatibility and whether the file downloaded completely. An in-place update requires the same application ID and a compatible signing certificate. Do not uninstall before considering the local-only history and media that could be lost.

If Play Protect shows a warning, do not assume it is harmless. Verify the source and report the exact warning to the developer. A SHA-256 match verifies file identity, not absence of malicious behavior.

## Deleted history or saved media is missing

Confirm the relevant preservation option and per-chat settings. The client must have received and saved the content first. Files may be unavailable after storage cleanup, deletion, uninstall or app-data clearing. These features do not recover content from Telegram's servers after it becomes unavailable.

## Text recognition is inaccurate

Use a clear, higher-resolution image with readable Arabic or English text. Blur, handwriting, perspective and decorative typefaces can reduce accuracy. Review recognized text before copying or translating it.

## Report a bug

Open a GitHub issue or contact the [community](https://t.me/AuraGramXChat). Include:

- AuraGramX version and build number.
- Android version and device model.
- Expected behavior and what actually happened.
- Short reproduction steps and whether it happens consistently.
- A redacted screenshot or relevant log excerpt, only if it contains no private information.

Never include login codes, phone numbers, private messages, session/authentication files, passwords, signing keys or unredacted diagnostic archives. For security-sensitive matters, ask the [developer channel](https://t.me/GAEMSMAHDI) for an appropriate private contact before sharing details.
