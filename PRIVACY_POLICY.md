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

All data is stored locally on your device:

* **Room Database**: Tracked folders and reminders
  * Stored in app's private data directory (`/data/data/com.sudarshantechlabs.remindtodeletemedia/`)
  * Protected by Android's app sandbox
  * Encrypted using Android's built-in encryption
  * Not accessible by other apps or users
* **DataStore**: App preferences
  * Stored in app's private data directory
  * Protected by Android's app sandbox
  * Encrypted using Android's built-in encryption
* **Local Device Only**: All data remains on your device
  * Not synced to cloud
  * Not backed up to external services
  * Not accessible via network

### 5.2 Data Storage Security

* **Encryption**: All local data is encrypted using Android's built-in encryption mechanisms
* **App Sandbox**: Data is stored in the app's private directory, isolated from other apps
* **No External Access**: Data cannot be accessed by other apps or external services
* **No Network Storage**: Data is never stored on remote servers or cloud services

### 5.3 Data Retention

We retain your data for the following periods:

* **Tracked Folders**: Retained until you remove them or uninstall the app
* **Reminders**: Retained until completed, deleted, or app uninstall
* **Preferences**: Retained until you change them or uninstall the app
* **No Automatic Deletion**: We don't automatically delete your data based on time
* **User-Controlled**: You have full control over data retention through the app

### 5.4 Data Deletion

When you delete data or uninstall the app:

1. **Immediate Deletion**: Tracked folder entries are removed from the database immediately
2. **Reminder Removal**: Reminder entries are removed from the database
3. **Preferences Clear**: Preferences are cleared from DataStore
4. **Complete Removal**: Local app data is removed on uninstall
5. **Permanent**: Deletion is permanent and cannot be undone
6. **No Recovery**: Deleted data cannot be recovered

### 5.5 Backup and Sync

* **No Cloud Backup**: Your data is not backed up to cloud services
* **No Sync**: Your data is not synced across devices
* **Local Only**: All data remains on the device where it was created
* **Manual Backup**: You can manually backup your device using Android's built-in backup features (if enabled), but this is controlled by you, not the app

---

## 6. Security Measures

### 6.1 Data Protection

We implement security best practices to protect your data:

* ✅ **Private Storage**: Data stored in the app's private directory (not accessible by other apps)
* ✅ **Encryption**: All local data is encrypted using Android's built-in encryption mechanisms
* ✅ **No Network Transmission**: App data is never sent to external servers
* ✅ **Minimal Permissions**: Only requests permissions necessary for functionality
* ✅ **Secure Storage**: Data stored in app's private directory protected by Android's app sandbox
* ✅ **Regular Updates**: Security patches and updates applied regularly

### 6.2 Data Breach Procedures

In the unlikely event of a data breach affecting your personal information, we will:

* Notify affected users within 72 hours of becoming aware of the breach
* Provide clear information about what data was affected
* Explain steps taken to address the breach
* Offer guidance on protective measures users can take

**Note**: Since all data is stored locally on your device, the risk of external data breaches is minimal. However, we take security seriously and will communicate transparently if any security issues arise.

---

## 7. Your Rights

### 7.1 Data Control

You have the right to:

* **View Your Data**: Access tracked folders and reminders in the app
* **Edit Your Data**: Change reminder settings, snooze, keep forever, or remove tracking
* **Delete Your Data**: Remove tracked folders/reminders or clear app data
* **Uninstall**: Uninstalling removes all local data

### 7.2 GDPR Rights (EU Users)

If you're in the European Union, you have additional rights under the General Data Protection Regulation (GDPR):

* ✅ **Right to Access**: You have the right to request copies of your personal data
* ✅ **Right to Rectification**: You have the right to request correction of inaccurate or incomplete data
* ✅ **Right to Erasure**: You have the right to request deletion of your personal data ("Right to be Forgotten")
* ✅ **Right to Restrict Processing**: You have the right to request restriction of processing your personal data
* ✅ **Right to Data Portability**: You have the right to request transfer of your data to another service
* ✅ **Right to Object**: You have the right to object to processing of your personal data
* ✅ **Right to Withdraw Consent**: You have the right to withdraw consent at any time

**Legal Basis for Processing**: We process your data based on:
* **Legitimate Interest**: Providing reminder functionality and app features
* **Consent**: When you explicitly grant permissions or use features

**How to Exercise Your Rights**:
* Use the app's built-in features in Settings to view, edit, or delete your data
* Contact us directly at sudarshantechlabs@gmail.com with your request
* We will respond to your request within 30 days (as required by GDPR)
* You also have the right to lodge a complaint with your local data protection authority

### 7.3 CCPA Rights (California Users)

If you're in California, you have additional rights under the California Consumer Privacy Act (CCPA):

