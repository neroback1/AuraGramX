<p align="center">
  <a href="https://t.me/AuraGramx"><img src="auragramx-social.png" alt="AuraGramX — Your Telegram, refined. Blue AuraGramX logo and illustrative phone artwork." width="100%"></a>
</p>

<h1 align="center">AuraGramX</h1>

<p align="center"><strong>Your Telegram, refined.</strong><br>
An enhanced, unofficial Telegram client for Android.<br>
More control over your conversations, media and everyday experience.</p>

<p align="center">
  <a href="https://t.me/AuraGramx"><img alt="Download APK on Telegram" src="https://img.shields.io/badge/Download_APK-Telegram-0088CC?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="https://t.me/AuraGramXChat"><img alt="Join the community" src="https://img.shields.io/badge/Community-Join_chat-2563EB?style=for-the-badge&logo=telegram&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Android 8.1 or newer" src="https://img.shields.io/badge/Android-8.1%2B-3DDC84?logo=android&logoColor=white">
  <img alt="Universal APK, four architectures" src="https://img.shields.io/badge/APK-Universal_%C2%B7_4_ABIs-2563EB">
  <img alt="Arabic and English" src="https://img.shields.io/badge/Interface-Arabic_%26_English-00B8D9">
  <img alt="Developer NERO / MAHDI" src="https://img.shields.io/badge/By-NERO_%2F_MAHDI-182235">
</p>

<p align="center"><a href="#download">Download</a> · <a href="#features">Features</a> · <a href="#installation">Installation</a> · <a href="#updates">Updates</a> · <a href="#faq">FAQ</a> · <a href="#community--developer">Community</a></p>

## Meet AuraGramX

AuraGramX brings a distinctive electric-blue identity and practical power-user tools to the familiar Telegram experience. Stay connected to your Telegram chats, groups and channels while exploring local message history, media controls, on-device text recognition and deeper appearance customization.

Built and maintained by **NERO / MAHDI — one independent developer**.

> AuraGramX is a third-party Telegram client, not an official Telegram application. It is not affiliated with or endorsed by Telegram. This repository is the product and download guide, not the application's complete source tree.

## Download

### [Download AuraGramX APK from the official channel →](https://t.me/AuraGramx)

Open **@AuraGramx**, find the newest APK release post, download the attached file and install it. The button opens the channel; it is not a direct APK file link. The channel remains the source for future releases, so this page does not point to an expiring file mirror.

