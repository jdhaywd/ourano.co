---
layout: page
title: "Charlie Privacy Notice"
permalink: /charlie-privacy
---

# Charlie Privacy Notice

**Last updated: August 31, 2026**

> **Read this together with the [Ouranoco Privacy Policy](/privacy)**, which covers our privacy commitments, legal bases, your rights, international transfers, complaints, and contact details, and applies in full to Charlie. This notice covers only what is specific to Charlie. Where the two conflict, this notice governs.

Charlie is a personal productivity tool for airline flight crew. This notice describes how we handle your personal information when you download and use the Charlie mobile app. Questions? Contact us at privacy@ouranoco.com.

**In short:** Charlie has no account system, and for most users **nothing reaches Ouranoco at all**. Everything you enter stays on your device and, if you are signed into iCloud, in your own private iCloud database, which we cannot see. If you complete the optional airline verification, we receive your verified work email address and a small set of aggregate usage counts — nothing more.

---

## A1. What Information Does Charlie Collect?

### Data you enter — stored on your device and in your iCloud, never sent to us

Charlie requires no account, login, or personal identification, and we do not collect your name or employee number. The following may be entered by you and stored within the app:

- **Airline and fleet preferences** — your airline name and aircraft type, entered during onboarding and stored locally
- **Flight data** — callsigns, flight numbers, routes, departure and arrival times, fuel figures, MSA data, maneuver speeds, crew rest periods, and other data you enter for each flight
- **Operational flight plan (OFP) data** — figures and documents you import from your airline's OFP
- **Airport notes and data** — personal notes, visit history, and operational information you record for each airport
- **Satellite imagery** — snapshots of airport locations fetched from Apple Maps and stored on your device for offline reference
- **Personal notes** — text, images, procedures, mnemonics, and tables you create
- **Checklists** — checklist templates and per-flight checklists you build and manage
- **Reminders and timers** — titles, dates, durations, and notification preferences you configure

We never receive the content of any of it.

### Data collected from verified users

Airline verification is **optional**. If you skip it, nothing below is collected and no data whatsoever is sent to our servers. If you choose to verify, we process:

- **Verified work email address** — submitted during verification and sent to our verification service and backend database
- **Usage statistics** — on each app launch after verification: your verified email address, a last-activity timestamp, total app launch count, and total numbers of flights, notes, and airports recorded. These are **aggregate counts only**; the content of your flights, notes, and airports is never transmitted.

These counts are first-party operational statistics used to understand engagement among verified crew — not third-party analytics, never sold or shared.

### Automatic collection

For unverified users, **none**. We collect no device identifiers, IP addresses, usage statistics, or telemetry.

When you view an airport, the app may request satellite imagery from Apple's MapKit using the airport's publicly known coordinates. This is a standard Apple system call carrying no personally identifiable information, and is governed by Apple's privacy policy.

Charlie also processes no sensitive or special category personal information.

---

## A2. How Does Charlie Use Your Information?

Processing happens within the app, through Apple's iCloud infrastructure (which you control via your Apple ID), and — for verified users only — through our own backend:

- **To provide the Services.** Powering flight planning, fuel management, airport reference, notes, checklists, reminders, and timers.
- **To sync across your devices.** If you are signed into iCloud, your data syncs to your other Apple devices via your private iCloud database.
- **To back up your data.** At your instruction, the app can export a backup to your iCloud Drive, accessible only to you.
- **To send local notifications.** Reminders and timers are scheduled entirely on-device, with no server or third-party notification service involved.
- **To verify airline association** *(verified users only)*. Your work email address is submitted to our verification service to confirm your association with the airline, unlocking airline-specific features and settings.
- **To record aggregate usage statistics** *(verified users only)*. The counts described in A1 are sent on each app launch.

Verification and its associated usage statistics rest on your **consent**, which you give by choosing to verify and can withdraw at any time. Everything else is local processing on your own device.

---

## A3. Who Is Your Information Shared With?

| Recipient                                    | Data involved                                                                                                    | Purpose                                                                         |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Apple iCloud**                             | All app data you enter (flights, airports, notes, checklists, etc.)                                              | Syncing across your personal Apple devices via your private iCloud account       |
| **Apple MapKit**                             | Airport latitude and longitude (publicly available data)                                                         | Fetching satellite imagery of airport locations for offline reference           |
| **Apple Notifications**                      | Reminder titles and scheduled times                                                                              | Scheduling local notifications on your device                                   |
| **Ouranoco backend** *(verified users only)* | Verified work email address, last-seen timestamp, and aggregate counts of app launches, flights, notes, airports | Airline verification and aggregate usage statistics                              |

Apple system services are governed by Apple's Privacy Policy; your iCloud data sits in your own private database, which we have no access to. Our backend is operated by us and governed by this notice.

No one else receives your data — see the [company-wide sharing rules](/privacy#6-when-and-with-whom-do-we-share-your-personal-information).

---

## A4. Retention and Deletion

Charlie has no account to delete. Almost all your data sits on your device and in your own iCloud account, so retention is entirely under your control.

| Data type                                                   | Where stored            | How to delete                                                      |
| ----------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------ |
| Airline and fleet preferences                               | Device (local settings) | Settings → Clear Local Data, or delete the app                     |
| Flight data                                                 | Device + iCloud         | Delete individual flights in-app, or Settings → Clear iCloud Data  |
| Airport data and notes                                      | Device + iCloud         | Delete individual airports in-app, or Settings → Clear iCloud Data |
| Personal notes                                              | Device + iCloud         | Delete individual notes in-app, or Settings → Clear iCloud Data    |
| Checklists and templates                                    | Device + iCloud         | Delete in-app, or Settings → Clear iCloud Data                     |
| Reminders and timers                                        | Device + iCloud         | Delete in-app, or Settings → Clear iCloud Data                     |
| Satellite imagery                                           | Device (local storage)  | Cleared when you delete the airport or delete the app              |
| iCloud Drive backups                                        | iCloud Drive            | Delete manually from the Files app                                 |
| Verified email and usage statistics *(verified users only)* | Ouranoco backend        | Email privacy@ouranoco.com to request deletion                     |

To remove everything at once: **Settings → Clear Local Data**, then **Settings → Clear iCloud Data**, then delete any iCloud Drive backups from the Files app and delete the app itself.

---

## A5. Charlie-Specific Security Measures

Beyond the [company-wide security baseline](/privacy#9-how-do-we-keep-your-information-safe), Charlie relies on:

- **Apple's private iCloud database** — encrypted in transit and at rest by Apple. This is your own iCloud account; Ouranoco has no access to it.
- **Encrypted backend storage** *(verified users only)* — verified email addresses and aggregate counts are transmitted over TLS and encrypted at rest, with access restricted to us.

Protect your device and iCloud account with a strong passcode and two-factor authentication.

---

## A6. Exercising Your Rights in Charlie

Your rights are set out in the [Ouranoco Privacy Policy](/privacy#11-what-are-your-privacy-rights). If you are unverified we hold no information about you, so there is nothing on our side to access, port, or delete. Otherwise:

- **Access and portability** — export your airport data via the Share button in the Airports tab, or open the iCloud Drive backup file in the Files app.
- **Erasure** — use the in-app controls in A4 above for device and iCloud data; email privacy@ouranoco.com to have your verified email address and usage statistics removed from our backend.
- **Withdrawing consent to verification** — email privacy@ouranoco.com and we will remove your record.
