# PRIVACY POLICY

**Effective Date:** January 5, 2026

## 1. Introduction
Thank you for using **Hams** ("the App"), developed by **AKK** ("we," "us," or "our"). We are committed to protecting your personal data and respecting your privacy.

This Privacy Policy explains how we collect, use, and safeguard your information. **We prioritize local storage and advanced security mechanisms to ensure maximum privacy.**

## 2. Information We Collect

### 2.1 Information Stored in the Cloud (For Service & VIP)
We only upload the minimum amount of data necessary to manage your account and subscription:
* **Account Identity (Firebase Auth):** Your **email address** and **User ID (UID)**.
* **VIP Membership Data (Firebase Firestore):**
    * VIP Status (Active/Inactive) and Level.
    * Subscription Expiration Date.
    * **Quota Counters:** We store a numeric counter (e.g., "Used 5/100 credits") to manage limits. **We do not store details of what files were downloaded.**
* **Purchase History (RevenueCat):** Transaction receipts used strictly for validating subscriptions.

### 2.2 Information Stored LOCALLY (Not Uploaded)
To protect your privacy, the following data is processed and stored **exclusively on your device** and is **NEVER uploaded** to our servers:
* **Download History:** Records of files you have downloaded (filenames, URLs, dates).
* **App Settings:** Your preferences and configurations (e.g., WiFi-only mode, resolution settings).
* **Cached Files:** Thumbnails, icons, and temporary media files.
* **Temporary Session Data:** Short-term data such as recent URL entries or back-forward navigation lists.

### 2.3 Information Collected Automatically (Ephemeral & Diagnostics)
* **Device Sensors (iOS/Android):** We access motion sensors **only** when you use the "Shake-to-Ad" feature. Data is processed in real-time and not saved.
* **Advertising Data (AdMob):** For non-VIP users, Google AdMob collects interaction data to display ads.
* **Crash Logs (Crashlytics):** We collect anonymized crash reports and performance data to help us fix bugs and improve App stability.

## 3. How We Use Your Information
We use the collected data for the following purposes:
1.  **Service Provision:** To sync your VIP status across devices (Cloud) and manage your local download tasks (Local).
2.  **Monetization (AdMob):** To display advertisements to free users. **VIP users are exempt from ad targeting.**
3.  **Privacy by Design (Decentralized Processing):**
    * We adopt a decentralized architecture. Core video processing (such as transcoding via local FFmpeg) is performed entirely on your local device.
    * **We never upload your media content to any cloud server**, physically eliminating the risk of data leakage.
4.  **Functionality:** To enable optional motion-based features via device sensors.
5.  **Stability:** To monitor App health and fix crashes.

## 4. Third-Party Services
We employ third-party companies to facilitate our Service:
* **Google Firebase (Auth, Firestore & Analytics):** User authentication and minimal state sync.
* **Google Firebase Crashlytics:** Collects anonymized crash logs and diagnostics to help us improve App stability.
* **RevenueCat:** Subscription validation and management.
* **Google AdMob:** Advertising network (Free users only).
* **Google UMP:** Privacy consent management.

## 5. Permissions
The App requests the following permissions to function:
* **Internet Access:** Required to browse the web and download files.
* **Storage / Photos:** Required to save downloaded files to your device's public storage.
* **Sensors (iOS Motion Usage):** Required for the optional "Shake-to-Ad" feature (`NSMotionUsageDescription`). This permission is not used for background tracking.

## 6. Data Security
We implement multi-layer security mechanisms to protect your data:

### 🛡️ Anti-Hijacking Login Protection
We implement a strict **Login Mode** to ensure account safety:
* **Automatic Isolation:** When accessing login pages (e.g., Google, Twitter), we automatically remove JS Bridges to prevent malicious scripts from accessing user data via injection interfaces.
* **Environment Reset:** The WebView environment is forcibly reset before and after login to prevent Cross-Site Scripting (XSS) attacks.
* **Secure Popups:** OAuth authorization uses independent, isolated WebView instances to strictly limit URL redirects and prevent phishing.

### 🧹 Comprehensive Data Erasure
We provide thorough data cleaning capabilities:
* **Full-Stack Clearing:** When you choose to clear data, we wipe not only Cookies but also LocalStorage, WebSQL, WebView caches, and HTTP authentication data.
* **Forced Disk Wiping:** We ensure that residual data in memory is immediately erased from the disk.

### 🔒 Standard Security Measures
* **Encryption:** All cloud data transmission uses **HTTPS encryption**.
* **International Transfer:** Your account information (User ID and Membership Status) may be transferred to and maintained on servers located outside of your country (e.g., US or Singapore). We ensure all transfers comply with applicable laws.

## 7. Data Retention and Deletion
* **Cloud Account:** Account info (Email/UID) is retained as long as your account is active. You may request deletion by contacting us.
* **App Private Data:** Data stored in the App's private directory (e.g., Download History database, Settings) **is automatically deleted by the Operating System** when you uninstall the App.
* **Public Media Files:** Media files (videos, images) that you have downloaded and saved to public directories (e.g., System Gallery, /Downloads folder) **are NOT deleted** by uninstalling the App. You maintain full ownership and control over these files and must delete them manually via your device's file manager.

## 8. Global Compliance (GDPR & CCPA)
* **Consent Management:** We utilize the **Google User Messaging Platform (UMP)** to strictly comply with international privacy regulations such as GDPR.
* **Regional Strategy:** We intelligently identify user regions to ensure that users in the European Economic Area (EEA) and the UK are provided with clear consent options regarding data collection and ads.
* **Right to Erasure:** You can request us to delete your cloud account. Local data is already under your full control.
* **Opt-Out:** Users can manage their ad preferences via the App settings.

## 9. Children's Privacy
The App is not intended for use by children under the age of **14**. We do not knowingly collect personally identifiable information from children under this age. If we discover such data has been collected, we will delete it immediately.

## 10. Contact Us
If you have any questions about this Privacy Policy or wish to request account deletion, please contact us at:

**Email: akk911709@gmail.com**
