# Privacy Policy

**Last Updated: March 30, 2026**

**Effective Date: March 30, 2026**

Hasan Balki ("we," "our," or "us") operates HitThePan (the "App"), a beauty product tracking application available on Apple's App Store. This Privacy Policy is available at https://hitthepan.com/privacy. Your use of the App is also governed by our Terms of Service, available at https://hitthepan.com/terms.

This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use the App. By downloading, installing, or using the App, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with the terms of this Privacy Policy, please do not access or use the App.

---

## 1. Information We Collect

### 1.1 Information You Provide Directly

**Account Information**
- Display name
- Email address (provided through Apple Sign-In or Google Sign-In)
- Username (optional, for social features)
- Profile avatar photo (optional)

**Product Data**
- Product names, brands, categories, and shades
- Usage counts and tracking goals
- Purchase dates and prices
- Product photos (optional)
- Repurchase verdicts

**Financial Tracking Data**
- Saved purchase records (product name, brand, amount, reason)
- Dream reward goals (name, target amount)

**Diary Entries**
- Text notes associated with products
- Diary photos

**Routine Data**
- Custom routine names and associated products

**Social Interactions**
- Friend requests and connections
- User reports (including reason text)
- Block actions

### 1.2 Information Collected Automatically

**Analytics Data (With Your Consent)**
- App usage events (e.g., screens viewed, features used, products added)
- Device type and operating system version
- App version
- Subscription status (premium or free)

**Crash and Performance Data (With Your Consent)**
- Crash reports including stack traces
- App performance metrics
- Error context information

**Device Identifiers**
- Unique user identifier (UUID) generated at account creation
- No advertising identifiers are collected

### 1.3 Information We Do NOT Collect

- We do not collect precise geolocation data
- We do not collect contacts or address book data
- We do not collect browsing history
- We do not collect health or fitness data
- We do not collect financial or payment card information (all payments are processed by Apple through the App Store)
- We do not use advertising identifiers or track users across apps

---

## 2. How We Use Your Information

We use the information we collect for the following purposes:

| Purpose | Legal Basis (GDPR) |
|---------|-------------------|
| Provide and maintain the App's core functionality | Performance of contract |
| Create and manage your account | Performance of contract |
| Sync your data across sessions | Performance of contract |
| Process subscription purchases (via Apple) | Performance of contract |
| Enable social features (friends, leaderboard) | Performance of contract |
| Send local notification reminders (with permission) | Consent |
| Analyze app usage to improve features | Consent |
| Diagnose crashes and fix bugs | Consent |
| Respond to user reports and enforce community standards | Legitimate interest |
| Comply with legal obligations | Legal obligation |

---

## 3. Third-Party Services

We use the following third-party services to operate the App:

### 3.1 Supabase (Database & Authentication)

- **Purpose:** Cloud database, user authentication, and real-time data synchronization
- **Data processed:** All user-generated content, account information, social connections
- **Data location:** Supabase infrastructure (AWS)
- **Privacy policy:** https://supabase.com/privacy

### 3.2 Firebase by Google

**Firebase Analytics**
- **Purpose:** Anonymous app usage analytics (only with your consent)
- **Data processed:** Usage events, screen views, device type, app version
- **Data retention:** 14 months (Google default)
- **Privacy policy:** https://firebase.google.com/support/privacy

**Firebase Crashlytics**
- **Purpose:** Crash reporting and stability monitoring (only with your consent)
- **Data processed:** Crash logs, stack traces, device information, user ID, subscription status
- **Data retention:** 90 days

**Firebase Remote Config**
- **Purpose:** Feature configuration and A/B testing
- **Data processed:** Device metadata for targeting (no personal data)

### 3.3 RevenueCat

- **Purpose:** Subscription management and entitlement verification
- **Data processed:** User identifier, subscription status, purchase events
- **Data location:** RevenueCat infrastructure
- **Privacy policy:** https://www.revenuecat.com/privacy

### 3.4 Apple Sign-In

- **Purpose:** User authentication
- **Data processed:** Name, email address (may be relayed/hidden per user preference)
- **Privacy policy:** https://www.apple.com/legal/privacy/

### 3.5 Google Sign-In

- **Purpose:** User authentication
- **Data processed:** Name, email address, profile identifier
- **Privacy policy:** https://policies.google.com/privacy

### 3.6 Open Beauty Facts

