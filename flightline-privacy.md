---
layout: page
title: "FlightLine Privacy Notice"
permalink: /flightline-privacy
---

# FlightLine Privacy Notice

**Last updated: August 31, 2026**

> **Read this together with the [Ouranoco Privacy Policy](/privacy).**
>
> The [Ouranoco Privacy Policy](/privacy) is our company-wide policy. It covers our privacy commitments, the legal bases we rely on, your rights under the UK GDPR and GDPR, international transfers, how to complain, and how to contact us. It applies in full to FlightLine.
>
> **This notice covers only what is specific to FlightLine**: exactly what data the app handles, where it is stored, who else is involved, how long it is kept, and how to delete it. Where this notice and the company policy differ, this notice governs for FlightLine.

FlightLine is a roster, pay, and commute tool for airline crew. This notice describes how and why we might access, collect, store, use, and/or share ('process') your personal information when you download and use the FlightLine mobile app.

Questions or concerns? Contact us at privacy@ouranoco.com.

---

## FlightLine at a Glance

- **Does FlightLine require an account?** Yes. FlightLine uses **Sign in with Apple** as its sole authentication method, and stores a small account profile.
- **What does Ouranoco hold?** Your staff number, crew code, optional display name, subscription status, last login timestamp, and a monthly count of commute route calculations.
- **What never reaches us?** Your roster data, your pay and tax figures, your airline password, and your Fleetlist credentials. All of these stay on your device.
- **Service providers?** Three, all named below: Supabase, Apple, and Mapbox.
- **Third-party analytics, ads, or trackers?** None.
- **How do you delete your data?** Email privacy@ouranoco.com to delete your account, and delete the app to clear local data.

---

## Contents

