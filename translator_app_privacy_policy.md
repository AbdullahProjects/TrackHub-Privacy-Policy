# Privacy Policy — Translator

**Effective date:** October 23, 2026

This privacy policy describes how the Translator app ("the App") handles information when you use it. The App is designed to work **on your device**: translation, language detection, text recognition, and speech features run locally, and your saved data never leaves your phone.

## Summary

- The App has **no user accounts, no servers, and no analytics**.
- Your translations, history, favorites and settings are stored **only on your device**.
- Text, photos, and voice input are processed **on-device** and are not uploaded to us — we never receive them.
- The only network traffic is **downloading language packs** for offline translation (provided by Google ML Kit) and your own sharing actions.
- We do **not** sell, share, or collect personal data.

## Information the App processes

This policy covers the features currently available in the App: text translation, photo translation and single-speaker voice translation.

### Text you translate
Text you type or paste is translated on your device using Google ML Kit on-device translation models. Input text is not sent to us and is not stored outside the App's local database.

### Voice translation (microphone)
When you tap the microphone button on the Text or Voice tab, the App records audio and passes it to your device's speech recognition service to produce text, which is then translated on the device. The Voice tab translates one speaker at a time. This happens only while you actively use the feature; the App does not record in the background. Audio is handled by the recognition service of your device/operating-system vendor — for example, Google's speech service on most Android phones, whose own privacy policy applies to that processing.

### Photo translation (text recognition)
When you take a photo or choose an image in the Photo tab, the image is processed on-device with Google ML Kit text recognition. The image is not uploaded or saved by the App.

### History, favorites, and settings
The App keeps a local database (SQLite) on your device containing:

- your translation history (source text and translated text),
- items you mark as favorites,
- app settings (such as languages, voice preferences, and history on/off).

This data never leaves your device. You can delete it at any time from **Settings → Delete all data**, by clearing individual history entries, or by uninstalling the App (uninstalling removes the database completely).

### Language packs
Language packs needed for translation are downloaded from Google (via ML Kit) when you need them. During these downloads your device contacts Google's servers; Google processes that request under its own privacy policy. The App itself does not transmit any of your personal information with these downloads.

## Permissions

- **Internet** — used only to download ML Kit language packs (and other on-demand ML Kit models) so translation works offline afterwards.
- **Microphone** — used only while you tap the voice-input button, to convert your speech to text.
- **Camera and photos** — used only when you tap "Take a photo" or "Choose from gallery" in the Photo tab, so the App can read text from that image on your device.

## Information we do not collect

We do not collect or receive:

- personal information (name, email, contacts, identifiers),
- location data,
- usage analytics, crash reports, or telemetry,
- advertising identifiers,
- your translations, voice recordings, or images.

There are no third-party analytics or advertising SDKs in the App.

## Third-party services

The App uses the following third-party components, each governed by its own terms:

- **Google ML Kit** (translation, language identification, text recognition) — model downloads and on-device inference: https://developers.google.com/ml-kit
- **Your device's speech recognition and text-to-speech services** — provided by your device vendor (e.g., Google on most Android devices).
- **The Android share sheet** — when you tap "share", the shared content is handled by the app you choose; the App does not send it anywhere itself.

## Data retention and deletion

All App data lives in the local database on your device. It is retained until you delete it:

1. Delete individual entries from History or Favorites, or
2. Use **Settings → Delete all data** to erase everything, or
3. Uninstall the App.

Language packs can be removed from the language pack manager inside the App.

## Security

Data is stored in the App's private local storage on your device. Because nothing is transmitted to us, there is no external store of your translations to breach. Protecting your device (lock screen, encryption) also protects the App's data.

## Children's privacy

The App does not target children under 13 (or the equivalent minimum age in your jurisdiction), and we do not knowingly collect personal information from children.

## Changes to this policy

We may update this policy as the App evolves. Changes will be posted in this file with a revised effective date. Continued use of the App after changes means you accept the updated policy.

## Contact

Questions about this policy? Contact:

**[Your name / company]** — **[you@example.com]**

_(Replace the placeholders above before publishing.)_