- **Purpose:** Product barcode lookup (optional feature)
- **Data processed:** Barcode numbers only; no personal data is sent
- **Privacy policy:** https://world.openbeautyfacts.org/terms-of-use

---

## 4. Data Storage and Security

### 4.1 Where Your Data Is Stored

| Storage Location | Data Types | Encryption |
|-----------------|------------|------------|
| Supabase (Cloud) | Account data, products, usage logs, diary text, social data, purchases, dreams, badges, routines | Encrypted in transit (TLS) and at rest |
| Device — CoreData | Diary photos and thumbnails | iOS file protection (NSFileProtectionComplete) |
| Device — File System | Product images, dream images, avatar photo | iOS file protection |
| Device — Keychain | Authentication tokens, user ID | iOS Keychain encryption (hardware-backed) |
| Device — UserDefaults | Preferences (dark mode, reminders, consent) | Standard iOS protection |

### 4.2 Security Measures

- All network communication uses HTTPS/TLS encryption
- Authentication tokens are stored in the iOS Keychain with `.whenUnlockedThisDeviceOnly` accessibility
- Local database files use iOS file protection (complete encryption when device is locked)
- Row-Level Security (RLS) policies ensure users can only access their own data on our backend
- API rate limiting prevents abuse (120 requests/minute general, 30 requests/minute for write operations)
- A privacy screen (blur overlay) is applied when the app moves to the background to protect visible content

### 4.3 Data Retention

- **Account data:** Retained until you delete your account
- **Product and usage data:** Retained until you delete the specific item or your account
- **Analytics data:** 14 months (Firebase default), collected only with your consent
- **Crash reports:** 90 days (Firebase Crashlytics default), collected only with your consent
- **User reports:** Retained for up to 2 years from the date of submission, or longer if required for ongoing investigations or legal proceedings
- **Temporary export files:** Deleted automatically after download

---

## 5. Your Rights and Choices

### 5.1 Analytics Consent

When you first open the App, you will be asked whether to allow anonymous analytics. You can:
- **Allow** analytics to help us improve the App
- **Deny** analytics to prevent any usage data from being collected

If denied, Firebase Analytics and Crashlytics are fully disabled. You can withdraw or change your analytics consent at any time through the Analytics toggle in **Profile > Preferences**, which re-displays the consent prompt. Withdrawing consent is as easy as giving it, in accordance with GDPR Article 7(3).

### 5.2 Notification Preferences

You can enable or disable daily reminder notifications in the App's settings. These are local notifications only; we do not send remote push notifications.

### 5.3 Data Portability (GDPR Article 20)

You can export all your data at any time through the App:
- Navigate to **Profile > Export Data**
- A CSV file is generated containing your profile, products, usage logs, saved purchases, dream rewards, and badge progress
- Save the file to your preferred location

### 5.4 Account Deletion (GDPR Article 17)

You can permanently delete your account and all associated data:
- Navigate to **Profile > Delete Account**
- Confirm deletion through a two-step confirmation process
- All data is permanently erased from our servers and your device, including:
  - All products, usage logs, diary entries, and photos
  - All social connections and reports
  - All saved purchases and dream rewards
  - Your authentication record
  - All local files, cached data, and preferences

This action is irreversible. Once deleted, your data cannot be recovered.

### 5.5 Data Reset

You can reset all your content data without deleting your account through **Profile > Reset Data**. This removes all products, logs, and content while preserving your account.

### 5.6 Rights Under GDPR (EU/EEA Users)

If you are located in the European Union or European Economic Area, you have the following rights:

- **Right of access** — Request a copy of all personal data we hold about you
- **Right to rectification** — Update or correct your personal data through the App
- **Right to erasure** — Delete your account and all associated data
- **Right to data portability** — Export your data in CSV format
- **Right to restrict processing** — Deny analytics consent to limit data processing
- **Right to object** — Object to processing based on legitimate interests
- **Right to withdraw consent** — Withdraw analytics consent at any time

To exercise any of these rights, contact us at **contact@hitthepan.com**.

### 5.7 Rights Under CCPA/CPRA (California Users)

If you are a California resident, you have the right to:

- **Right to Know** — Request disclosure of the categories and specific pieces of personal information we collect, the sources from which it is collected, the business purpose for collection, and the categories of third parties with whom it is shared
- **Right to Delete** — Request deletion of your personal information
- **Right to Correct** — Request correction of inaccurate personal information
- **Right to Opt-Out of Sale/Sharing** — We do not sell your personal information and do not share it for cross-context behavioral advertising. Therefore, no opt-out is required; however, you may contact us at **contact@hitthepan.com** to confirm this at any time
- **Right to Non-Discrimination** — We will not discriminate against you for exercising your privacy rights

