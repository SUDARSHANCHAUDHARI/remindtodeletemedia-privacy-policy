## Privacy Policy — RemindToDeleteMedia

### Data collection
RemindToDeleteMedia does **not** collect, store, or transmit personal data to external servers.

### What we store (on-device only)
The app stores only:
- Folder identifiers you choose to track (MediaStore relative path, or SAF tree Uri)
- Reminder configuration (schedule, snooze state)
- Folder statistics (counts/sizes, when available)
- App preferences (onboarding state, theme)

### Media access
The app accesses photos/videos only to:
- Detect media folders (MediaStore)
- Calculate basic folder statistics

The app **never**:
- Uploads media
- Shares media with third parties
- Deletes media automatically

### Permissions
- `READ_MEDIA_IMAGES` / `READ_MEDIA_VIDEO` (Android 13+): scan media folders and show counts
- `READ_EXTERNAL_STORAGE` (Android 12 and below): scan media folders
- `POST_NOTIFICATIONS`: send reminder notifications
- `RECEIVE_BOOT_COMPLETED`: restore scheduled checks after reboot
- SAF (user-selected folder): uses a user-granted folder permission when you pick a folder

### Contact
Email: `sunny.sudarshan@gmail.com`

