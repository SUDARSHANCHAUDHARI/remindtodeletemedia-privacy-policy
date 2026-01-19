## RemindToDeleteMedia Privacy Policy 📱🔒

**Official Privacy Policy Repository for RemindToDeleteMedia Android Application**

<div align="center">

[![Privacy](https://img.shields.io/badge/Privacy-First-green.svg)](./PRIVACY_POLICY.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)

*Your privacy matters. All your data stays on your device.*

</div>

---

## 📋 About This Repository

This repository hosts the official privacy policy for the **RemindToDeleteMedia** Android application. It is maintained for:

- **Public Access**: Easy access to our privacy policy
- **Google Play Store**: Required privacy policy link for app listing
- **Transparency**: Clear communication about how we handle your data
- **Compliance**: Meeting privacy regulations (GDPR, CCPA, etc.)

---

## 🎯 About RemindToDeleteMedia

**RemindToDeleteMedia** is an Android app that helps you manage storage by setting reminders to review media folders and delete unwanted photos/videos manually using your system gallery/file manager.

**Key Features:**

- ⏰ **Time-based folder reminders** - Set reminders to review folders after X days (3, 7, 14, 30, or custom)
- 🗂️ **Folder selection** - Scan MediaStore folders and/or pick any folder via the system folder picker (SAF)
- 😴 **Snooze reminders** - Snooze reminders when you’re not ready to clean up
- ⭐ **Keep folders forever** - Exclude folders from reminders permanently
- 🔔 **Notifications** - Get notified when it’s time to review a folder
- 🎨 **Modern UI** - Built with Jetpack Compose and Material design

**Important**: The app **never deletes media automatically**. All deletions are performed manually by you.

**Learn more**: [Main RemindToDeleteMedia Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)

---

## 🔒 Privacy-First Design

RemindToDeleteMedia is built with **privacy and security as core principles**.

### Core Privacy Principles

1. **100% Local Storage**: All data is stored locally on your device
2. **No Cloud Storage**: We don't store your data on any remote servers
3. **No User Accounts**: No account creation required
4. **Minimal Data Collection**: We only store what’s required for reminders
5. **No Tracking**: No analytics, no ads, no external servers
6. **Transparent Practices**: Clear communication about what we access and why

---

## 📊 What Data We Collect

### Media Reminder Data (Stored Locally Only)

- **Tracked Folders**:
  - Folder identifier (MediaStore relative path, or SAF tree Uri)
  - Folder display name
  - Reminder days configuration
  - Exclusion status (Keep Forever)
  - Basic folder statistics (counts/sizes, when available)
- **Reminder Data**:
  - Reminder ID
  - Folder identifier
  - Trigger time
  - Completion status
  - Snooze count and status
- **App Preferences** (Stored Locally Only):
  - Default reminder days setting
  - Onboarding completion status

### What We DON'T Collect

- ❌ Photos, videos, or other media files
- ❌ Personal identification information (name, email, phone)
- ❌ Location data
- ❌ Contacts
- ❌ Device identifiers for tracking
- ❌ Analytics or advertising identifiers

---

## 💾 Data Storage & Security

**All data is stored locally on your device using:**

- **Room Database**: Tracked folders and reminders
- **DataStore**: App preferences
- **No Cloud Sync**: Your data never leaves your device

---

## 🌐 Third-Party Services

RemindToDeleteMedia **does not use third-party services** that collect your data:

- ❌ No analytics services
- ❌ No advertising networks
- ❌ No crash reporting services

---

## 🔐 Permissions Explained

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **READ_MEDIA_IMAGES** (Android 13+) | Scan photo folders | Detect folders containing images and show counts/sizes |
| **READ_MEDIA_VIDEO** (Android 13+) | Scan video folders | Detect folders containing videos and show counts/sizes |
| **READ_EXTERNAL_STORAGE** (Android 12 and below) | Scan media folders | Required for MediaStore access on older Android versions |
| **POST_NOTIFICATIONS** | Send reminder notifications | Notify you when reminders expire |
| **RECEIVE_BOOT_COMPLETED** | Restore scheduling | Restore scheduled checks after reboot |

**SAF folder picker**: When you pick a folder, Android grants the app access to that folder (where supported).

---

## 📄 Full Privacy Policy

The complete, detailed privacy policy is available in [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).

---

## 📜 License

This privacy policy repository is licensed under the **MIT License**.

See [LICENSE](./LICENSE) file for details.