**Categories of Personal Information Collected (per CCPA § 1798.140):**

| CCPA Category | Examples | Business Purpose |
|---------------|----------|-----------------|
| Identifiers | Name, email, user ID, username | Account management |
| Commercial Information | Purchase records, subscription status | Service delivery |
| Internet/Electronic Activity | App usage events, screens viewed | Analytics (with consent) |
| Geolocation Data | Not collected | N/A |
| Audio/Visual | Product photos, avatar | App functionality |

We do not sell personal information. We do not share personal information for cross-context behavioral advertising as defined under the California Privacy Rights Act (CPRA).

### 5.8 Rights Under LGPD (Brazilian Users)

If you are located in Brazil, you have rights under the Lei Geral de Proteção de Dados (LGPD), including:

- **Confirmation and access** — Confirm whether we process your data and request access
- **Correction** — Request correction of incomplete, inaccurate, or outdated data
- **Anonymization, blocking, or deletion** — Request anonymization or deletion of unnecessary or excessive data
- **Data portability** — Request portability of your data (available via the App's Export Data feature)
- **Deletion** — Request deletion of data processed with your consent
- **Information about sharing** — Request information about third parties with whom we share your data
- **Consent withdrawal** — Withdraw consent at any time

**Legal bases for processing under LGPD:** Performance of contract (Art. 7, V) for core app functionality; consent (Art. 7, I) for analytics and crash reporting; legitimate interest (Art. 7, IX) for moderation and community safety.

Contact us at **contact@hitthepan.com** to exercise these rights.

### 5.9 Rights Under KVKK (Turkish Users)

If you are located in Turkey, you have rights under the Kişisel Verilerin Korunması Kanunu (KVKK), including the right to learn whether your personal data has been processed, to request information about processing, to learn the purpose of processing, to know third parties to whom data is transferred, to request rectification, and to request deletion. Contact us at **contact@hitthepan.com**.

**Data Controller:** Hasan Balki, Istanbul, Turkey.

---

## 6. Children's Privacy

The App is not directed to children under the age of 13 (or the applicable age in your jurisdiction). We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided us with personal information, please contact us at **contact@hitthepan.com**, and we will take steps to delete such information.

---

## 7. Social Features and Public Information

### 7.1 Public Profiles

If you enable a public profile, the following information may be visible to other users:
- Display name
- Username
- Avatar photo
- Product statistics (aggregated, not individual products)

You can disable your public profile at any time through **Profile > Account > Public Profile**.

### 7.2 Friend Connections

When you connect with friends, they can view your public profile information and leaderboard rankings. You can remove friends, block users, or report inappropriate behavior at any time.

### 7.3 Reporting and Blocking

When you report a user, your report (including the reason you provide) is stored for moderation purposes. When you block a user, that user can no longer see your profile, send friend requests, or interact with you. Reports are reviewed to maintain community safety.

---

## 8. International Data Transfers

Your data may be transferred to and processed in countries outside your country of residence, including the United States, where our third-party service providers (Supabase, Firebase, RevenueCat) operate their infrastructure. These transfers are conducted in compliance with applicable data protection laws, including through the use of Standard Contractual Clauses (SCCs) where required by GDPR.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make material changes, we will:
- Update the "Last Updated" date at the top of this policy
- Notify you through the App or other appropriate means

Your continued use of the App after any changes constitutes your acceptance of the updated Privacy Policy.

---

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Email:** contact@hitthepan.com

**Response Time:** We aim to respond to all privacy-related inquiries within 30 days.

For GDPR-related requests, you also have the right to lodge a complaint with your local data protection authority.

---

## 11. Supplementary Technical Information

### 11.1 API Usage Declarations

As required by Apple, the App declares usage of the following system APIs in its privacy manifest:
- **UserDefaults** — For storing user preferences and app settings
- **File Timestamp** — For managing cached files
- **Disk Space** — For ensuring sufficient storage before saving photos

### 11.2 Encryption

The App does not use non-exempt encryption. All encryption is provided by standard iOS frameworks (HTTPS/TLS) and third-party services.

### 11.3 Tracking

The App does not track users across other companies' apps or websites. `NSPrivacyTracking` is set to `false` in our privacy manifest. No advertising identifiers (IDFA) are collected.
