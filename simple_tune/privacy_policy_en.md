# Privacy Notice
## Simple Tune App (Huawei AppGallery)

**Effective date:** 01.03.2026
**Last updated:** 27.09.2026
**Data Controller:** Maksim Sorokoumov
**Contact email:** kamchatka_lab@mail.ru
**Controller country/address:** Russia

This Notice explains how data is processed when you use **Simple Tune** (package: `com.kamchatka.simpletune.huawei`) in Huawei AppGallery.

The app has no user accounts, no registration and no sign-in. We do not collect your name, phone number, e-mail address or contact list.

## 1. What data is processed

### 1.1 Data processed locally on your device
The app stores on your device:
- selected instrument, tuning, mode and string (via SharedPreferences);
- pitch settings: A4 reference frequency and temperament (via SharedPreferences);
- app preferences: theme, interface language, tuning hints and sound/glow options;
- technical service values, such as the timestamp of the last fullscreen ad.

This data is used exclusively for app functionality and is not transmitted to third parties.

### 1.2 Data that may be processed by the third-party ad network
The app uses **Yandex Mobile Ads SDK** to display ads through the Huawei AppGallery platform.
When ads are served, the third-party SDK may process:
- device advertising identifiers (e.g., OAID/AAID/GAID, where available);
- IP address and network parameters;
- technical device/app data;
- ad events (impressions, clicks, technical delivery events).

Purposes: ad delivery, frequency capping, anti-fraud, and ad performance analytics.

### 1.3 Data that may be processed by the third-party analytics SDK
The app uses **Yandex AppMetrica SDK** for app usage statistics.
The SDK may process:
- device and app technical data (device model, OS version, app version and build, language, screen parameters);
- device identifiers used for statistics and app-install attribution;
- IP address and network parameters;
- app usage events and session statistics (screens opened, features used, app launches);
- technical error and failure reports.

Purposes: app usage statistics, audience and retention analytics, identification of technical errors and crashes, and app-install statistics.
The SDK does not receive the content of your audio input: the microphone stream is processed on the device to determine the pitch and is not stored or transmitted.

## 2. App permissions

The app itself uses the following permissions:
- `INTERNET` and `ACCESS_NETWORK_STATE` — loading ads and network requests;
- `RECORD_AUDIO` — audio recording for pitch detection (tuner);
- `MODIFY_AUDIO_SETTINGS` — modifying audio settings for synthesizer playback.

The store listing shows the complete list of permissions, including technical permissions declared by the third-party SDKs integrated into the app. Such permissions are used by those SDKs only for the purposes described in Sections 1.2 and 1.3 (ad delivery, frequency capping, anti-fraud, analytics).

The app does not access files, photos, contacts, precise location or the device camera, and does not keep audio recordings.

## 3. Legal bases

Processing is carried out:
- to provide app functionality and deliver services to you;
- based on our legitimate interests in monetizing the app through advertising and in measuring app usage;
- based on user consent where required by applicable law.

By using the app, you consent to data processing as described in this Notice.

## 4. Third-party sharing

We do not sell users' personal data to third parties.

Ad- and analytics-related data may be processed by third-party providers through SDK operation:
- **Yandex Ads (Yandex Mobile Ads SDK)**
  Yandex Privacy Policy: https://yandex.com/legal/confidential/
  SDK documentation: https://ads.yandex.com/helpcenter/en/dev/
- **Yandex AppMetrica (AppMetrica SDK)**
  Yandex Privacy Policy: https://yandex.ru/legal/confidential/
  SDK documentation: https://appmetrica.yandex.ru/docs/

## 5. International transfers

Third-party ad and analytics providers may process data in different jurisdictions according to their policies and applicable law.
If you are located in the European Union, data processing is also subject to Regulation (EU) 2016/679 (GDPR).

## 6. Retention

- Local app data remains on your device until you delete app data or uninstall the app.
- Data processed by the ad network and the analytics service is retained under the respective provider's own policies.

## 7. Security

Reasonable technical and organizational safeguards are applied. No internet transmission or storage system can be guaranteed 100% secure. We recommend protecting access to your device.

## 8. Age rating and children

- Age rating in Huawei AppGallery: **12+**.
- The app does not knowingly collect personal data from children. If you believe that a child has provided personal data, contact the controller at kamchatka_lab@mail.ru and we will delete it.
- Users below the age of digital consent in their jurisdiction (13–16 years, depending on the country) should use the app with the consent of a parent or legal guardian.

## 9. Data subject rights

Depending on applicable law, users may have rights of access, correction, deletion, restriction, objection, and other rights.
The detailed procedure for exercising these rights is described in the "Data Subject Rights" document, available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_tune/data_subject_rights_en.md

## 10. Applicable law and jurisdiction

This Notice is prepared in accordance with the laws of the Russian Federation. If you are located in the European Union, the GDPR (Regulation (EU) 2016/679) also applies.

## 11. Contact

For privacy/data requests:
- Email: kamchatka_lab@mail.ru
- Subject line: "Personal Data — Simple Tune"

## 12. Changes to this Notice

This Notice may be updated. The current version is available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_tune/privacy_policy_en.md
