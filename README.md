# Chainly-App-Privacy-Policy
# Privacy Policy for Chainly

**Effective Date:** May 17, 2026  
**Last Updated:** May 17, 2026

---

## 1. Introduction

Chainly ("**Company**," "**we**," "**us**," or "**our**") operates the Chainly mobile application (the "**App**"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App, whether accessed via mobile device or other technology.

**Company Name:** Chainly  
**Contact Email:** info@chainly.site  
**Website:** www.chainly.site 

Please read this Privacy Policy carefully. If you do not agree with our policies and practices, please do not use our App.

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

When you create an account and use the Chainly App, we collect the following personal information:

#### **Authentication & Account Information:**
- Full Name
- Email Address
- Phone Number (for Customers)
- Company Name (for Managers)
- Password (securely hashed and encrypted)

#### **Location Information:**
- Latitude and Longitude coordinates
- Physical address (street, city, country)
- Location data is collected during the sign-up process and may be updated during order tracking

#### **Profile Information:**
- Profile Picture/Avatar
- Role Selection (Manager or Customer)
- Account Settings and Preferences

#### **Order & Supply Chain Data:**
- Order details and history
- Order status and tracking information
- Supplier information
- Product information
- Demand forecasting data

### 2.2 Information Collected Through Camera & Device Features

#### **Camera & Video Recording:**
- The App requests camera permission for:
  - QR code and barcode scanning
  - Defect detection through video recording
  - Quality assurance processes
- **Video/Image Handling:** Videos and images captured for defect detection are **processed locally on your device** using TensorFlow Lite machine learning models
- **Data Retention:** Processed detection results are stored on your device; raw video files are **not retained** after analysis

#### **Device Information:**
- Device type, model, and operating system
- Device identifiers (for internal analytics purposes)
- Mobile network information

### 2.3 Information Collected Automatically

When you use the Chainly App, we automatically collect:

- **Usage Data:** Pages visited, features accessed, time spent in the App
- **Chat & Communication Data:** Messages sent through the AI ChatBot (stored **locally only** on your device, not on our servers)
- **Cached Preferences:** User preferences and app settings via local storage
- **Log Data:** Error logs, API request/response times (for debugging and service improvement)

---

## 3. How We Use Your Information

We use the collected information for the following purposes:

### 3.1 Core Service Delivery
- Account creation and management
- User authentication and authorization
- Role-based access control (Manager vs. Customer features)
- Order processing and tracking
- Demand forecasting and AI-driven insights
- Quality control and defect detection
- Supply chain management and optimization

### 3.2 Location Services
- **Mandatory Location Data:** Your location is required during registration and is used to:
  - Identify your physical business location (for Managers)
  - Enable order tracking and delivery logistics
  - Support geolocation-based features
  - Share with logistics partners for order fulfillment
- Location data may be shared with delivery partners and third-party logistics providers to facilitate order delivery and tracking

### 3.3 Service Improvement
- Analyze how users interact with the App
- Identify technical issues and bugs
- Improve App functionality and user experience
- Optimize performance and reliability

### 3.4 Communication
- Send service-related notifications (order updates, password reset, account changes)
- Respond to user inquiries and support requests
- Send important policy updates

### 3.5 Legal & Compliance
- Comply with applicable laws and regulations
- Enforce our Terms of Service
- Protect against fraud and security threats
- Respond to lawful government requests

---

## 4. Data Sharing & Third Parties

### 4.1 Information We Share

**Your information may be shared with:**

#### **Logistics & Delivery Partners:**
- Location data (latitude/longitude and physical address) is shared with logistics and delivery partners to facilitate order tracking and fulfillment
- Order details necessary for delivery operations

#### **Google Services:**
- **Google Maps API:** We use Google Maps for location-based services. Your location data may be processed by Google in accordance with Google's Privacy Policy
- Refer to [Google Privacy Policy](https://policies.google.com/privacy) for details on how Google handles your data

#### **Backend Server (Egypt):**
- All non-sensitive app usage data
- Order and supply chain information
- User profile information
- We do **NOT** share or sell your personal data to third parties for marketing purposes

### 4.2 Information We Do NOT Share

- **No Third-Party Analytics:** We do not use third-party analytics services (Firebase Analytics, Mixpanel, etc.)
- **No Marketing Partners:** We do not share data with marketing or advertising partners
- **Chat History:** Your AI ChatBot conversations are stored **locally only** and are NOT transmitted to or stored on our servers
- **No Data Sales:** We do not sell your personal data to any third parties

---

## 5. Data Security & Protection

### 5.1 Security Measures

We implement industry-standard security practices to protect your data:

#### **Authentication & Token Management:**
- **JWT Tokens:** User authentication relies on JSON Web Tokens (JWT) stored securely in your device's encrypted storage
- **Secure Storage:** Authentication tokens are stored using `flutter_secure_storage`, which leverages:
  - **Android Keystore** for Android devices
  - **iOS Keychain** for iOS devices
- **Automatic Token Refresh:** Expired tokens are automatically refreshed to maintain session security
- **Bearer Token Authentication:** All API requests include Bearer token authentication headers

#### **Data Transmission:**
- **HTTPS/TLS Encryption:** All data transmitted between your device and our backend is encrypted using HTTPS/TLS protocols
- **No Plain Text Storage:** Sensitive data (passwords, tokens, personal information) is never stored in plain text

#### **Password Security:**
- Passwords are hashed and salted using industry-standard algorithms on our backend servers
- We do not store plain-text passwords

#### **Local Data Protection:**
- Sensitive data on your device is encrypted using platform-specific security mechanisms
- Non-sensitive data is cached in `shared_preferences` with appropriate access controls

#### **Logging & Monitoring:**
- Detailed API logging is disabled in production builds for security
- Only essential error logs are retained for troubleshooting

### 5.2 Data Retention

- **Active Accounts:** Data is retained as long as your account is active
- **Deleted Accounts:** When you delete your account, we retain your data for **30 days** to comply with potential legal obligations and to prevent accidental data loss. After 30 days, data is permanently deleted
- **Chat History:** Locally stored chat history is deleted when you clear the App cache or uninstall the App
- **Location Data:** Location data is retained for order tracking purposes and deleted upon order completion (typically 30-90 days depending on delivery time)
- **Processing Data:** Defect detection analysis results are stored temporarily and deleted after order completion

---

## 6. User Rights & Data Control

### 6.1 Your Rights

You have the following rights regarding your personal data:

#### **Right to Access:**
- You can access your profile information at any time through the App
- You can view your personal information, order history, and account settings

#### **Right to Modify:**
- You can update your personal information (name, email, phone, company name) through the Profile screen
- You can change your password through the "Change Password" feature

#### **Right to Delete:**
- You can delete your account through the App's settings
- Upon account deletion, your data will be retained for 30 days and then permanently removed from our servers
- **Note:** We may retain certain data as required by law for compliance and audit purposes

#### **Right to Data Portability:**
- Contact us at info@chainly.site to request a copy of your personal data in a portable format

#### **Right to Withdraw Consent:**
- You can revoke permissions (camera, location) through your device settings
- Revoking permissions will disable related App features

### 6.2 Data Subject Requests

If you wish to exercise any of these rights, please contact us at:

**Email:** info@chainly.site

We will respond to your request within **30 days** in accordance with applicable data protection regulations.

---

## 7. Permissions & Device Access

### 7.1 Required Permissions

The Chainly App requests the following device permissions:

#### **Android Permissions:**
```
android.permission.INTERNET
android.permission.CAMERA
android.permission.ACCESS_FINE_LOCATION
android.permission.ACCESS_COARSE_LOCATION
```

#### **iOS Permissions:**
```
NSCameraUsageDescription: "Camera access is required for QR code scanning and defect detection."
NSLocationWhenInUseUsageDescription: "Location is used to attach GPS coordinates to orders and enable tracking features."
```

### 7.2 Permission Management

- All permissions are requested at runtime when the relevant feature is used
- You can manage permissions through your device settings (Settings > Apps > Chainly)
- Denying permissions will disable related features (e.g., denying camera access disables barcode scanning)
- Location permission is **mandatory** to complete account registration

---

## 8. Children's Privacy

The Chainly App is designed for business users (Managers and Customers) and is **not intended for children under 13 years old**. We do not knowingly collect personal information from children under 13.

If we become aware that a child under 13 has provided us with personal information, we will delete such information promptly and terminate the child's account.

---

## 9. Data Processing & GDPR Compliance

### 9.1 Legal Basis for Processing

We process your personal data based on:
- **Contractual Necessity:** Processing required to provide the App services
- **Legal Obligation:** Compliance with applicable laws and regulations
- **Legitimate Interests:** Business operations and service improvement
- **Consent:** You have explicitly consented to specific processing activities

### 9.2 International Data Transfers

Our backend servers are located in **Egypt**. If you are accessing the App from a country with data protection laws (such as the EU under GDPR), your data will be transferred to Egypt for processing.

**Data Transfer Mechanism:** We implement appropriate safeguards including:
- Encryption during transmission
- Secure authentication protocols
- Limited access controls on the backend

By using the Chainly App, you consent to the transfer of your personal data to Egypt.

### 9.3 GDPR Compliance (for EU Users)

If you are subject to GDPR:
- You have the right to request access, correction, deletion, or portability of your data
- You have the right to withdraw consent at any time
- You have the right to lodge a complaint with your local data protection authority
- Contact us at info@chainly.site for GDPR-related requests

---

## 10. Cookies & Tracking Technologies

### 10.1 Local Storage & Preferences

The Chainly App uses local storage mechanisms to enhance your experience:

- **shared_preferences:** Stores non-sensitive app preferences (theme, language, cached user name)
- **flutter_secure_storage:** Stores sensitive authentication tokens and credentials with platform-level encryption

### 10.2 Tracking

- We do **NOT** use third-party cookies, web beacons, or pixel tracking
- We do **NOT** use external analytics services (Firebase Analytics, Mixpanel, etc.)
- We do **NOT** track your behavior across other apps or websites
- Limited device-level metrics are collected for service improvement purposes only

---

## 11. Third-Party Links & Services

The Chainly App may contain links to third-party websites and services (such as Google Maps). We are **not responsible** for the privacy practices of these third parties.

Please review the privacy policies of any third-party services before providing them with your information:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Maps Privacy & Security](https://policies.google.com/privacy)

---

## 12. Updates to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our practices, technology, legal requirements, or other factors. We will notify you of material changes by:
- Posting the updated Privacy Policy in the App
- Updating the "Effective Date" and "Last Updated" at the top of this document
- Sending you an email notification (if applicable)

Your continued use of the App following the posting of revised Privacy Policy means you accept and agree to the changes.

---

## 13. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or our privacy practices, please contact us at:

**Company Name:** Chainly  
**Email:** info@chainly.site  
**Backend Location:** Egypt

We will respond to your inquiry within **30 days** of receipt.

---

## 14. Specific Feature Privacy Notes

### 14.1 Authentication & Sign-Up
- Your email and password are encrypted during transmission and hashed on our backend
- Role selection (Manager/Customer) determines which personal information is collected (company name for Managers, phone for Customers)
- Your location coordinates are required for account registration and are used to identify your business location

### 14.2 Order Tracking & Management
- Order details and tracking information are stored on our backend servers
- Location data is shared with logistics partners for order delivery
- Order history is retained for your account records

### 14.3 Demand Forecasting (Manager Feature)
- Your product and sales data is analyzed using AI models
- Forecasting insights are generated and displayed in your dashboard
- Historical data is retained for trend analysis and reporting

### 14.4 Quality Control & Defect Detection (Manager Feature)
- Camera access is used for video recording of production lines
- Videos are processed **locally on your device** using TensorFlow Lite models
- Detection results are stored locally and on your backend account for records
- Raw video files are **not retained** after processing

### 14.5 AI ChatBot (All Users)
- Chat messages are stored **locally only** on your device
- Messages are **NOT** transmitted to our servers or any third-party AI service
- Your chat history is deleted when you clear App cache or uninstall the App
- No conversation data is used for training purposes

### 14.6 Barcode & QR Code Scanning (Manager Feature)
- Camera is used for scanning barcodes and QR codes
- Scanned data is processed locally
- Scan history is retained on your device and backend for order management

---

## 15. Data Protection Officer & Compliance

While we are based in Egypt, we are committed to protecting your privacy in accordance with international data protection standards. Our data handling practices adhere to:
- Industry-standard security protocols
- Best practices for mobile app data privacy
- Applicable data protection regulations

For compliance inquiries or data protection concerns, contact: **info@chainly.site**

---

## 16. Acknowledgment

By using the Chainly App, you acknowledge that you have read, understood, and agree to this Privacy Policy. If you do not agree with our privacy practices, please do not use the App.

---

**© 2026 Chainly. All Rights Reserved.**

---

## Appendix: Data Flow Summary

| Data Type | Collection Method | Storage Location | Sharing | Retention |
|-----------|-------------------|------------------|---------|-----------|
| **Name, Email, Password** | User Input | Backend (Egypt) + Device (Encrypted) | No | Account Active + 30 Days |
| **Phone Number** | User Input (Customers) | Backend (Egypt) + Device | No | Account Active + 30 Days |
| **Company Name** | User Input (Managers) | Backend (Egypt) + Device | No | Account Active + 30 Days |
| **Location (GPS)** | Automatic (Mandatory) | Backend (Egypt) + Device | Yes (Logistics Partners) | 30-90 Days (Order Duration) |
| **Profile Picture** | User Upload | Backend (Egypt) + Device | No | Account Active + 30 Days |
| **Order Data** | User Input/API | Backend (Egypt) | Yes (Logistics Partners) | Indefinite |
| **Chat Messages** | User Input | Device Only | No | Until Manual Deletion |
| **Defect Detection Videos** | Camera Recording | Device (Temporary) + Backend (Results) | No | Order Completion |
| **QR/Barcode Scans** | Camera Scan | Device + Backend | No | Indefinite |
| **App Preferences** | User Settings | Device (shared_preferences) | No | Until App Uninstall |
| **Auth Tokens** | System Generated | Device (Secure Storage) | No | Token Expiry |

---
