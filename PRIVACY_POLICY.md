# Privacy Policy & Data Deletion Instructions for Synthesis

**Effective Date:** September 3, 2026

## 1. Introduction
Synthesis ("we", "our", or "us") is committed to protecting your privacy. This document describes how your information is handled and how you can request or perform data deletion when using the Synthesis mobile application (the "App").

## 2. Data Collection and Usage
Synthesis is designed as an offline-first industrial management application for production reporting, asphalt mixture statistics, fuel refills, and laboratory mixture tracking.

- **Account & Cloud Sync:** Basic profile information (e.g., email, secure authentication tokens) is managed securely via Cloud services (Firebase). 
- **Offline Mode:** You can opt to use the App in a strictly Offline Mode from the Settings. In Offline Mode, no data is synced, and features relying on Cloud services (like AI OCR) are disabled, keeping all operations entirely local.
- **Local Storage:** Production reports, mixture recipes, material quantities, fuel logs, and site information are stored locally on your device using a secure SQLite database.
- **Biometric Data:** If you enable App Lock, biometric authentication (Fingerprint or Face ID) is processed entirely on-device by your Operating System's native security APIs (`local_auth`). We do not collect, transmit, or store your biometric data.
- **Camera and Storage Access:** The App may request access to your device camera or media storage solely for scanning documents/QR codes or exporting production reports (PDF/Excel files). Photos sent for OCR scanning are processed ephemerally and are not stored long-term on any server.

## 3. Data Protection and Third-Party Sharing
- **No Third-Party Tracking:** We do not track your activity across other apps or websites.
- **No Data Selling:** We do not sell, trade, or share your data with any third parties.
- **Data Transfers:** Your data remains strictly on your local device unless you explicitly choose to export reports or back up your database file.

## 4. User Data Deletion Instructions
Since Synthesis stores your data locally on your mobile device, you have total control over your data deletion:

### A. In-App Deletion (Full Wipe)
- **Account Deletion:** You have the right to permanently delete your account directly from the App's Account Settings. Performing an account deletion triggers a **Full Wipe**, which securely and irreversibly erases all your data from both your local device (SQLite databases) and our Cloud servers (Firebase).
- **Clear App Cache/Data:** Alternatively, you can clear app data via Android Device Settings -> Apps -> Synthesis -> Storage -> Clear Data. This will delete all local data, but it will not delete your Cloud account. To completely erase your presence, please use the in-app Account Deletion feature.

### B. Request Data Deletion Assistance
If you require assistance or have questions regarding data deletion:
- **Email Request:** Send an email to **kwstas147@gmail.com** with the subject line "Synthesis Data Deletion Request".
- **Processing:** Since no user data is maintained on external servers, we will guide you on confirming full local deletion or assist with any inquiries within 48 hours.

## 5. Security
We take reasonable security measures to protect your information locally. App authentication tokens and keys are secured using Android Encrypted Shared Preferences / KeyStore.

## 6. Children's Privacy
Our App is intended for professional use and does not knowingly target or collect personal information from children under 13.

## 7. Contact Us
If you have any questions or suggestions regarding this policy, please contact us at:
- **Email:** kwstas147@gmail.com
