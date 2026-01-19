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

### Local Storage

**All your personal data is stored locally on your device using:**

- **Room Database**: Encrypted local database for tracked folders and reminders
- **DataStore**: Secure local storage for app preferences
- **No Cloud Sync**: Your data never leaves your device
- **No Backups**: Data is not backed up to cloud services

### Security Measures

- ✅ **Encryption**: All local data is encrypted using Android's built-in encryption
- ✅ **No Network Transmission**: App data is never sent over the network
- ✅ **Secure Storage**: Data stored in app's private directory
- ✅ **Regular Updates**: Security patches and updates applied regularly

### Data Retention

- **Tracked Folders**: Retained until you remove them or uninstall the app
- **Reminders**: Retained until completed, deleted, or app uninstall
- **Preferences**: Retained until you change them or uninstall the app
- **Uninstall**: All data is permanently deleted when you uninstall the app

---

## 🌐 Third-Party Services

### No Third-Party Services

RemindToDeleteMedia **does not use any third-party services** that collect or process your data:

- ❌ No analytics services
- ❌ No advertising networks
- ❌ No cloud storage services
- ❌ No crash reporting services
- ❌ No user tracking services

**Your data stays 100% on your device.**

---

## 🔐 Permissions Explained

### Required Permissions

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **READ_MEDIA_IMAGES** (Android 13+) | Scan photo folders | Detect folders containing images and show counts/sizes |
| **READ_MEDIA_VIDEO** (Android 13+) | Scan video folders | Detect folders containing videos and show counts/sizes |
| **READ_EXTERNAL_STORAGE** (Android 12 and below) | Scan media folders | Required for MediaStore access on older Android versions |
| **POST_NOTIFICATIONS** | Send reminder notifications | Notify you when reminders expire |
| **RECEIVE_BOOT_COMPLETED** | Restore scheduling | Restore scheduled checks after reboot |

**SAF folder picker**: When you pick a folder, Android grants the app access to that folder (where supported).

### Privacy Controls

- ✅ **Notification Control**: Enable/disable notifications anytime in Settings
- ✅ **Data Deletion**: Remove tracked folders or clear all data anytime
- ✅ **Exclude Folders**: Mark folders as "Keep Forever" to exclude from reminders
- ✅ **Uninstall**: Uninstalling removes all local data permanently

---

## 👤 Your Rights

### Data Control

- **View Your Data**: Access all tracked folders and reminders in the app
- **Edit Your Data**: Modify reminder days, exclude folders, or remove tracking
- **Delete Your Data**: Remove individual folders or clear all data (Settings)
- **Uninstall**: Uninstalling removes all local data

### GDPR Rights (EU Users)

If you're in the European Union, you have additional rights:

- ✅ **Right to Access**: View all your personal data
- ✅ **Right to Rectification**: Edit inaccurate data
- ✅ **Right to Erasure**: Delete your data at any time ("Right to be Forgotten")
- ✅ **Right to Data Portability**: Request your data export (contact us)
- ✅ **Right to Object**: Control how your data is used

**How to Exercise Your Rights**:

- Use the app's built-in features in Settings
- Contact us directly at sudarshantechlabs@gmail.com
- We will respond within 48 hours

### CCPA Rights (California Users)

If you're in California, you have additional rights under CCPA:

- ✅ **Right to Know**: Know what personal information we collect
- ✅ **Right to Delete**: Request deletion of your personal information
- ✅ **Right to Opt-Out**: Opt-out of sale of personal information (we don't sell data)
- ✅ **Right to Non-Discrimination**: We won't discriminate for exercising your rights

---

## 📱 App Information

- **Package Name**: `com.sudarshantechlabs.remindtodeletemedia`
- **Platform**: Android only
- **Language**: Kotlin
- **Architecture**: MVVM with Jetpack Compose
- **Database**: Room (Local SQLite)

---

## 📄 Privacy Policy

The complete, detailed privacy policy is available in [PRIVACY_POLICY.md](./PRIVACY_POLICY.md).

**Key Sections:**

- Information We Collect
- How We Use Your Information
- Data Storage & Retention
- Data Sharing
- Your Rights and Controls
- Children's Privacy
- Permissions Explained
- Security Measures
- GDPR Rights
- Contact Information

---

## 🚨 Important Privacy Highlights

### ✅ What We Do

- Store all data locally on your device
- Use encryption for local storage
- Allow you to export or delete your data anytime
- Work completely offline
- Respect your privacy choices
- Never share your data with third parties

### ❌ What We DON'T Do

- Store your data in the cloud
- Share your data with third parties
- Sell your data
- Track you across apps or websites
- Require user accounts
- Collect location data
- Access your contacts or other personal data
- Use analytics or advertising
- Send data to external servers

---

## 📞 Contact & Support

### Privacy-Related Questions

If you have questions about:

- How we handle your data
- Your privacy rights
- Data deletion requests
- GDPR compliance
- Security concerns

**Contact Us:**

- **Email**: sudarshantechlabs@gmail.com
- **Developer Email**: sunny.sudarshan@gmail.com
- **Website**: https://sudarshantechlabs.com
- **GitHub Issues**: [RemindToDeleteMedia Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)

### Response Time

We aim to respond to privacy-related inquiries within **48 hours**.

---

## 🔄 Policy Updates

We may update this privacy policy from time to time to reflect:

- Changes in app features
- Legal requirements
- Best practices
- User feedback

**How We Notify You:**

- In-app notifications for significant changes
- App update release notes
- Updated "Last updated" date in the policy

**Last Updated**: January 2026

---

## 📚 Additional Resources

- **Main App Repository**: [Source code and documentation](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)
- **GDPR Information**: European privacy regulations
- **CCPA Information**: California privacy regulations

---

## 🏢 About Sudarshan Tech Labs

**RemindToDeleteMedia** is developed and published by **Sudarshan Tech Labs**.

- **Company**: Sudarshan Tech Labs
- **Website**: https://sudarshantechlabs.com
- **Email**: sudarshantechlabs@gmail.com
- **Developer**: Sudarshan Kishor Chaudhari
- **Developer Email**: sunny.sudarshan@gmail.com
- **GitHub**: @SUDARSHANCHAUDHARI

---

## 📜 License

This privacy policy repository is licensed under the **MIT License**.

See [LICENSE](./LICENSE) file for details.

---

## ⭐ Quick Privacy Summary

### 🔒 Your Data Stays Local

**All your personal content (tracked folders, reminders, preferences) is stored on your device and never sent to any server.**

| Feature | Privacy Status |
|-------------------|----------------|
| Tracked Folders | ✅ 100% Local |
| Reminders | ✅ 100% Local |
| App Preferences | ✅ 100% Local |
| Notifications | ✅ Local Only |
| Analytics | ❌ None |
| Cloud Sync | ❌ None |
| Third-Party Services | ❌ None |

---

**Made with ❤️ by Sudarshan Tech Labs**

_Privacy is not a feature - it's a fundamental right._

[View Full Privacy Policy](./PRIVACY_POLICY.md) | [Main App Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)


