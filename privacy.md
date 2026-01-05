# PRIVACY POLICY

**Effective Date:** January 5, 2026

## 1. Introduction
Thank you for using **Hams** ("the App"), developed by **QIANKUN** ("we," "us," or "our"). We are committed to protecting your personal data and respecting your privacy.

This Privacy Policy explains how we collect, use, and safeguard your information. **We prioritize local storage for your usage data to ensure maximum privacy.**

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
* **Temporary Session Data:** Short-term data such as recent URL entries or back-forward navigation lists, which are typically cleared when the specific session ends or the app is closed.

### 2.3 Information Collected Automatically (Ephemeral)
* **Device Sensors (iOS/Android):** We access motion sensors **only** when you use the "Shake-to-Ad" feature. Data is processed in real-time and not saved.
* **Advertising Data (AdMob):** For non-VIP users, Google AdMob collects interaction data to display ads.

## 3. How We Use Your Information
We use the collected data for the following purposes:
1.  **Service Provision:** To sync your VIP status across devices (Cloud) and manage your local download tasks (Local).
2.  **Monetization (AdMob):** To display advertisements to free users. **VIP users are exempt from ad targeting.**
3.  **Privacy by Design:** We intentionally architected the App so that your detailed usage habits remain on your device. We cannot see what you are downloading.
4.  **Functionality:** To enable optional motion-based features via device sensors.

## 4. Third-Party Services
We employ third-party companies to facilitate our Service:
* **Google Firebase (Auth, Firestore & Analytics):** User authentication and minimal state sync.
* **RevenueCat:** Subscription validation and management.
* **Google AdMob:** Advertising network (Free users only).
* **Google UMP:** Privacy consent management.

## 5. Permissions
The App requests the following permissions to function:
* **Internet Access:** Required to browse the web and download files.
* **Storage / Photos:** Required to save downloaded files to your device's public storage.
* **Sensors (iOS Motion Usage):** Required for the optional "Shake-to-Ad" feature (`NSMotionUsageDescription`). This permission is not used for background tracking.

## 6. Data Security
* **Encryption:** All cloud data transmission uses **HTTPS encryption**.
* **Local Isolation:** Since sensitive usage data (like download history) is stored locally, it is protected by your device's operating system security (Sandbox).
* **International Transfer:** Your account information (User ID and Membership Status) may be transferred to and maintained on servers located outside of your country (e.g., US or Singapore). We ensure all transfers comply with applicable laws.

## 7. Data Retention and Deletion
* **Cloud Account:** Account info (Email/UID) is retained as long as your account is active. You may request deletion by contacting us.
* **App Private Data:** Data stored in the App's private directory (e.g., Download History database, Settings) **is automatically deleted by the Operating System** when you uninstall the App.
* **Public Media Files:** Media files (videos, images) that you have downloaded and saved to public directories (e.g., System Gallery, /Downloads folder) **are NOT deleted** by uninstalling the App. You maintain full ownership and control over these files and must delete them manually via your device's file manager.

## 8. GDPR & CCPA Compliance
* **Right to Erasure:** You can request us to delete your cloud account. Local data is already under your full control.
* **Ad Consent:** We use Google UMP to collect consent for ad personalization where required.
* **Opt-Out:** Users can manage their ad preferences via the App settings.

## 9. Children's Privacy
The App is not intended for use by children under the age of **14**. We do not knowingly collect personally identifiable information from children under this age. If we discover such data has been collected, we will delete it immediately.

## 10. Contact Us
If you have any questions about this Privacy Policy or wish to request account deletion, please contact us at:

**Email: akk911709@gmail.com**