- [A1. What Information Does FlightLine Collect?](#a1-what-information-does-flightline-collect)
- [A2. How Does FlightLine Use Your Information?](#a2-how-does-flightline-use-your-information)
- [A3. Who Is Your Information Shared With?](#a3-who-is-your-information-shared-with)
- [A4. Accounts and Sign in with Apple](#a4-accounts-and-sign-in-with-apple)
- [A5. How Long Is Your Information Kept?](#a5-how-long-is-your-information-kept)
- [A6. FlightLine-Specific Security Measures](#a6-flightline-specific-security-measures)
- [A7. Deleting Your Data](#a7-deleting-your-data)
- [A8. Exercising Your Rights in FlightLine](#a8-exercising-your-rights-in-flightline)

---

## A1. What Information Does FlightLine Collect?

**In Short:** A small account profile reaches our servers. Your roster, pay figures, and third-party credentials do not — they stay on your device.

### Information you provide

The personal information we collect depends on the features you use, and may include:

- **Staff number** — used to authenticate you and to retrieve roster data from your airline's scheduling system
- **Crew code** — used to authenticate you and to retrieve roster data from your airline's scheduling system
- **Display name** — optionally provided during Sign in with Apple
- **Roster and schedule data** — trip lines, duties, sectors, and ground duties imported from your airline's scheduling system
- **Postcode or home location** — if you choose to use the commute calculator feature
- **Payslip estimation data** — salary, tax code, and other financial parameters you voluntarily enter for payslip calculations. **This data is stored locally on your device only and is never transmitted to our servers.**
- **Fleetlist credentials** — if you choose to use the pilot lookup feature, your fleetlist.com email and password are stored in your device's encrypted Keychain and are **never transmitted to FlightLine servers**
- **Calendar data** — if you grant calendar access, we write roster events to your device calendar. **We do not read or collect your existing calendar data.**
- **Custom key dates and notification preferences** — dates and reminder settings you configure within the app

### Financial information

Salary and tax information you enter for the payslip estimation feature is processed **exclusively on your device**. It is never transmitted to our servers, and we never see it. You provide it voluntarily and can remove it at any time by deleting the app.

### Information automatically collected

When you use the app, we automatically record:

- **Last login timestamp** — stored in your profile on our backend service
- **Mapbox API usage count** — the number of commute route calculations you perform each month, used to enforce fair usage limits on a metered third-party service

These are first-party operational records, not analytics. We do not collect device identifiers, IP addresses, browser types, or other telemetry for analytics purposes. See [Our Privacy Commitments](/privacy#2-our-privacy-commitments).

### Information NOT collected

In addition to the [company-wide commitments](/privacy#2-our-privacy-commitments) — no ads, no data sales, no GPS, no contacts/photos/camera/microphone access, no third-party tracking SDKs — we want to be specific about FlightLine:

- **We do not collect or store your airline login password.** It is used in memory only during your session and is never written to storage or transmitted to our servers.
- **We do not store your Fleetlist password.** It lives in your device's encrypted Keychain.
- **We do not receive your roster data.** It is fetched by your device from your airline's systems and stored there.
- **We do not receive your pay or tax figures.**
- **We do not receive your email address from Apple.**

---

## A2. How Does FlightLine Use Your Information?

**In Short:** To authenticate you, deliver the app's features, manage your subscription, and keep metered features within fair usage.

We process your personal information for the following purposes:

- **To facilitate account creation and authentication.** We process your staff number, crew code, and Apple identity token to create and verify your account.
- **To deliver the Services.** Your roster data is processed on your device to display your schedule, calculate allowances, estimate pay, and provide commute information.
- **To manage subscriptions.** We process your subscription status to provide access to premium features.
- **To enforce usage limits.** We count commute route calculations to manage fair usage of a metered third-party API.
- **To send notifications.** If you opt in, we send notifications for key dates, commute alerts, and trip reminders.
- **To export calendar events.** If you grant permission, we write your roster events to your device calendar.

The legal bases we rely on are set out in the [Ouranoco Privacy Policy](/privacy#5-what-legal-bases-do-we-rely-on-to-process-your-personal-information). In summary: your account, roster, and subscription processing rests on **performance of a contract**; optional features such as the commute calculator, calendar export, pay estimation, notifications, and Fleetlist lookup rest on your **consent**; and usage counting rests on our **legitimate interest** in operating a metered service fairly.

---

## A3. Who Is Your Information Shared With?

**In Short:** Three named service providers, plus systems you connect to directly using your own credentials. No one else.

### Service providers

These providers process personal information on our behalf, under contract, and only on our instructions:

| Provider | Data involved | Purpose |
|----------|---------------|---------|
| **Supabase** | Staff number, crew code, display name, subscription status, API usage count, last login timestamp | Account management, subscription verification, usage tracking |
| **Apple** (Sign in with Apple) | Apple identity token | Authentication |
| **Mapbox** | Postcode/coordinates, destination coordinates | Commute route calculation and geocoding |

<!-- REVIEW: Confirm the Supabase project region and Mapbox processing locations, and record the transfer mechanism (UK IDTA / SCCs) for any processing outside the UK/EEA. Then update section 7 of the company policy, or state the mechanism here. Also confirm a written processor agreement (UK GDPR Art. 28) is in place with each of these providers. -->

### Services you access directly

The following are accessed directly by your device using your own credentials. FlightLine facilitates the connection but does not relay or store your credentials for these services on our servers:

- **Airline scheduling systems** — accessed using your own airline credentials
- **Airline bidding systems** — accessed using your own airline credentials
- **Airline briefing systems** — accessed using your own airline credentials
- **Fleetlist.com** — accessed using credentials you optionally store in your device's encrypted Keychain

These organisations are independent controllers of any data they hold, governed by their own privacy policies. We have no visibility into or control over how they process your information.

### We do NOT share data with

Advertising networks, data brokers, marketing partners, third-party analytics providers, or any other third party not named above. See [company-wide sharing rules](/privacy#6-when-and-with-whom-do-we-share-your-personal-information).

---

## A4. Accounts and Sign in with Apple

**In Short:** Sign in with Apple is the only way to sign in, and Apple shares very little with us.

FlightLine uses **Sign in with Apple** as its sole authentication method. When you sign in, we receive:

- An identity token from Apple
- Your full name, **only if you choose to share it**

**We do not receive your email address from Apple.** We use the information we receive only for the purposes described in this notice. We do not control, and are not responsible for, Apple's use of your personal information. We recommend that you review Apple's privacy policy to understand how they collect, use, and share your personal information.

Your airline credentials are separate from your FlightLine account. Your airline password is never stored by us.

---

## A5. How Long Is Your Information Kept?

**In Short:** Server-side records are kept until you delete your account. On-device data is kept until you remove it.

| Data type | Where stored | Retention |
|-----------|-------------|-----------|
| Account profile (staff number, crew code, display name) | Supabase | Until you delete your account |
| Subscription status | Supabase | Until you delete your account |
| Last login timestamp | Supabase | Until you delete your account |
| API usage counts | Supabase | Reset monthly |
| Roster and schedule data | Device | Managed by you; cleared on app deletion |
| Payslip estimation data | Device only | Cleared on app deletion |
| Fleetlist credentials | Device Keychain | Cleared on app deletion or manual removal |
| Cached crew photos | Device only | Cleared on app deletion |
| Calendar events written by the app | Your device calendar | Managed by you in the Calendar app |

When you delete your account, we will delete or anonymise your personal information from our active databases. Some information may be retained in backup archives for a limited period, during which it will be securely isolated from any further processing until deletion is possible.

---

## A6. FlightLine-Specific Security Measures

In addition to the [company-wide security baseline](/privacy#9-how-do-we-keep-your-information-safe), FlightLine applies:

- **Sign in with Apple** for secure, privacy-preserving authentication — we never handle a password for your FlightLine account
- **iOS Keychain** encryption for any stored third-party credentials
- **iOS Data Protection** for locally stored roster, pay, and cached data
- **HTTPS** for all network communications
- **No storage of airline passwords** on our servers — credentials are used in memory only
- **On-device-only processing** of your pay and tax figures, so that this information never travels over the network at all
- **No analytics or tracking SDKs** that could expose your data

No electronic transmission or storage technology can be guaranteed 100% secure. You should access the Services only within a secure environment and protect your device and Apple ID with a strong passcode and two-factor authentication.

---

## A7. Deleting Your Data

To remove your data from FlightLine:

- **Delete your account:** email **privacy@ouranoco.com** to request deletion of your account profile, subscription status, last login timestamp, and usage counts from our backend
- **Delete local data:** delete the app from your device. This removes your roster cache, payslip estimation data, cached crew photos, and any Fleetlist credentials held in the Keychain
- **Remove calendar events:** delete any roster events the app wrote to your device calendar using the Calendar app
- **Revoke Sign in with Apple:** in iOS, go to Settings → your name → Sign in with Apple → FlightLine → Stop Using Apple ID

Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases. We may retain limited information where necessary to prevent fraud, troubleshoot problems, assist with investigations, enforce our legal terms, or comply with applicable legal requirements.

<!-- REVIEW: Apple's App Store Review Guideline 5.1.1(v) requires apps with account creation to offer in-app account deletion, not email-only. FlightLine creates accounts via Sign in with Apple, so an in-app "Delete account" control is very likely required. If one exists, document it here as the primary route; if not, this is a compliance gap worth closing before the next submission. -->

---

## A8. Exercising Your Rights in FlightLine

Your full rights are described in the [Ouranoco Privacy Policy](/privacy#11-what-are-your-privacy-rights).

Because FlightLine holds an account record for you, requests for access, rectification, erasure, restriction, portability, or objection should be sent to **privacy@ouranoco.com**. We will respond within one month.

For data held only on your device — roster, pay figures, Fleetlist credentials, cached photos — you can exercise erasure immediately by deleting the app, and you do not need to contact us.

To withdraw consent for an optional feature (commute calculator, calendar export, notifications, pay estimation, or Fleetlist lookup), turn the feature off in the app or revoke the relevant iOS permission in Settings.
