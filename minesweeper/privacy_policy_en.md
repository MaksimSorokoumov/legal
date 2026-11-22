# Privacy Notice
## "Minesweeper" app (Huawei AppGallery)

**Effective date:** 21 Nov 2026
**Last updated:** 21 Nov 2026
**Personal data controller:** Maxim Sorokoumov
**Contact e-mail:** kamchatka_lab@mail.ru
**Controller country/address:** Russia

This Notice describes how data is processed when you use the **"Minesweeper"** mobile application (package: `com.kamchatka.minesweeper.huawei`) from Huawei AppGallery.

The app has no accounts, registration or sign-in. We do not collect your name, phone number, e-mail address or contacts. Game modes work fully offline; the network is used only for ads, analytics and the monthly player leaderboard.

## 1. What data is processed

### 1.1 Data processed locally on the device
The app stores on the user's device (via SharedPreferences):
- classic mode statistics: best times, wins and losses per difficulty;
- an unfinished classic game, to restore it after you leave;
- Survival mode progress: operation, completed levels and lines, lives, score and medals;
- Escape mode profile: coins, upgrades, boosters and level stars;
- settings: board background, sound, music, custom board size, interface language;
- the player name (a nickname you choose yourself) and a random internal player identifier;
- technical service values, e.g. the time of the last full-screen ad.

This data is used solely for the app to function. The nickname and identifier are additionally used for the leaderboard (section 1.4). Other local data is not shared with third parties.

### 1.2 Data that may be processed by a third-party ad network
The app uses the **Yandex Mobile Ads** SDK to show ads (banners, full-screen ads and rewarded ads that the user launches themselves — e.g. to call the medic in Survival).
When ads are shown, the third-party SDK may process:
- device advertising identifiers (e.g. OAID/AAID/GAID, where available);
- IP address and network parameters;
- technical device and app data;
- ad events (impressions, clicks, technical ad-delivery events).

Purposes: ad delivery, frequency capping, anti-fraud and ad performance analytics.

### 1.3 Data that may be processed by a third-party analytics SDK
The app uses the **Yandex AppMetrica** SDK for app usage statistics.
The SDK may process:
- technical device and app data (device model, OS version, app version and build, language, screen parameters);
- device identifiers used for statistics and install attribution;
- IP address and network parameters;
- anonymized app usage events and session statistics (modes opened, game outcomes, rewarded videos shown);
- technical error and crash reports.

The player name and internal player identifier are not sent to analytics.

Purposes: app usage statistics, audience and retention analytics, detection of technical errors and crashes, install statistics.

### 1.4 Data sent to the leaderboard server
For the monthly player leaderboard the app sends to the controller's server:
- a random internal player identifier (not linked to your name, account or device);
- the player name (nickname, visible to everyone in the table; do not use your real full name);
- the game result: mode and time, and for Survival also score, levels completed and blast count.

The server technically receives the device IP address — solely for abuse protection. Records older than two months are deleted automatically. Submission runs in the background when connectivity is available and does not affect gameplay.

### 1.5 Content shared at the user's initiative
The "Share" button passes only the text that the user themselves sends via a chosen app. The app does not pass this content to the controller.

### 1.6 Purchases
The Huawei AppGallery version has no purchases: there are no paid features or subscriptions in this version. Another store's purchase SDK is not used in this version.

## 2. App permissions

The app declares network access (`INTERNET`) and network state access (`ACCESS_NETWORK_STATE`) for ad loading, leaderboard submissions and technical data sent by third-party SDKs. The app does not request access to the microphone, files, photos, contacts, precise location or camera.

The store listing shows the full permission list, including technical permissions declared by third-party SDKs embedded in the app. Such permissions are used by the respective SDKs only for the purposes described in sections 1.2 and 1.3.

## 3. Legal bases for processing

Personal data is processed:
- to provide the app's functionality and services to the user (including the leaderboard table);
- on the basis of our legitimate interests in monetizing the app through ads and in measuring app usage;
- on the basis of the user's consent where required by applicable law.

By using the app you consent to data processing in accordance with this Notice.

## 4. Sharing data with third parties

We do not sell users' personal data to third parties.

Ad- and analytics-related data may be processed by third-party providers as part of SDK operation:
- **Yandex Ads (Yandex Mobile Ads SDK)**
  Yandex privacy policy: https://yandex.com/legal/confidential/
  SDK documentation: https://ads.yandex.com/helpcenter/en/dev/
- **Yandex AppMetrica (AppMetrica SDK)**
  Yandex privacy policy: https://yandex.ru/legal/confidential/
  SDK documentation: https://appmetrica.yandex.ru/docs/

Leaderboard data (section 1.4) is processed on the controller's server and is not passed to other third parties.

## 5. Cross-border transfers

Third-party ad and analytics services may process data on servers in different jurisdictions in accordance with their policies and applicable law.
If you are in the European Union, Regulation (EU) 2016/679 (GDPR) also applies to the processing.

## 6. Retention

- Local app data is kept on the device until the user deletes it (clearing app data or uninstalling the app).
- Leaderboard records on the controller's server are deleted automatically after two months.
- Data processed by the ad network and analytics service is retained under the respective provider's rules.

## 7. Security

Reasonable organizational and technical measures are applied to protect data. Transmission over the internet cannot be absolutely secure. We recommend protecting access to your device.

## 8. Children

The app is a logic puzzle game and requires no registration. Age rating: 12+. The app is not directed to children under 12.

- We do not knowingly collect children's personal data: the app does not ask for name, age or contacts and has no registration. The leaderboard nickname is chosen freely by the user.
- Device advertising identifiers and network data may be processed by the third-party ad SDK as described in section 1.2. Parents and legal guardians are advised to configure device advertising identifiers in system settings (e.g. limit ad personalization or reset the identifier) and to review app permissions where needed.
- If you believe a child has provided personal data, contact the controller at kamchatka_lab@mail.ru — we will delete it.
- Users below the digital consent age in their country (13–16 depending on jurisdiction) should use the app with the consent and under the supervision of a parent or legal guardian.

## 9. Data subject rights

Depending on applicable law, users may have the right to access, rectification, erasure, restriction of processing, objection and other rights.
The detailed procedure is described in the "Data Subject Rights" document available at: https://github.com/MaksimSorokoumov/legal/blob/main/minesweeper/data_subject_rights_en.md

## 10. Governing law and jurisdiction

This Notice is drawn up in accordance with the legislation of the Russian Federation. If you are in the European Union, GDPR (Regulation (EU) 2016/679) also applies.

## 11. Contacts

For privacy and personal data questions:
- E-mail: kamchatka_lab@mail.ru
- Subject: "Personal data — Minesweeper"

## 12. Changes to this Notice

The controller may update this Notice. The current version is available at: https://github.com/MaksimSorokoumov/legal/blob/main/minesweeper/privacy_policy_en.md