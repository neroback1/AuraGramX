# Privacy & safety notes

[← Back to AuraGramX](README.md)

These notes explain important feature boundaries. They are not a claim of an independent security audit or a complete legal privacy policy.

## Telegram account and communication

AuraGramX is an unofficial Telegram client. Telegram account access and communication depend on Telegram's services. Never share login codes, two-step verification passwords or session data with channel administrators or support contacts. Ordinary cloud chats are not end-to-end encrypted; do not infer extra encryption guarantees from the AuraGramX branding.

## Local message and media history

Supported message deletions, edits, read information and media can be retained on the device according to the app's saving settings. Some saving options are enabled by default in the documented build; review them before using the app. Local retention may outlast a sender's deletion or expiry request. Use it with the knowledge and permission of other participants.

Local retention is not a cloud backup or a recovery service. Uninstalling, clearing app data, deleting files or storage-management actions can remove retained data. A folder limit set to Unlimited does not provide unlimited physical storage.

Hiding a phone number in the client interface does not change who can see it under Telegram's account privacy settings.

## OCR and translation

Arabic and English OCR recognition uses bundled Tesseract models on the device. Choosing a translation action may send the extracted text to the selected online translation service. Review sensitive text before using online translation.

## Analytics

The application has Firebase Analytics integration. Do not interpret the product description as a no-analytics or no-telemetry promise. The available collection settings and behavior depend on the build; users who require further details should ask the developer before installing. See [Google's Firebase privacy information](https://firebase.google.com/support/privacy) for the provider's documentation.

## Permissions and installation

Notifications, camera, microphone, media access and background operation depend on Android permissions and the features you use. Review permissions in Android settings. Keep device security protections enabled and obtain APKs only from the intended release source. A checksum confirms that bytes match a particular file, not that the software is risk-free.
