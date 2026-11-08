# RemindToDeleteMedia — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-11-08
**Version:** 1.2.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

RemindToDeleteMedia helps you keep photo and video folders from quietly filling up, by letting you pick folders to track and reminding you to review them.

To do that it needs access to your photos and videos, which is sensitive. Three things are worth knowing up front, and all three are verifiable in the source:

1. **Nothing leaves your device.** The App has no `INTERNET` permission, so it is incapable of uploading your media or anything about it.
2. **The App never deletes your photos or videos.** It contains no media-deletion code at all. It reminds you, and you delete what you want to delete yourself, in your own gallery or file manager.
3. **It reads folder information, not your images.** What it stores is folder names, file counts, sizes and dates — never the contents of a photo.

Sudarshan Tech Labs operates no backend server and receives nothing from the App.

---

## Data Collection

### What the App reads from your media

| Data | Why |
|---|---|
| Folder names (the MediaStore "bucket") | So you can choose which folders to track and see them listed |
| File counts, file sizes and dates | To show how much a folder has grown since you last reviewed it |
| Relative paths | To identify a folder across sessions |

These come from Android's MediaStore index. The App queries the metadata columns only — bucket, date, size and path.

### When your images are displayed

The folder preview screen shows thumbnails of the photos in a folder you chose to preview, so you can see what is in it. Those images are read from your device and drawn on your screen. They are **not copied, uploaded, or stored anywhere by the App**.

### Data stored locally on your device

A Room database inside the App's private directory, holding three things: the folders you have chosen to track, your reminders for them, and your reminder history. Plus your preferences.

There is no account, no sign-in, no identifier, no analytics and no advertising.

---

## How You Grant Access

You choose the folders. The App opens Android's own folder picker, and Android grants it access to the folder you select — not to your whole library. That grant is recorded by Android and is revocable.

---

## How We Use Your Data

We do not use it, because we never receive it. Everything the App reads and stores is used only to show your tracked folders and send your reminders.

---

## Data Storage and Security

- **All data is stored locally** in a Room database inside the App's private directory, protected by Android's application sandbox
- **No transmission is possible:** the finished app declares no `INTERNET` permission, and contains no HTTP client, no Firebase, and no analytics or crash-reporting SDK
- **No cloud storage:** Sudarshan Tech Labs operates no backend server

## Data Retention

| Data | Retention |
|---|---|
| Tracked folders and settings | Until you remove them, clear app data, or uninstall the App |
| Media metadata | Not retained beyond what is shown to you; cleared with app data |

---

## Export and Backup

You can export your tracked-folder list and history to a file you choose. The file is written as JSON to the location you pick, on your device or wherever you point the picker. It contains your folder list and reminder history — no media. Nothing is sent anywhere.

---

## Data Sharing

Nothing is shared. We do not sell user data. Your folder names, your media metadata and your images never leave your device.

The App can open your browser at this project's GitHub page or its Play Store listing if you tap those links. That hands the request to your browser or the Play Store app; the App itself sends nothing.

---

## Permissions Explained

The App itself asks for five permissions:

| Permission | Why It Is Needed |
|---|---|
| `READ_MEDIA_IMAGES` | Read photo folder information, and show thumbnails in the preview screen (Android 13 and later) |
| `READ_MEDIA_VIDEO` | The same, for video folders (Android 13 and later) |
| `READ_EXTERNAL_STORAGE` | The equivalent on Android 12 and earlier, which had no split media permissions |
| `POST_NOTIFICATIONS` | Deliver your folder-review reminders |
| `RECEIVE_BOOT_COMPLETED` | Reschedule your reminders after the device restarts |

The App asks for **no write or delete permission over your media**, which is why it cannot remove anything itself.

### Permissions added by Android libraries

The finished app carries five more, declared by the Android libraries it is built on rather than by the App's own code. They still appear in the permission list you see on the Play Store:

| Permission | Comes from | What it does |
|---|---|---|
| `ACCESS_NETWORK_STATE` | WorkManager | Lets a library check whether a network exists. It does **not** grant network access, and without `INTERNET` nothing can be sent |
| `WAKE_LOCK`, `FOREGROUND_SERVICE`, `BIND_JOB_SERVICE` | WorkManager | How Android runs and re-registers the scheduled folder checks |
| `DUMP` | a build-time library | Diagnostic permission. Android grants it only to system apps, so it has no effect here |

**`INTERNET` is absent from the finished app.** Verified against the merged manifest, not just the App's own file.

---

## Your Rights and Controls

- **Revoke media access:** Android Settings → Apps → RemindToDeleteMedia → Permissions. The App can no longer read folder information
- **Stop tracking a folder:** remove it in the App. That deletes the tracking record only; your photos are untouched
- **Turn reminders off:** in the App's settings
- **Delete all data:** uninstall the App, or go to Android Settings → Apps → RemindToDeleteMedia → Storage → Clear Data

Because your data exists only on your device and we hold no copy, a data access or deletion request to us would return nothing — you already have the only copy.

---

## Children's Privacy

RemindToDeleteMedia is not directed at children under 13. We collect no personal information from anyone.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of RemindToDeleteMedia after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Photos and videos | Accessed on device, never collected or uploaded | No | App functionality |
| Files and docs (folder metadata) | Read on device, never collected | No | App functionality |
| Personal info | No | No | — |
| Crash logs | No | No | — |
| Device or other IDs | No | No | — |

Declare **"No data collected"** in the Play Console data safety form. The finished app has no network capability, so there is no transfer to disclose. Note that the broad media permissions require their own Play Console declaration of how they are used.

---

## Recent Updates (Version 1.2.0 - November 8, 2026)

- **Rewrote the policy from the app's source,** replacing the shared template. The previous text claimed protection by "the browser, Firebase, Google, GitHub" and carried scaffold location sections; this app uses none of them and requests no location.
- **Stated that the app never deletes your media.** For an app named RemindToDeleteMedia, holding photo and video permissions, a reader will assume otherwise and the old text never said. No deletion API is called anywhere, and no write or delete permission over media is requested.
- **Stated that it reads folder metadata, not image content** — bucket name, date, size and path. The exception is thumbnails drawn in the preview screen for a folder you chose to preview, which are not copied or stored.
- **Stated that nothing can leave the device.** No `INTERNET` permission in the finished build and no URL anywhere in the app's source.
- **Documented the folder grant,** which goes through Android's Storage Access Framework on a folder you pick, not your whole library, and the JSON export, which contains your folder list and history but no media.
- **Listed the five library-merged permissions** — `ACCESS_NETWORK_STATE`, `WAKE_LOCK`, `FOREGROUND_SERVICE` and `BIND_JOB_SERVICE` from WorkManager, and `DUMP` — since the app declares five while the Play Store shows ten.

---

## Recent Updates (Version 1.1.0 - May 17, 2026)

- **Aligned policy with the shared privacy-policy structure.**
- **Clarified folder/media metadata, local-only storage, permissions, and no automatic media deletion.**

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-11-08

---

This is the published policy, served at https://sudarshanchaudhari.github.io/remindtodeletemedia-privacy-policy/ from the `main` branch of this repository. `index.html` carries the same content for the web and must be updated alongside this file. The copy in the [RemindToDeleteMedia app repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia/blob/main/PRIVACY_POLICY.md) is kept identical.