| Package information | Details |
| :--- | :--- |
| Platform | Android 8.1 or newer |
| Package | `com.tele.auragramx` |
| Distribution | Universal APK |
| Architectures | `arm64-v8a`, `armeabi-v7a`, `x86`, `x86_64` |
| Documented build | **12.10.0 (1274)** |
| Documented APK size | Approximately **117.3 MiB** |
| Download source | [@AuraGramx](https://t.me/AuraGramx) |

These details describe build 1274; check the channel for newer releases. Universal means the four listed architectures are included in one APK, not that every Android device is guaranteed compatible. See [release notes and checksum](CHANGELOG.md).

## Features

### Conversations, with more context

| Feature | What it adds |
| :--- | :--- |
| **Local deleted-message history** | Keep supported messages locally after deletion, with a visible deleted status and conversation refresh. |
| **Message edit history** | Review supported earlier versions of edited messages. |
| **Read-receipt history** | Retain available read information locally where supported. |
| **Bot-message saving controls** | Configure retention for messages from bots and inside bot chats. |
| **Per-chat saving controls** | Adjust which conversations participate in local message preservation. |
| **Reply without a quote** | Reply to a message without turning the action into a forward. |

Local history depends on what the client received and retained. It cannot recover messages it never received or files that no longer exist. Use retention features with the other participants' knowledge and permission.

### Media tools that fit your workflow

| Feature | What it adds |
| :--- | :--- |
| **Timed-media labels** | Distinguish view-once content from media with a specified self-destruct duration. |
| **Local media preservation** | Reopen supported downloaded media when preservation is enabled and a local copy remains available. |
| **Saved attachments** | Organize retained files with AuraGramX storage settings and configurable folder limits. |
| **Unlimited folder-limit option** | Disable the app's configured saved-attachment size cap; available device storage still applies. |
| **Transfer tuning** | Adjust supported upload and download behavior for your connection. Actual speed depends on Telegram and your network. |
| **Arabic + English OCR** | Extract text from images on your device using bundled recognition models, then copy the result or open translation. Translation may use an online provider. |

### A look that feels yours

- Dedicated **AuraGramX settings** with Arabic and English localization.
- Branded welcome experience, channel cards and release dialogs.
- Multiple AuraGramX launcher-icon options, including darker and illustrated styles.
- Theme, color, font and appearance controls.
- Bottom navigation for quickly moving between core sections.
- AuraGramX notification icon and notification preferences.
- Optional phone-number hiding in the local interface. This does **not** change Telegram's account-level phone-number privacy setting.

### Everyday essentials

- Your familiar Telegram conversations, groups, channels and media sharing.
- In-app release checking through the AuraGramX update channel.
- Background message reception support and connection-recovery handling.
- A single Universal APK for ARM and x86 devices.

Notification delivery still depends on Android permissions, battery restrictions and network availability. No client can guarantee instant delivery in every device state. See the [notification troubleshooting guide](SUPPORT.md#notifications-arrive-late).

## Installation

1. Open [the official download channel](https://t.me/AuraGramx) and download its latest APK attachment.
2. Open the APK. If Android asks, allow installation from the app you used to download it.
3. Complete the Android installer and open AuraGramX.
4. Sign in through the in-app Telegram account flow. Never send login codes or passwords to a channel administrator or another person.
5. Review notification permissions, background battery settings and AuraGramX's local-saving preferences.

**Already using AuraGramX?** Install the newer official APK over the existing app. Updates require the same application ID and a compatible signing certificate. Do not uninstall as a first troubleshooting step: uninstalling can remove local-only data. The official Telegram app can remain installed separately.

## Updates

AuraGramX can check the official channel and display an in-app update dialog with version details and a download action when it finds an eligible newer release. You can also use **Check for Updates** in the app or download the APK manually from the channel.

- Download and installation depend on your connection and Android permissions.
- Android's installer confirmation still applies; updates are not silently installed.
- A newer build number matters even if the visible Telegram base version is unchanged.
- If the app says it is up to date unexpectedly, compare its build number with the channel post and see [update troubleshooting](SUPPORT.md#an-update-is-not-detected).

## Privacy & responsible use

Local preservation can keep content longer than the sender intended. Review these settings before use, respect other people's privacy and do not treat local storage as a secure backup. Clearing app data, uninstalling or removing saved files may erase retained history.

AuraGramX builds include Firebase Analytics integration. This page does not claim the app is telemetry-free. OCR recognition runs locally; Telegram communication and optional online services require network access. Ordinary Telegram cloud chats should not be described as end-to-end encrypted.

Read [privacy and safety notes](PRIVACY.md) for the scope and limitations of these features.

## FAQ

<details>
<summary><strong>Is this the official Telegram app?</strong></summary>

No. AuraGramX is an independent, enhanced Telegram client for Android. Your account remains a Telegram account, and Telegram's service rules and limitations still apply.

</details>

<details>
<summary><strong>Which APK should I choose?</strong></summary>

The Universal APK includes ARM 32-bit, ARM 64-bit, x86 and x86_64 libraries. The documented build requires Android 8.1 or newer. You do not need a separate APK for each listed architecture.

</details>

<details>
<summary><strong>Can it recover every deleted message or expired photo?</strong></summary>

No. Preservation only applies where supported and where the client has received and retained the content. It is not server-side recovery and is not a guarantee that expired or deleted files remain available.

</details>

<details>
<summary><strong>Does it unlock Telegram Premium or remove Telegram's limits?</strong></summary>

No such claim is made. Client-side customization does not grant Telegram Premium, change account entitlements or remove server-enforced limits.

</details>

<details>
<summary><strong>Why might Android show an installation warning?</strong></summary>

Android may flag an unfamiliar or potentially unsafe APK. A working download link or a checksum alone does not establish safety. Verify the source, keep protection enabled and report unexpected warnings through the developer channel rather than installing a file you do not trust.

</details>

<details>
<summary><strong>Where can I report a problem?</strong></summary>

Use this repository's Issues or the community channel. Include the AuraGramX build number, Android version, device model, steps to reproduce and a redacted screenshot if useful. Never publish login codes, phone numbers, session files, passwords or signing keys. See [support guidance](SUPPORT.md).

</details>

## Community & developer

| Destination | Link |
| :--- | :--- |
| **APK downloads & updates** | [@AuraGramx](https://t.me/AuraGramx) |
| **Community chat** | [@AuraGramXChat](https://t.me/AuraGramXChat) |
| **Developer channel** | [@GAEMSMAHDI](https://t.me/GAEMSMAHDI) |
| **Developer** | **NERO / MAHDI** |

## Credits & source context

AuraGramX builds on the Telegram Android ecosystem and work by other client projects. See [credits and licensing context](CREDITS.md) for upstream acknowledgments. This showcase repository does not replace the corresponding application source or its license notices.

---

<p align="center"><strong>AuraGramX — Connect. Share. Evolve.</strong><br>
Independent Telegram client · Android · NERO / MAHDI<br>
<sub>Header artwork is a promotional illustration, not a literal application screenshot.</sub></p>
