# Privacy Policy for VacuBot Advisor

**Last updated:** September 29, 2026 (applies to app version 1.2 and later)

This Privacy Policy describes how **VacuBot Advisor** ("the App", "we", "our", or "us") handles information when you use our Android application.

---

## 1. Overview

VacuBot Advisor is a robot vacuum recommendation app that helps you find the right robot vacuum cleaner through a guided quiz and a browsable product database.

The App is designed to work with minimal data:

* We do **not** require an account and we do **not** ask for your name, email address or any other contact details.
* We do **not** operate our own servers. Your quiz answers and settings never leave your device.
* The App shows **advertising** provided by Google AdMob, and it downloads **updated prices** and **currency exchange rates** from third-party services (see Section 3).

---

## 2. Information Stored on Your Device

The App stores the following **locally on your device only**. We cannot access it.

| Data | Purpose | Personal? |
| --- | --- | --- |
| Robot vacuum database | Product specifications and prices for browsing and recommendations | No |
| Quiz answers and results | Calculating your top 3 recommendations. Kept in memory for the current session only, never saved permanently | No |
| App settings | Your dark mode and currency (USD/EUR) choices | No |
| Cached exchange rate | The latest USD→EUR rate and when it was downloaded, so prices can be shown in euros offline | No |
| Advertising consent choice | Your answer to the consent message (see Section 4), stored by Google's consent tool in the standard IAB TCF format so the App can respect it | Relates to your privacy choices |

---

## 3. Third-Party Services

The App uses the following third-party services. They receive some technical data from your device when the App communicates with them.

### 3.1 Google AdMob (advertising)

The App displays **banner advertisements** and a **full-screen (interstitial) advertisement** before showing your quiz results. These ads are served by **Google AdMob**, which may collect and process:

* Your device's advertising identifier (Google Advertising ID) and, on supported Android versions, Android Privacy Sandbox ad signals (Topics, Attribution)
* IP address (used to estimate your approximate location, e.g. country or city)
* Device and app information (Android version, device model, screen size, language, app version)
* Ad interactions (impressions and clicks) and diagnostic information
* Information stored on or read from your device (similar to cookies)

Depending on your consent choice (Section 4) and your location, ads may be **personalised** (based on your interests) or **non-personalised / limited** (based on context such as the app content and approximate location only).

Google acts as an independent controller and/or processor for this data. See:

* Google Privacy Policy: https://policies.google.com/privacy
* How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites

### 3.2 Google User Messaging Platform (consent management)

To ask for and remember your advertising consent, the App uses Google's **User Messaging Platform**, a Google-certified consent management platform integrated with the IAB Transparency and Consent Framework (TCF) v2.2. To determine whether a consent message applies to you, it processes your IP address (to estimate your region) and device information, and it stores your choice on your device.

### 3.3 Google Firebase Remote Config (price updates)

The App uses **Firebase Remote Config** to download updated robot vacuum prices, so that the prices shown stay current without an app update. To do this, Firebase processes:

* A Firebase installation identifier (a random ID for this installation of the App, not linked to your identity)
* App and device information (app version, Android version, language, country)
* IP address

We do not use Firebase Analytics and we do not use Firebase to track your behaviour. Firebase privacy information: https://firebase.google.com/support/privacy

### 3.4 Frankfurter (currency exchange rates)

At most once per day, the App requests the current USD→EUR exchange rate from the public **Frankfurter** API (api.frankfurter.app), which publishes reference rates from the European Central Bank. The request contains no personal data. As with any internet request, the service receives your IP address and standard technical request information.

### 3.5 Retailer links

Where the App shows a **"Buy Now"** button, tapping it opens a third-party retailer's website or app. The link may be an affiliate link, meaning we may receive a commission if you buy something. The App does not send any personal data to the retailer. Once you are on the retailer's site, its own privacy policy applies.

### 3.6 Contacting us

If you use **"Report an Issue"**, the App opens your own email app with a pre-filled message. Nothing is sent unless you send the email yourself. We then receive your email address and whatever you write, and use them only to reply to you.

---

## 4. Your Advertising Consent (EEA, UK and Switzerland)

If you are in the European Economic Area, the United Kingdom or Switzerland, the App asks for your consent before any ads are requested. You can:

* **Consent:** Google and its advertising partners may use your data for personalised ads and ad measurement.
* **Do not consent:** you will still see ads, but they will be non-personalised or limited.
* **Manage options:** choose individual purposes and partners.

