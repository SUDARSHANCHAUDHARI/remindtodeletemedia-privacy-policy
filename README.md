# Privacy Policy — RemindToDeleteMedia

**Effective Date:** 2026-03-21
**Company:** SudarshanTechLabs
**Location:** Bangkok, Bangkok, TH
**Contact:** sudarshantechlabs@gmail.com

---

## 1. Data Collection

RemindToDeleteMedia **does not collect, store, or transmit any personal data** to external servers, third-party services, or the developer.

The app operates entirely on your device. There are no analytics, no crash reporting services, no advertising SDKs, and no network requests of any kind.

---

## 2. Data Stored on Your Device

The app stores the following data **locally on your device only**:

- **Folder identifiers** — the media folders you choose to track (stored as MediaStore relative paths or SAF tree URIs)
- **Reminder configuration** — reminder interval (days or date), snooze state, "keep forever" flag
- **Folder statistics** — media count and estimated storage size, calculated on-device when you open the app
- **App preferences** — onboarding completion state, theme setting

All of this data is stored using Android's standard local storage (Room database + DataStore Preferences). It never leaves your device.

---

## 3. Data Use

The data stored on your device is used solely to:

- Schedule and display reminder notifications for folders you have configured
- Show you folder statistics (media count, storage used)
- Restore reminders after your device restarts

---

## 4. Media Access

The app requests permission to access photos and videos on your device (`READ_MEDIA_IMAGES`, `READ_MEDIA_VIDEO` on Android 13+, or `READ_EXTERNAL_STORAGE` on Android 12 and below).

This access is used **only** to:
- Detect available media folders
- Calculate basic folder statistics (count and size)

The app **never**:
- Uploads, shares, or transmits your media to any server or service
- Deletes any media file automatically
- Modifies any media file

You are always in full control of your media. Any deletion is performed manually by you in your gallery or file manager.

---

## 5. Third-Party Services

RemindToDeleteMedia does **not** integrate with any third-party services, including:

- Analytics platforms (e.g., Firebase Analytics, Mixpanel)
- Advertising networks
- Crash reporting services (e.g., Crashlytics)
- Social login providers
- Cloud storage services

---

## 6. Permissions

| Permission | Purpose |
|---|---|
| `READ_MEDIA_IMAGES` / `READ_MEDIA_VIDEO` (Android 13+) | Scan media folders and calculate stats |
| `READ_EXTERNAL_STORAGE` (Android ≤ 12, maxSdkVersion 32) | Scan media folders and calculate stats |
| `POST_NOTIFICATIONS` | Send reminder notifications when a folder review is due |
| `RECEIVE_BOOT_COMPLETED` | Restore scheduled reminders after device reboot |
| SAF folder access (user-granted) | Access a custom folder selected by you via the system file picker |

No permission is used for any purpose beyond what is listed above.

---

## 7. Security

Because RemindToDeleteMedia stores all data locally and transmits nothing over the network, there is no data-in-transit exposure. Local storage is protected by Android's standard app sandboxing.

---

## 8. Children's Privacy

RemindToDeleteMedia does not collect personal information from anyone, including children under the age of 13. The app contains no content directed at children.

---

## 9. Changes to This Policy

If this privacy policy changes in a future version of the app, the updated policy will be published at the same URL with an updated effective date. Continued use of the app after a policy change constitutes acceptance of the new policy.

---

## 10. Contact Us

If you have any questions about this privacy policy, please contact:

**SudarshanTechLabs**
Bangkok, Bangkok, Thailand
Email: sudarshantechlabs@gmail.com
