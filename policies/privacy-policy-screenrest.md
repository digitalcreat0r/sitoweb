---
layout: document
title: Privacy Policy - ScreenRest
back_url: /screenrest
back_text: Back to ScreenRest
---
# Privacy Policy - ScreenRest

*Last updated: May 15, 2026*

**ScreenRest** is an application developed and managed by **Oleksandr Bihansky** ("I"), operating as **CleverPocket**. It is built with a "Privacy by Design" approach: I believe your data belongs to you. This application is designed to function primarily on your device while maintaining high standards for technical stability and privacy.

## 1. Data Controller
The data controller for this application is:
**Oleksandr Bihansky (CleverPocket)**
Email: {{ site.email }}
Website: {{ site.url }}

## 2. Information Collection
I do **not** collect, store, or process any personal information such as names, email addresses, or phone numbers.

### Diagnostics & Crash Reporting (Opt-In)
To help me improve app stability, I use **Firebase Crashlytics**. By default, automatic crash reporting is disabled.

If the app experiences a crash, it will generate a local log on your device. Upon your next launch, you will be presented with a prompt asking for your explicit consent to send this specific crash report.
- **If you choose "Send":** The app will transmit the anonymous report to Firebase.
- **If you choose "Don't Send":** The local report is permanently deleted from your device and no data is transmitted.

The anonymous report, only if explicitly sent by you, includes:
- **Crashlytics Installation UUID:** A randomly generated, anonymous identifier.
- **Stack traces:** Technical logs indicating exactly where the code failed.
- **Device Metadata:** Hardware model, operating system version, and the state of the app at the time of the crash.

## 3. Local Storage & Permissions
The app uses **Android Jetpack DataStore** to save your preferences locally. These remain on your device and are never uploaded to any external server.

### Permissions Used
- **Exact Alarms:** Used to trigger precise wellness timers.
- **Notifications:** Used to provide status updates and reminders.
- **Vibration:** Used for haptic feedback.

## 4. Compliance & Rights
In accordance with GDPR and international privacy laws, you have full control over your data. Since all operational data is stored locally, you can exercise your right to erasure at any time by clearing the app's data or uninstalling the application. Furthermore, crash logs are strictly opt-in and are only transmitted with your explicit, per-crash consent.

## 5. Contact Information
If you have any questions regarding your privacy, please contact me at: **{{ site.email }}**