You can change or withdraw your choice at any time in the App under **Settings → Privacy & ad choices**. Withdrawing consent does not affect processing that happened before the withdrawal.

Outside these regions, ads may be personalised in line with Google's policies. You can always limit this on your device (Section 7.2).

---

## 5. Legal Basis for Processing (GDPR)

For users in the EEA, UK and Switzerland:

| Processing | Legal basis |
| --- | --- |
| Personalised advertising, and storing/reading information on your device for advertising | Your **consent** (Art. 6(1)(a) GDPR; ePrivacy rules) |
| Non-personalised/limited ads, ad fraud prevention, ad measurement where permitted | **Legitimate interests** in funding a free app (Art. 6(1)(f) GDPR) |
| Downloading price updates and exchange rates | **Legitimate interests** in showing accurate, current prices (Art. 6(1)(f) GDPR) |
| Replying to your emails | **Legitimate interests** in answering your enquiry (Art. 6(1)(f) GDPR) |

---

## 6. App Permissions

| Permission | Purpose |
| --- | --- |
| `INTERNET` | Loading ads, showing the consent message, downloading price updates and exchange rates, and opening retailer links |
| `ACCESS_NETWORK_STATE` | Checking whether a network connection is available before making requests |
| `com.google.android.gms.permission.AD_ID` | Lets Google AdMob read the advertising identifier (subject to your consent and device settings) |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Android Privacy Sandbox advertising APIs used by Google AdMob on supported devices |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Added by Google's libraries so they can finish short background tasks reliably |

The App does not request access to your location, contacts, camera, microphone, photos or files.

---

## 7. Data Retention and Deletion

### 7.1 Data on your device

All App data (including your settings and consent choice) is stored in the App's private storage. To delete it:

* Go to **Android Settings → Apps → VacuBot Advisor → Storage → Clear storage**, or
* **Uninstall the App**.

### 7.2 Advertising data

* Change your consent at any time in **Settings → Privacy & ad choices**.
* To reset or delete your advertising ID: **Android Settings → Privacy → Ads** (Android 12+), or **Settings → Google → Ads** (older versions).
* To manage Google's data about you: https://myaccount.google.com

Data held by Google (AdMob, the User Messaging Platform, Firebase) is kept according to Google's retention policies.

### 7.3 Emails

We keep your emails only as long as needed to handle your request, and delete them on request.

---

## 8. International Data Transfers

Google and the Frankfurter service may process data on servers outside your country, including outside the EEA (for example in the United States). Google relies on legal safeguards such as the EU–U.S. Data Privacy Framework and Standard Contractual Clauses for these transfers.

---

## 9. Children's Privacy

The App is not directed at children under 16 and does not knowingly collect personal information from children. If you believe a child has sent us personal information, please contact us (Section 12) and we will delete it.

---

## 10. Data Security

The App stores no personal data on any server of ours, because we do not operate one. Data on your device is kept in the App's private storage, which other apps cannot access. All connections to Google and Frankfurter use encrypted HTTPS.

---

## 11. Your Rights

Depending on where you live, you may have rights under laws such as the GDPR (EU/EEA), UK GDPR or CCPA (California), including the right to access, correct, delete or restrict your data, to object to processing, to data portability, and to withdraw consent.

* **Advertising consent:** change it in **Settings → Privacy & ad choices**.
* **Data held by Google:** use Google's tools at https://myaccount.google.com or contact Google.
* **Emails you sent us:** contact us (Section 12).

You also have the right to lodge a complaint with your data protection authority. In Slovakia, this is the Office for Personal Data Protection of the Slovak Republic (Úrad na ochranu osobných údajov SR, https://dataprotection.gov.sk).

---

## 12. Contact Us

For questions about this Privacy Policy, to exercise your rights, or to report a security vulnerability:

**Email:** [netmentor.dev@gmail.com](mailto:netmentor.dev@gmail.com)

We aim to respond within **30 days**. For security reports, please include a description of the issue, steps to reproduce it, and its potential impact.

---

## 13. Changes to This Privacy Policy

We update this Privacy Policy whenever the App's handling of data changes, for example when a new feature, third-party service or permission is added. The **"Last updated"** date at the top shows the latest version. Significant changes will be announced in the App's release notes on Google Play.

---

*This privacy policy applies to the Android application **VacuBot Advisor** (`com.netmentor.vacubot`), published on Google Play.*
