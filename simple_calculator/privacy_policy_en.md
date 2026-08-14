# Privacy Notice
## Calculator & Converter App (Huawei AppGallery)

**Effective date:** 13.08.2026
**Last updated:** 14.08.2026
**Data Controller:** Maksim Sorokoumov
**Contact email:** kamchatka_lab@mail.ru
**Controller country/address:** Russia

This Notice explains how data is processed when you use **Calculator & Converter** (package: `com.kamchatka.simple_calculator.huawei`) in Huawei AppGallery.

## 1. What data is processed

### 1.1 Data processed locally on your device
The app stores on your device:
- app settings: calculator mode, key sound and vibration, number of decimal places, interface language, selected exchange rate source;
- calculation history, including entered expressions, results, timestamps and text notes that you add to entries yourself;
- adding machine tape state: entered numbers, operators, subtotals and grand totals;
- conversion history: source and resulting values, selected units and currencies;
- a cache of the most recently downloaded currency and cryptocurrency rates, so that the converter works offline.

This data stays on your device, is used exclusively for app functionality and is not transmitted to the controller or to third parties.

### 1.2 Network requests for currency and cryptocurrency rates
To refresh exchange rates, the app queries public external data sources. The source is selected by you in the settings:
- Central Bank of Russia via the public mirror `cbr-xml-daily.ru`;
- `ExchangeRate-API` (`exchangerate-api.com`);
- `FXRatesAPI` (`api.fxratesapi.com`);
- `CoinGecko` (`coingecko.com`) — cryptocurrency rates;
- `OKX` (`okx.com`) — cryptocurrency rates.

These requests contain no personal data, no user identifiers, no entered numbers and no calculation history — only a reference rate table is requested. As with any network connection, the receiving party technically sees the device IP address and standard HTTP request parameters. Processing of that data is governed by the respective providers' policies.

### 1.3 Data that may be processed by a third-party ad network
The app uses **Yandex Mobile Ads SDK** to display ads through the Huawei AppGallery platform. The SDK ships with the **AppMetrica** analytics library (Yandex) — it is installed together with the ad SDK and is not integrated by the app separately.
When ads are served, the third-party SDK may process:
- device advertising identifiers (e.g., OAID/AAID/GAID, where available);
- IP address and network parameters;
- technical device/app data (model, OS version, app version, language, network type);
- ad events (impressions, clicks, technical delivery events);
- technical app events (launches, crashes) — on the AppMetrica side.

Purposes: ad delivery, frequency capping, anti-fraud, ad performance analytics, and technical diagnostics of the app.

## 2. App permissions

The app uses the following permissions:
- `android.permission.INTERNET` — loading ads and network requests (refreshing currency and cryptocurrency rates).

No other permissions are requested: the app does not access the camera, microphone, location, contacts, files or other sensitive data.

## 3. Legal bases

Processing is carried out:
- to provide app functionality and deliver services to you;
- based on our legitimate interests in monetizing the app through targeted advertising;
- based on user consent where required by applicable law.

By using the app, you consent to data processing as described in this Notice.

## 4. Third-party sharing

We do not sell users' personal data to third parties.

Ad-related data may be processed by third-party providers through SDK operation:
- **Yandex Ads (Yandex Mobile Ads SDK)**
  Yandex Privacy Policy: https://yandex.com/legal/confidential/
  SDK documentation: https://ads.yandex.com/helpcenter/en/dev/
- **AppMetrica (Yandex)** — analytics library bundled with Yandex Mobile Ads SDK
  Service website: https://appmetrica.yandex.com/
  Yandex Privacy Policy: https://yandex.com/legal/confidential/

The exchange rate providers listed in section 1.2 receive only technical network connection parameters and operate under their own privacy policies.

## 5. International transfers

Third-party ad providers and exchange rate providers may process data in different jurisdictions according to their policies and applicable law.
If you are located in the European Union, data processing is also subject to Regulation (EU) 2016/679 (GDPR).

## 6. Retention

- Local app data (settings, calculation and conversion history, rate cache) remains on your device until you delete it: clearing history inside the app, clearing app data in system settings, or uninstalling the app.
- Data processed by the ad network is retained under the provider's own policies.

## 7. Security

Reasonable technical and organizational safeguards are applied. No internet transmission or storage system can be guaranteed 100% secure. We recommend protecting access to your device.

## 8. Age restriction

The app is not intended for users under 18 years old.
If you believe a minor has provided data, contact the controller at kamchatka_lab@mail.ru.

## 9. Data subject rights

Depending on applicable law, users may have rights of access, correction, deletion, restriction, objection, and other rights.
The detailed procedure for exercising these rights is described in the "Data Subject Rights" document, available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_calculator/data_subject_rights_en.md

## 10. Applicable law and jurisdiction

This Notice is prepared in accordance with the laws of the Russian Federation. If you are located in the European Union, the GDPR (Regulation (EU) 2016/679) also applies.

## 11. Contact

For privacy/data requests:
- Email: kamchatka_lab@mail.ru
- Subject line: "Personal Data — Calculator & Converter"

## 12. Changes to this Notice

This Notice may be updated. The current version is available at: https://github.com/MaksimSorokoumov/legal/blob/main/simple_calculator/privacy_policy_en.md
