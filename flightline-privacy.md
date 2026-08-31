---
layout: page
title: "FlightLine Privacy Notice"
permalink: /flightline-privacy
---

# FlightLine Privacy Notice

**Last updated: August 31, 2026**

> **Read this together with the [Ouranoco Privacy Policy](/privacy)**, which covers our privacy commitments, legal bases, your rights, international transfers, complaints, and contact details, and applies in full to FlightLine. This notice covers only what is specific to FlightLine. Where the two conflict, this notice governs.

FlightLine is a roster, pay, and commute tool for airline crew. This notice describes how we handle your personal information when you download and use the FlightLine mobile app. Questions? Contact us at privacy@ouranoco.com.

**In short:** FlightLine uses Sign in with Apple and keeps a small account profile on our backend — staff number, crew code, optional display name, subscription status, last login timestamp, and a monthly count of commute route calculations. Your roster, your pay and tax figures, your airline password, and your crew directory credentials never reach us; they stay on your device. Three categories of service provider are involved, described in A3.

---

## A1. What Information Does FlightLine Collect?

### Held on our backend

- **Staff number** and **crew code** — used to authenticate you and retrieve roster data from your airline's scheduling system
- **Display name** — optional, provided during Sign in with Apple
- **Subscription status** — to provide access to premium features
- **Last login timestamp**
- **Commute API usage count** — how many route calculations you perform each month, used to enforce fair usage limits on a metered third-party service

The last two are first-party operational records, not analytics. We collect no device identifiers, IP addresses, browser types, or other telemetry.

### Held only on your device, never transmitted to us

- **Roster and schedule data** — trip lines, duties, sectors, and ground duties imported from your airline's scheduling system
- **Payslip estimation data** — salary, tax code, and other financial parameters you voluntarily enter. Processed **exclusively on your device**; we never see it.
- **Crew directory credentials** — if you use the pilot lookup feature, the email address and password for a third-party crew directory service are stored in your device's encrypted Keychain
- **Cached crew photos**
- **Custom key dates and notification preferences**

### Used but not retained

- **Postcode or home location** — sent for route calculation if you use the commute calculator (see A3)
- **Your airline login password** — held in memory only during your session, never written to storage or transmitted to us
- **Calendar access** — if you grant it, we write roster events to your device calendar. We do not read or collect your existing calendar data.

We also do not receive your email address from Apple (see A2).

---

## A2. How Does FlightLine Use Your Information, and On What Basis?

| Purpose                                                                        | Legal basis                                     |
| ------------------------------------------------------------------------------ | ----------------------------------------------- |
| Creating and authenticating your account                                       | Performance of a contract                       |
| Displaying your schedule, calculating allowances, estimating pay               | Performance of a contract (processed on-device) |
| Managing your subscription and premium entitlements                            | Performance of a contract                       |
| Counting commute route calculations to enforce fair usage                      | Legitimate interests                            |
| Optional features: commute calculator, calendar export, notifications, payslip estimation, crew directory lookup | Consent                                         |

**Sign in with Apple** is the sole authentication method. When you sign in we receive an identity token from Apple and your full name **only if you choose to share it**. We do not receive your email address. We are not responsible for Apple's own use of your personal information; review Apple's privacy policy for that. Your airline credentials are entirely separate from your FlightLine account.

---

## A3. Who Is Your Information Shared With?

### Service providers

These process personal information on our behalf, under contract, only on our instructions:

| Provider                         | Data involved                                                                                            | Purpose                                                       |
| -------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **Hosted database provider**                     | Staff number, crew code, display name, subscription status, API usage count, last login timestamp        | Account management, subscription verification, usage tracking |
| **Apple** (Sign in with Apple)   | Apple identity token                                                                                      | Authentication                                                |
| **Mapping and routing provider**                       | Postcode/coordinates, destination coordinates                                                             | Commute route calculation and geocoding                       |

### Services you access directly

Accessed by your device using your own credentials. FlightLine facilitates the connection but does not relay or store credentials for these services on our servers:

- Airline scheduling, bidding, and briefing systems — using your own airline credentials
- **A third-party crew directory service** — using credentials you optionally store in your device's encrypted Keychain

These organisations are independent controllers governed by their own privacy policies.

No one else receives your data — see the [company-wide sharing rules](/privacy#6-when-and-with-whom-do-we-share-your-personal-information).

---

## A4. Retention and Deletion

| Data type                                          | Where stored          | Retention and deletion                                        |
| -------------------------------------------------- | --------------------- | ------------------------------------------------------------- |
| Account profile (staff number, crew code, display name) | Hosted database provider              | Until you delete your account                                 |
| Subscription status                                | Hosted database provider              | Until you delete your account                                 |
| Last login timestamp                               | Hosted database provider              | Until you delete your account                                 |
| API usage counts                                   | Hosted database provider              | Reset monthly                                                 |
| Roster and schedule data                           | Device                | Cleared on app deletion                                       |
| Payslip estimation data                            | Device only           | Cleared on app deletion                                       |
| Crew directory credentials                         | Device Keychain       | Cleared on app deletion or manual removal                     |
| Cached crew photos                                 | Device only           | Cleared on app deletion                                       |
| Calendar events written by the app                 | Your device calendar  | Managed by you in the Calendar app                            |

**To delete your account**, email privacy@ouranoco.com. We will delete or anonymise your information from our active databases, though we may retain limited information where necessary to prevent fraud, troubleshoot, assist investigations, enforce our legal terms, or comply with legal requirements. Some data may persist briefly in backup archives, isolated from further processing.

**To delete local data**, delete the app. You may also want to remove any roster events the app wrote to your calendar, and revoke access under iOS Settings → your name → Sign in with Apple → FlightLine.

---

## A5. FlightLine-Specific Security Measures

Beyond the [company-wide security baseline](/privacy#9-how-do-we-keep-your-information-safe), FlightLine applies:

- **Sign in with Apple** — we never handle a password for your FlightLine account
- **On-device-only processing of your pay and tax figures**, so that information never travels over the network at all

Protect your device and Apple ID with a strong passcode and two-factor authentication.

---

## A6. Exercising Your Rights in FlightLine

Your rights are set out in the [Ouranoco Privacy Policy](/privacy#11-what-are-your-privacy-rights).

Because we hold an account record for you, requests for access, rectification, erasure, restriction, portability, or objection should go to privacy@ouranoco.com; we respond within one month. For data held only on your device — roster, pay figures, crew directory credentials, cached photos — you can achieve erasure immediately by deleting the app, without contacting us.

To withdraw consent for an optional feature, turn it off in the app or revoke the relevant iOS permission in Settings.
