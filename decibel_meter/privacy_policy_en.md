# Privacy Policy
## Decibel Meter App (Шумомер)

**Effective Date:** November 1, 2026  
**Data Controller:** Maksim Sorokoumov  
**Contact Email:** kamchatka_lab@mail.ru  
**Country:** Russian Federation  
**Application Identifiers:**  
- RuStore: `com.kamchatka.dbmeter`  
- Huawei AppGallery: `com.kamchatka.dbmeter.huawei`  

This Privacy Policy explains how data is handled when you use the mobile application **"Decibel Meter"** (hereinafter referred to as the "Application").

The Application does not require user accounts, registration, or login. We do not collect or request your name, phone number, contacts, personal documents, or private identifiers.

---

## 1. What Data Is Processed

### 1.1 Data Processed Locally on Your Device
- **Microphone Audio Stream:**  
  Used exclusively in real time to calculate sound pressure levels (SPL dB), perform frequency/spectrum analysis, and detect volume threshold exceedances. All processing is performed strictly in volatile memory (RAM). **The Application does not record audio to files, does not store audio recordings, and never transmits sound over the network.**
- **Saved Measurements and History (SQLite):**  
  User-saved measurement records (dB value, timestamp, optional text note), custom alert thresholds, alert history, and night noise monitoring summaries (aggregated per-minute dB levels and peak events). All these records are stored exclusively in the local database on your device and are not uploaded to remote servers.
- **Preferences and Settings (SharedPreferences):**  
  Visual theme preference (light/dark mode), weighting filter selection (A-weighting, C-weighting, Z-flat), time weighting (Fast/Slow), microphone calibration coefficients, and ad-free mode timer.
- **Exported Reports:**  
  Generation of night noise PDF reports is performed entirely on-device at the user's explicit request.

### 1.2 Data Processed by Advertising Networks (Yandex Mobile Ads)
The Application integrates the **Yandex Mobile Ads SDK** to display in-app advertisements (banners, interstitials, and rewarded ads).
The third-party advertising SDK may collect and process:
- Advertising identifiers (GAID, OAID);
- IP address and general network parameters;
- Device model and OS version;
- Ad interaction events (impressions, clicks, dismissals).

Purposes: ad delivery, frequency capping, anti-fraud verification, and viewability analytics.  
The advertising SDK does not have access to the microphone, sound measurements, or local database records.

### 1.3 Data Processed by Analytics (AppMetrica)
The Application integrates the **Yandex AppMetrica SDK** to gather pseudonymous diagnostic and operational telemetry.
The analytics SDK may collect:
- Device hardware specifications and OS version;
- Crash and unhandled exception logs;
- Pseudonymous app usage events (screens viewed, measurement start/stop, PDF exports).

The analytics SDK does not collect personal identifiers and has no access to audio data.

---

## 2. App Permissions

- `RECORD_AUDIO` — access to the device microphone for local real-time sound level measurements. Audio is neither recorded to storage nor streamed over the network.
- `FOREGROUND_SERVICE` and `FOREGROUND_SERVICE_MICROPHONE` (Android 14+) — long-running background noise monitoring during night sessions ("Night Log") with a persistent system notification.
- `INTERNET` and `ACCESS_NETWORK_STATE` — ad loading and diagnostic crash reporting.
- `WAKE_LOCK` — keeps the CPU active during continuous overnight noise monitoring.
- `VIBRATE` — haptic feedback and alert notifications when custom sound thresholds are breached.
- `POST_NOTIFICATIONS` — displaying foreground service status and noise alert notifications.

The Application **does not access** precise geolocation, camera, address book, photos, or personal media files.

---

## 3. Legal Basis for Processing

Data is processed:
- To provide the core functionality of the Application requested by the user;
- Under legitimate interests in maintaining app stability, preventing crashes, and monetization via ad display;
- Based on user consent granted through Android runtime permission dialogs.

---

## 4. Third-Party Data Sharing

We do not sell, rent, or trade your data. Pseudonymous operational data may be processed by:
- **Yandex LLC (Yandex Mobile Ads SDK):**  
  Privacy Policy: https://yandex.com/legal/confidential/
- **Yandex LLC (AppMetrica SDK):**  
  Privacy Policy: https://yandex.com/legal/confidential/

---

## 5. Data Retention and Deletion

All user data, history, calibrations, and settings reside solely within the Application's private sandbox storage on your device.  
You can delete measurement history directly inside the Application or clear all data / uninstall the Application via standard Android system settings at any time.

---

## 6. Contact Information

For any inquiries regarding this Privacy Policy:  
**Email:** kamchatka_lab@mail.ru  
**Developer:** Maksim Sorokoumov
