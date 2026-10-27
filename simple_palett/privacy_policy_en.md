# Privacy Notice
## "Palettica: Palette & Gradient" app (RuStore, Huawei AppGallery)

**Effective date:** 28.10.2026
**Last updated:** 28.10.2026
**Data controller:** Maxim Sorokoumov
**Contact e-mail:** kamchatka_lab@mail.ru
**Country/address of the controller:** Russia

This Notice describes how data is processed when you use the mobile app **"Palettica: Palette & Gradient"** (packages: `com.kamchatka.palettica` — RuStore, `com.kamchatka.palettica.huawei` — Huawei AppGallery).

The app has no accounts, sign-up or login. We do not collect your name, phone number, e-mail address or contacts. The core features (palettes, color wheel, gradients, contrast checker, lux meter) work offline.

## 1. What data is processed

### 1.1 Data processed locally on the device
The app stores on the user's device (via Hive and SharedPreferences):
- created palettes, colors, tags and their order;
- favorite Design Lab sets and app settings (language, theme);
- launch and export counters and the expiry dates of ad rewards (used to limit ad frequency and to keep unlocked features).

This data is used only to operate the app and is not sent to the controller or third parties. It is deleted when you clear the app's data or uninstall the app.

### 1.2 Camera and light sensor
- The **camera** (`CAMERA`) is used in real time only: to detect a color through the viewfinder and as a fallback mode of the lux meter. The app does not take photos, does not record video or audio, and does not store or transmit frames.
- The **light sensor** is used to show illuminance in lux; the values are not stored or transmitted.
- For "Color from photo", the image is chosen through the Android system file picker; the app does not scan the device's files and processes the chosen image on the device only.

### 1.3 Data that may be processed by a third-party ad network
The app uses the **Yandex Mobile Ads** SDK: interstitial ads after an export or "Share" and rewarded ads that the user starts personally (to unlock export, palette copying and extra fonts). The app has no banners.
When ads are shown, the SDK may process:
- device advertising identifiers (for example OAID/AAID/GAID, where available);
- IP address and network parameters;
- technical data about the device and the app;
- ad events (impressions, clicks, technical delivery events).

Purposes: showing ads, frequency capping, anti-fraud and ad performance analytics.

### 1.4 Data that may be processed by a third-party analytics SDK
The app uses the **Yandex AppMetrica** SDK. The SDK may process:
- technical data about the device and the app (model, OS version, app version and build, language, screen parameters);
- device identifiers for statistics and install attribution;
- IP address and network parameters;
- anonymized usage events and session statistics;
- technical error and crash reports.

Purposes: usage statistics, detecting errors and crashes, install statistics.

### 1.5 Google Fonts
In Design Lab, fonts are loaded from the internet from Google Fonts servers. As with any web server, Google's server receives the device's IP address and technical details of the request. The app sends no other data to Google. Google's policy: https://policies.google.com/privacy

### 1.6 Content shared at the user's initiative
The "Share" and export buttons pass on only the text or file that the user sends through the app they choose. The app does not send this content to the controller.

## 2. App permissions

- `CAMERA` — color detection and the lux meter fallback (see 1.2); the app also works without the camera.
- `INTERNET`, `ACCESS_NETWORK_STATE` — loading ads, sending technical data by third-party SDKs, loading Design Lab fonts.

The store listing shows the full list of permissions, including technical permissions declared by the embedded third-party SDKs. These SDKs use them only for the purposes described in sections 1.3 and 1.4.

## 3. Legal bases for processing

Personal data is processed:
- to provide the app's functionality and services to the user;
- on the basis of our legitimate interests in monetizing the app through ads and in measuring app usage;
- on the basis of the user's consent, where required by applicable law.

By using the app, you consent to the processing of data in accordance with this Notice.

## 4. Sharing data with third parties

We do not sell users' personal data to third parties.

Data related to advertising, analytics and fonts may be processed by third-party providers:
- **Yandex Ads (Yandex Mobile Ads SDK)**
  Yandex privacy policy: https://yandex.com/legal/confidential/
  SDK documentation: https://ads.yandex.com/helpcenter/en/dev/
- **Yandex AppMetrica (AppMetrica SDK)**
  Yandex privacy policy: https://yandex.ru/legal/confidential/
  SDK documentation: https://appmetrica.yandex.ru/docs/
- **Google Fonts** — font loading (see 1.5): https://policies.google.com/privacy

## 5. Cross-border transfers

Third-party advertising and analytics services may process data on servers in different jurisdictions in accordance with their policies and applicable law.
If you are in the European Union, data processing is also subject to Regulation (EU) 2016/679 (GDPR).

## 6. Retention

- Local app data is stored on the device until the user deletes it (by clearing the app's data or uninstalling the app).
- Data processed by the ad network, the analytics service and Google Fonts is retained under the rules of the respective provider.

## 7. Security

Reasonable organizational and technical measures are used to protect data. Transmission over the internet cannot be completely secure. We recommend protecting access to your device.

## 8. Children

The app is not directed at children and does not knowingly collect children's personal data: it does not ask for a name, age or contacts and has no registration.

- Device advertising identifiers and network data may be processed by the third-party advertising SDK as described in section 1.3. Parents and legal guardians are advised to configure advertising identifiers in the device's system settings (limit ad personalization or reset the identifier).
- If you believe a child has provided personal data, contact the controller at kamchatka_lab@mail.ru and we will delete it.
- Users under the age of digital consent in their country (13–16 depending on jurisdiction) should use the app with the consent of a parent or legal guardian.

## 9. Data subject rights

Depending on applicable law, the user may have the right of access, rectification, erasure, restriction of processing, objection and other rights.
The procedure is described in the document "Data Subject Rights": https://github.com/MaksimSorokoumov/legal/blob/main/simple_palett/data_subject_rights_en.md

## 10. Governing law and jurisdiction

This Notice is drawn up in accordance with the laws of the Russian Federation. If you are in the European Union, the GDPR (Regulation (EU) 2016/679) also applies.

## 11. Contact

For privacy and personal data matters:
- E-mail: kamchatka_lab@mail.ru
- Subject line: "Personal data — Palettica"

## 12. Changes to this Notice

The controller may update this Notice. The current version is available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_palett/privacy_policy_en.md
