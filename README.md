# RemindToDeleteMedia — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

RemindToDeleteMedia helps you manage media files on your Android device by scheduling reminders to review and delete old photos and videos. All data is stored locally on your device. Sudarshan Tech Labs does not collect or transmit personal data.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Media reminder configurations (folder, file type, reminder date) | Core reminder functionality | Room database on your device |
| App preferences | Personalisation | DataStore on your device |

### Media File Access

RemindToDeleteMedia reads your media files (images and videos) to allow you to set reminders for specific folders or file types. Media file content is processed in-app only and is not stored permanently or transmitted externally. The App does not read, copy, or upload media file content.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Display media files for reminder setup | Read media metadata (not content) at runtime |
| Schedule and deliver reminder notifications | Local reminder configurations |
| Run background reminder checks | Local WorkManager tasks |

---

## Data Storage and Security

- **Reminder data:** Stored in a Room database in the App's private directory
- **No cloud storage:** Sudarshan Tech Labs operates no backend server
- **No media upload:** The App never reads, copies, or uploads your photos or videos to any server
- **Android sandbox:** All data is protected by Android's application isolation

## Data Retention

| Data | Retention |
|---|---|
| All local reminder data | Until you delete it or uninstall the App |

---

## Data Sharing

We do not collect, sell, or share your data or any media file content.

---

## Background Services

RemindToDeleteMedia uses a foreground service (`FOREGROUND_SERVICE_DATA_SYNC`) to check for due reminders in the background. A persistent notification is visible while the service runs.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Deliver media deletion reminder notifications |
| `RECEIVE_BOOT_COMPLETED` | Reschedule reminders after device restart |
| `READ_MEDIA_IMAGES` | Read image file metadata to set reminders for photos |
| `READ_MEDIA_VIDEO` | Read video file metadata to set reminders for videos |

---

## Your Rights and Controls

- **Delete individual reminders:** Use the delete function in the App
- **Delete all data:** Uninstall or go to Android Settings > Apps > RemindToDeleteMedia > Storage > Clear Data

---

## Children's Privacy

RemindToDeleteMedia is not directed at children under 13. We do not collect personal information.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of RemindToDeleteMedia after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Reminder configurations | Local only | No | App functionality |
| Media file metadata | Runtime only, not stored | No | Reminder setup |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
