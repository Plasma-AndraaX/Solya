# Privacy Policy — Solya

**Effective date: February 8, 2026**

Solya is a voice assistant application designed for blind and visually impaired people. It enables managing emails, calendar, SMS, phone calls, reminders, instant messaging, notes, weather, news and web search by voice.

## 1. Data collected and purpose

### Audio data (microphone)
- **What**: Voice recordings captured through the device microphone.
- **Why**: Speech recognition to control the application by voice.
- **Processing**: Recordings are streamed in real time to a speech recognition service then immediately discarded. No audio recordings are stored on our servers.

### Emails
- **What**: Email content via Gmail or IMAP.
- **Why**: Read, summarize and reply to emails by voice.
- **Processing**: Emails are processed in memory on the device and sent to an artificial intelligence service for summarization and reply drafting. A local cache stores attachment metadata.

### Calendar
- **What**: Google Calendar events.
- **Why**: View, create and manage events by voice.
- **Processing**: Accessed via the Google API. Data remains on the device.

### Contacts
- **What**: Names and phone numbers from the Android contacts.
- **Why**: Make phone calls, send SMS and identify correspondents.
- **Processing**: Read-only access from the local contacts. Contacts are not transmitted to third parties.

### SMS
- **What**: Sent and received SMS messages.
- **Why**: Read and send SMS by voice.
- **Processing**: Accessed via Android APIs. Content may be sent to an artificial intelligence service for summarization.

### Call log
- **What**: Phone call history.
- **Why**: View missed calls and call back contacts.
- **Processing**: Read from the Android call log. Data is not transmitted to third parties.

### Location
- **What**: Approximate or precise geographic location.
- **Why**: Provide local weather and geographic context.
- **Processing**: Sent to the weather service to obtain forecasts. Not stored.

### Installed applications
- **What**: List of applications installed on the device.
- **Why**: Allow launching applications by voice command.
- **Processing**: Local read-only. The list is not transmitted to third parties.

### Email attachments
- **What**: Documents and images attached to emails.
- **Why**: Analysis and voice description of content (OCR, vision).
- **Processing**: Sent to a document analysis service for content extraction (OCR, vision), then deleted. A temporary local cache is used.

### Backup
- **What**: Application settings and data.
- **Why**: Allow restoration on a new device.
- **Processing**: Encrypted backup on Google Drive (optional, user-initiated).

## 2. Third-party services

To operate, Solya relies on third-party services in the following categories:

- **Speech recognition**: voice-to-text transcription (real-time audio stream, not retained).
- **Text-to-speech**: converting text into spoken audio.
- **Artificial intelligence**: understanding commands, summarizing content and drafting replies.
- **Google services**: access to emails, calendar and backup through your Google account.
- **Document analysis**: extracting text from attachments (OCR, vision).
- **Web search**: executing searches at the user's request.

These services are subject to their own privacy policies. Data transmitted is limited to the strict minimum required for each feature.

## 3. Data storage

- **On device**: Settings, attachment cache (SQLite), TTS audio cache, notes and reminders.
- **On Google Drive**: Encrypted backup (optional).
- **No proprietary server**: Solya does not have a backend server. All communications go directly between the device and third-party services.

## 4. Data sharing

Solya does not sell, rent or share any personal data for advertising or commercial purposes. Data is only transmitted to third-party services strictly within the scope of the features described above.

## 5. Security

- Communications with third-party services use HTTPS (TLS encryption).
- Google authentication uses the OAuth 2.0 protocol (no Google password is stored by the application).
- Google Drive backups are encrypted.

## 6. User rights

You can at any time:
- **Revoke permissions** for the application in Android settings.
- **Revoke Google access** from your Google account (https://myaccount.google.com/permissions).
- **Delete local data** by uninstalling the application.
- **Delete your backup** from Google Drive.

## 7. Children's use

Solya is not intended for children under 13 years of age. We do not knowingly collect data from minors.

## 8. Changes

This privacy policy may be updated. The effective date at the top of the document indicates the last revision. Continued use of the application after changes constitutes acceptance.

## 9. Contact

For any questions regarding this privacy policy, contact us at:https://github.com/Plasma-AndraaX/Solya/issues
