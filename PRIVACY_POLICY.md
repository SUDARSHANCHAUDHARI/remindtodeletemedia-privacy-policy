# RemindToDeleteMedia Privacy Policy

**Last Updated**: January 2026

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "our", or "us") collects, uses, and protects your information when you use the **RemindToDeleteMedia** Android application ("the App", "our App", "the Service").

By using RemindToDeleteMedia, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Tracked Folder Information

When you track a folder for reminders, we store the following information locally on your device:

* **Folder Identifier**: A stable identifier for the folder you selected
  * MediaStore folders: folder path/relative path used for grouping media
  * SAF folders: the selected folder’s tree Uri string
  * Stored in Room database
* **Folder Display Name**: Display name shown in the app
  * Derived from MediaStore bucket name or SAF folder name
  * Stored for display purposes
* **Reminder Days / Schedule**: How long until the reminder triggers
  * Set by you when creating a reminder
  * Stored in Room database
* **Exclusion Status**: Whether the folder is marked as “Keep Forever”
  * Set by you to exclude folders from reminders
  * Stored in Room database
* **Folder Statistics (Optional)**: Media counts and size estimates
  * Used for display and sorting
  * Stored in Room database (when available)

### 1.2 Reminder Data

We store reminder information locally on your device:

* **Reminder ID**: Unique identifier for each reminder
* **Folder Identifier**: Which folder the reminder is for
* **Trigger Time**: When the reminder should fire
* **Completion Status**: Whether the reminder has been completed/marked as reviewed
* **Snooze Status**: Whether the reminder has been snoozed
* **Snooze Count**: How many times the reminder has been snoozed

### 1.3 App Preferences (Local Storage)

The following data is stored locally on your device using DataStore:

* **Default Reminder Days**: Your preferred default number of days for reminders
* **Onboarding Completed**: Whether you've completed the onboarding flow
* **Theme / UI preferences** (if enabled)

### 1.4 What We DON'T Collect

We do **NOT** collect:

* ❌ Photos, videos, or other media file contents
* ❌ Personal identification information (name, email, phone number)
* ❌ Location data
* ❌ Contact information
* ❌ Device identifiers for tracking
* ❌ App usage analytics
* ❌ Advertising identifiers
* ❌ Payment information
* ❌ Biometric data

---

## 2. How We Use Your Information

### 2.1 Primary Uses

We use your information to:

* **Track Selected Folders**: Maintain the list of folders you chose to track
* **Set Reminders**: Create reminders based on your settings
* **Send Notifications**: Notify you when reminders expire (if notifications are enabled)
* **Manage Exclusions**: Remember folders marked as “Keep Forever”
* **Show Folder Stats**: Display counts/sizes (when available)

### 2.2 Data Sharing

* **With Third Parties**:
  * We do **NOT** share your data with any third parties
  * We do **NOT** sell, rent, or monetize your data
  * We do **NOT** use your data for advertising
* **With Cloud Services**:
  * We do **NOT** store your data in the cloud
  * We do **NOT** sync your data to any servers
  * All data remains on your device

---

## 3. Third-Party Services

### 3.1 No Third-Party Services

RemindToDeleteMedia **does not use any third-party services** that collect or process your data:

* ❌ No analytics services
* ❌ No advertising networks
* ❌ No crash reporting services
* ❌ No user tracking services

**Your data stays 100% on your device.**

---

## 4. Permissions Explained

### 4.1 Required Permissions

| Permission | Purpose | Why Needed |
|------------|---------|------------|
| **READ_MEDIA_IMAGES** | Scan photo folders | Detect folders containing images and show counts/sizes (Android 13+) |
| **READ_MEDIA_VIDEO** | Scan video folders | Detect folders containing videos and show counts/sizes (Android 13+) |
| **READ_EXTERNAL_STORAGE** | Scan media folders | Required for MediaStore access on Android 12 and below |
| **POST_NOTIFICATIONS** | Send reminder notifications | Notify you when reminders expire (Android 13+) |
| **RECEIVE_BOOT_COMPLETED** | Restore scheduling | Restore scheduled checks after reboot |

### 4.2 SAF Folder Picker (User-Selected Folder Access)

If you pick a folder using Android’s system folder picker (Storage Access Framework / SAF), Android may grant the app access to that folder. On some devices/Android versions, this access can be persisted so reminders can continue working after reboot.

---

## 5. Data Storage & Retention

### 5.1 Where Data is Stored

* **Room Database**: Tracked folders and reminders
  * Stored in app's private data directory
  * Protected by Android’s app sandbox
* **DataStore**: App preferences
  * Stored in app's private data directory
  * Protected by Android’s app sandbox
* **Local Device Only**: All data remains on your device
  * Not synced to cloud

### 5.2 Data Retention

* **Tracked Folders**: Retained until you remove them or uninstall the app
* **Reminders**: Retained until completed, deleted, or app uninstall
* **Preferences**: Retained until you change them or uninstall the app

### 5.3 Data Deletion

When you delete data or uninstall the app:

1. Tracked folder entries are removed from the database
2. Reminder entries are removed from the database
3. Preferences are cleared
4. Local app data is removed on uninstall

**Note**: Deletion is permanent and cannot be undone.

---

## 6. Security Measures

### 6.1 Data Protection

We implement security best practices:

* ✅ **Private Storage**: Data stored in the app’s private directory (not accessible by other apps)
* ✅ **No Network Transmission**: App data is never sent to external servers
* ✅ **Minimal Permissions**: Only requests permissions necessary for functionality

---

## 7. Your Rights

### 7.1 Data Control

You have the right to:

* **View Your Data**: Access tracked folders and reminders in the app
* **Edit Your Data**: Change reminder settings, snooze, keep forever, or remove tracking
* **Delete Your Data**: Remove tracked folders/reminders or clear app data
* **Uninstall**: Uninstalling removes all local data

### 7.2 GDPR Rights (EU Users)

If you're in the European Union, you have additional rights under GDPR:

* ✅ **Right to Access**
* ✅ **Right to Rectification**
* ✅ **Right to Erasure**
* ✅ **Right to Data Portability**
* ✅ **Right to Object**

**How to Exercise Your Rights**:
* Use the app's built-in features
* Contact us at sudarshantechlabs@gmail.com

### 7.3 CCPA Rights (California Users)

If you're in California, you have additional rights under CCPA:

* ✅ **Right to Know**
* ✅ **Right to Delete**
* ✅ **Right to Opt-Out** (we don't sell data)
* ✅ **Right to Non-Discrimination**

---

## 8. Children's Privacy

RemindToDeleteMedia is intended for users who are 13 years of age or older. We do not knowingly collect personal information from children under 13.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by updating the "Last Updated" date at the top of this policy.

---

## 10. Contact Us

If you have questions about this Privacy Policy, please contact us:

* **Email**: sudarshantechlabs@gmail.com
* **Developer Email**: sunny.sudarshan@gmail.com
* **Website**: https://sudarshantechlabs.com
* **GitHub**: [RemindToDeleteMedia Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)

**Response Time**: We aim to respond within **48 hours**.

---

**Last Updated**: January 2026