* ✅ **Right to Know**: You have the right to know what personal information we collect, use, and share
* ✅ **Right to Delete**: You have the right to request deletion of your personal information
* ✅ **Right to Opt-Out**: You have the right to opt-out of sale of personal information (we don't sell data)
* ✅ **Right to Non-Discrimination**: We won't discriminate against you for exercising your privacy rights
* ✅ **Right to Data Portability**: You have the right to request your data in a portable format

**How to Exercise Your Rights**:
* Use the app's built-in features in Settings
* Contact us at sudarshantechlabs@gmail.com with "CCPA Request" in the subject line
* We will respond within 45 days (as required by CCPA)

### 7.4 Data Portability

You can request a copy of your data in a machine-readable format. To request your data:

1. Contact us at sudarshantechlabs@gmail.com
2. Specify the format you prefer (JSON, CSV, etc.)
3. We will provide your data within 30 days

**Note**: Since all data is stored locally, you can also access it directly through the app's interface.

---

## 8. Children's Privacy

RemindToDeleteMedia is intended for users who are 13 years of age or older. We do not knowingly collect personal information from children under 13.

### 8.1 COPPA Compliance

In compliance with the Children's Online Privacy Protection Act (COPPA):

* We do not knowingly collect personal information from children under 13
* If we discover that we have collected information from a child under 13, we will delete it immediately
* Parents or guardians who believe we may have collected information from a child under 13 should contact us immediately

### 8.2 Age Restrictions

* **Minimum Age**: 13 years old
* **Parental Consent**: Required for users under 18 in some jurisdictions
* **Age Verification**: We rely on app store age restrictions and do not verify user age directly

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect:

* Changes in app features or functionality
* Legal requirements and regulations
* Best practices and industry standards
* User feedback and requests

### 9.1 How We Notify You

When we make changes to this Privacy Policy:

* **Significant Changes**: We will notify you through:
  * In-app notifications (for major changes)
  * App update release notes
  * Updated "Last Updated" date at the top of this policy
* **Minor Changes**: Minor updates will be reflected in the "Last Updated" date
* **Continued Use**: Your continued use of the app after changes constitutes acceptance of the updated policy

### 9.2 Reviewing Changes

* The current version is always available in this repository
* Previous versions are available in the repository's commit history
* You can review changes by checking the "Last Updated" date

**Last Updated**: January 2026

---

## 10. International Data Transfers

### 10.1 Data Location

Since all data is stored locally on your device:

* **No International Transfers**: Your data never leaves your device
* **No Cross-Border Data Transfer**: No data is transferred across international borders
* **Local Storage Only**: All data remains on your device in your country/region

### 10.2 Data Processing Location

* All data processing occurs locally on your device
* No data is processed on external servers
* No cloud-based processing or storage

---

## 11. Cookies and Tracking Technologies

### 11.1 No Cookies or Tracking

RemindToDeleteMedia **does not use**:

* ❌ Cookies
* ❌ Web beacons
* ❌ Tracking pixels
* ❌ Analytics tracking
* ❌ Advertising identifiers
* ❌ Device fingerprinting

**Your privacy is protected - no tracking technologies are used.**

---

## 12. User Controls and Privacy Settings

### 12.1 Privacy Controls Available in the App

You have full control over your data through the app's settings:

* **Notification Settings**: Enable/disable notifications
* **Folder Management**: Add, remove, or exclude folders from tracking
* **Reminder Management**: Modify, snooze, or delete reminders
* **Data Deletion**: Remove individual folders or clear all app data
* **Preferences**: Customize default reminder days and other settings

### 12.2 How to Delete Your Data

**To delete your data:**

1. **Individual Folder**: Remove a tracked folder from the app
2. **All Data**: Clear all app data through Android Settings > Apps > RemindToDeleteMedia > Storage > Clear Data
3. **Uninstall**: Uninstalling the app permanently deletes all local data

**Note**: Data deletion is permanent and cannot be undone.

---

## 13. Data Retention and Deletion

### 13.1 Retention Periods

* **Tracked Folders**: Retained until you remove them or uninstall the app
* **Reminders**: Retained until completed, deleted, or app uninstall
* **Preferences**: Retained until you change them or uninstall the app
* **No Automatic Deletion**: We don't automatically delete your data

### 13.2 Deletion Procedures

When you delete data:

1. **Immediate Deletion**: Data is removed from the database immediately
2. **Permanent Removal**: Deleted data cannot be recovered
3. **Uninstall**: Uninstalling removes all app data permanently
4. **No Backup**: Since data is local-only, there are no cloud backups to delete

---

## 14. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

### 14.1 Contact Information

* **Company Email**: sudarshantechlabs@gmail.com
* **Developer Email**: sunny.sudarshan@gmail.com
* **Website**: https://sudarshantechlabs.com
* **GitHub**: [RemindToDeleteMedia Repository](https://github.com/SUDARSHANCHAUDHARI/RemindToDeleteMedia)
* **Company**: Sudarshan Tech Labs
* **Developer**: Sudarshan Kishor Chaudhari

### 14.2 Response Times

* **General Inquiries**: We aim to respond within **48 hours**
* **Privacy Requests (GDPR)**: We will respond within **30 days** (as required by law)
* **Privacy Requests (CCPA)**: We will respond within **45 days** (as required by law)
* **Data Breach Notifications**: Within **72 hours** (if applicable)

### 14.3 What to Include in Your Request

When contacting us about privacy matters, please include:

* Your name (optional)
* Description of your request or concern
* Any relevant details about your inquiry
* Preferred method of response

---

## 15. Legal Information

### 15.1 Governing Law

This Privacy Policy is governed by applicable privacy laws including:

* General Data Protection Regulation (GDPR) for EU users
* California Consumer Privacy Act (CCPA) for California users
* Other applicable local privacy laws

### 15.2 Dispute Resolution

If you have concerns about how we handle your data:

1. Contact us first at sudarshantechlabs@gmail.com
2. We will work to resolve your concern promptly
3. You have the right to file a complaint with your local data protection authority

### 15.3 Severability

If any provision of this Privacy Policy is found to be invalid or unenforceable, the remaining provisions will continue to be valid and enforceable.

---

**Last Updated**: January 2026

**Version**: 1.0

---

*This Privacy Policy is effective as of the "Last Updated" date above. By using RemindToDeleteMedia, you acknowledge that you have read and understood this Privacy Policy.*


