# Privacy Notice
## Simple Clicker App (Huawei AppGallery)

**Effective date:** 21.08.2026
**Last updated:** 21.08.2026
**Applies to app version:** 1.2.0
**Data Controller:** Maksim Sorokoumov
**Contact email:** kamchatka_lab@mail.ru
**Controller country/address:** Russia

This Notice explains how data is processed when you use **Simple Clicker** (package: `com.kamchatka.simple_clicker.huawei`) in Huawei AppGallery.

The app is a counter with three modes (plain counter, "Knitting", and "Beads"). It has no user accounts, no sign-up, and no backend of its own: the controller neither receives nor stores user data on its side.

## 1. What data is processed

### 1.1 Data processed locally on your device
The app stores in the device's local storage:
- counter projects for the plain counter, "Knitting", and "Beads" modules: the name you enter, the current and target counter values, project settings (for example, pattern-repeat parameters), and creation/archiving dates;
- counter session history (name, value, date), including entries migrated from earlier app versions;
- app preferences: theme, interface language, selected click sound, vibration on/off, and button caption display.

This data never leaves your device: it is not sent to the controller and is not shared with third parties. Project and session names are entered by you — we recommend not putting personal data into them.

### 1.2 Device sensor data
In the "Knitting" and "Beads" modules, an optional mode increments the counter when you tilt the device. For this mode the app reads the built-in accelerometer. Readings are processed in real time on the device only; they are not stored and not transmitted anywhere. The mode is enabled by the user and is off by default.

The app also uses the device's haptic feedback (a short vibration), which can be turned off in settings.

### 1.3 Data that may be processed by a third-party ad network
The app uses **Yandex Mobile Ads SDK** to display a banner ad through the Huawei AppGallery platform.
When ads are served, the third-party SDK may process:
- device advertising identifiers (e.g., OAID/AAID/GAID, where available);
- IP address and network parameters;
- technical device/app data;
- ad events (impressions, clicks, technical delivery events).

Purposes: ad delivery, frequency capping, anti-fraud, and ad performance analytics.

The controller does not receive this data in an identifiable form and does not use it outside the operation of the ad SDK.

## 2. App permissions

The app requests a single permission:
- `INTERNET` — to load the banner ad and perform the related network requests.

The app does **not** request access to contacts, microphone, camera, photos or videos, files, precise or approximate location, or the list of installed apps.

Please also note:
- the audio recording permission (`RECORD_AUDIO`) contributed by one of the library dependencies is explicitly removed from the release manifest: voice mode is unavailable in this app version and the microphone is not used;
- Bluetooth permissions that dependencies may contribute are likewise removed from the manifest;
- no Android permission is required to read the accelerometer or to trigger haptic feedback.

## 3. Legal bases

Processing is carried out:
- to provide app functionality and deliver services to you;
- based on our legitimate interests in monetizing the app through advertising;
- based on user consent where required by applicable law.

By using the app, you consent to data processing as described in this Notice.

## 4. Third-party sharing

We do not sell users' personal data to third parties.
Ad-related data may be processed by third-party providers through SDK operation:
- **Yandex Ads (Yandex Mobile Ads SDK)**
  Yandex Privacy Policy: https://yandex.com/legal/confidential/
  SDK documentation: https://ads.yandex.com/helpcenter/en/dev/

The app may contain links to app store pages (for example, to leave a review, or to the developer's other apps). Such links open in an external browser or store app; any further data processing is governed by the policies of those services.

## 5. International transfers

Third-party ad providers may process data in different jurisdictions according to their policies and applicable law. If you are located in the European Union, data processing is also subject to Regulation (EU) 2016/679 (GDPR).

## 6. Retention and storage location

- Local app data remains on your device until you delete it (clear the app's data or uninstall the app). Individual projects and sessions can also be deleted inside the app.
- Android system backup (`allowBackup`) is enabled for the app, so local app data may be included in a device backup created by the operating system or by the manufacturer's cloud service. Such backups are controlled by you and by that service, not by the controller.
- Data processed by the ad network is retained under the provider's own policies.

## 7. Security

Reasonable technical and organizational safeguards are applied. Because user data is stored only on the device, its safety depends primarily on the protection of the device itself. No internet transmission or storage system can be guaranteed 100% secure. We recommend protecting access to your device.

## 8. Age restriction

The app is not intended for users under 18 years old.
If you believe a minor has provided data, contact the controller at kamchatka_lab@mail.ru.

## 9. Data subject rights

Depending on applicable law, users may have rights of access, correction, deletion, restriction, objection, and other rights.
Because app data is stored only on the device, you can delete it yourself at any time: clear the app's data in Android settings or uninstall the app.
The detailed procedure for exercising these rights is described in the "Data Subject Rights" document, available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_clicker/data_subject_rights_en.md

## 10. Applicable law and jurisdiction

This Notice is prepared in accordance with the laws of the Russian Federation. If you are located in the European Union, the GDPR (Regulation (EU) 2016/679) also applies.

## 11. Contact

For privacy/data requests:
- Email: kamchatka_lab@mail.ru
- Subject line: "Personal Data — Simple Clicker"

## 12. Changes to this Notice

This Notice may be updated. The current version is available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_clicker/privacy_policy_en.md
