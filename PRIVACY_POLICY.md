# Privacy Policy for OpenWrt Manager

**Last updated:** March 3, 2025

**OpenWrt Manager** ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application handles your information.

---

## 1. Zero Data Collection & Local Processing

**OpenWrt Manager does NOT collect, store, transmit, or share any personal or device data to external servers or third-party services.**

* **Direct Local Connection:** All communications, commands, and API requests executed by the app are sent **directly** and **exclusively** from your mobile device to your specified local router (OpenWrt) via private local network (LAN) or user-configured encrypted channels (SSH / JSON-RPC UBUS).
* **No Cloud Servers:** We do not operate any external cloud databases, analytics servers, or telemetry tracking systems.

---

## 2. Information Stored Locally on Your Device

To function properly, the application stores certain configuration settings locally on your mobile device using encrypted storage provided by the operating system:

* **Router Credentials:** IP Address, Hostname, Username, and Encrypted Passwords used to authenticate with your router.
* **App Preferences:** Language preferences, theme preferences, and user interface selections.

This information is stored strictly on your local device and is never accessible to us or any third parties.

---

## 3. Device Permissions Used

The application requests specific permissions solely for functionality required to manage your network router:

* **Network / Internet Access (`INTERNET`, `ACCESS_NETWORK_STATE`, `ACCESS_WIFI_STATE`):** Required to discover, connect to, and send UBUS/SSH management commands to your local router.
* **Biometric Authentication (`USE_BIOMETRIC`, `USE_FINGERPRINT`):** (Optional) Used locally by your device OS to unlock the app if enabled by you. Biometric data is managed entirely by Android/iOS and is never accessed by this app.
* **Notifications (`POST_NOTIFICATIONS`):** (Optional) Used to send local notifications when new devices join your network or status alerts occur.

---

## 4. Third-Party Services & Analytics

* **No Analytics:** The app does not integrate Google Analytics, Firebase Tracking, Facebook SDKs, or any other tracking tools.
* **No Advertisements:** The app contains no advertisements.

---

## 5. Data Security

Your router credentials and settings are secured using native OS-level encryption mechanisms (`EncryptedSharedPreferences` on Android / `Keychain` on iOS).

---

## 6. Children's Privacy

The application does not collect any personal information from anyone, including children under the age of 13.

---

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last updated" date.

---

## 8. Contact Us

If you have any questions or suggestions about this Privacy Policy, feel free to contact us at:

* **GitHub Issues:** [https://github.com/YOUR_GITHUB_USERNAME/openwrt_manager/issues](https://github.com/YOUR_GITHUB_USERNAME/openwrt_manager/issues)
* **Email:** your.email@domain.com
