---
layout: page
title: "Roster Radar Privacy Notice"
permalink: /privacy/rosterradar
---

# Roster Radar Privacy Notice

**Last updated: August 31, 2026**

> **Read this together with the [Ouranoco Privacy Policy](/privacy).**
>
> The [Ouranoco Privacy Policy](/privacy) is our company-wide policy. It covers our privacy commitments, the legal bases we rely on, your rights under the UK GDPR and GDPR, international transfers, how to complain, and how to contact us. It applies in full to Roster Radar.
>
> **This notice covers only what is specific to Roster Radar**: exactly what data the app handles, where it is stored, who else is involved, how long it is kept, and how to delete it. Where this notice and the company policy differ, this notice governs for Roster Radar.

Roster Radar retrieves your British Airways roster directly from BA's own systems on your behalf. This notice describes how and why we might access, collect, store, use, and/or share ('process') your personal information when you download and use the Roster Radar mobile app.

Questions or concerns? Contact us at privacy@ouranoco.com.

---

## Roster Radar at a Glance

- **What does Ouranoco receive?** **Nothing.** No data from this app is ever sent to Ouranoco. We operate no servers for Roster Radar.
- **Does it require an account?** Not with us. It uses your existing British Airways BSAFE credentials to authenticate directly with BA.
- **What is stored, and where?** Your staff number and a cached copy of your roster, both held in local storage on your device.
- **Your BSAFE password?** Entered by you at runtime, held in memory only, never written to storage of any kind.
- **Third-party analytics, ads, or trackers?** None.
- **How do you delete your data?** Delete the app. That removes everything.

---

## Contents

- [A1. What Information Does Roster Radar Collect?](#a1-what-information-does-roster-radar-collect)
- [A2. How Does Roster Radar Use Your Information?](#a2-how-does-roster-radar-use-your-information)
- [A3. Who Is Your Information Shared With?](#a3-who-is-your-information-shared-with)
- [A4. Does Roster Radar Require an Account or Login?](#a4-does-roster-radar-require-an-account-or-login)
- [A5. How Long Is Your Information Kept?](#a5-how-long-is-your-information-kept)
- [A6. Roster Radar-Specific Security Measures](#a6-roster-radar-specific-security-measures)
- [A7. Deleting Your Data](#a7-deleting-your-data)
- [A8. Exercising Your Rights in Roster Radar](#a8-exercising-your-rights-in-roster-radar)

---

## A1. What Information Does Roster Radar Collect?

**In Short:** Ouranoco collects nothing. The only data stored is kept locally on your device and is never transmitted to us.

Roster Radar does not require an account, login, or any personal identification **with us**. The following data is stored locally on your device:

- **Staff number** — your six-digit British Airways staff number, saved locally so you do not need to re-enter it each time you open the app.
- **Cached roster data** — trip data retrieved from British Airways' eMaestro system (trip identifiers, flight numbers, routes, departure and arrival times), cached locally so it can be displayed without a network request on subsequent opens.

### Information entered at runtime but never stored

- **BSAFE password** — when eMaestro requires authentication, you are prompted to enter your BSAFE password. This password is used solely to authenticate with British Airways' own systems and is **never written to storage of any kind** by this app. It exists only in memory for the duration of the authentication request and is discarded immediately afterwards.

### Information automatically collected

**None.** The app transmits no data to us, automatically or otherwise.

### Information NOT collected

In addition to the [company-wide commitments](/privacy#2-our-privacy-commitments) — no ads, no data sales, no GPS, no contacts/photos/camera/microphone access, no third-party tracking SDKs — we want to be specific about Roster Radar:

- **We collect no data on our own servers.** No data from this app is ever sent to Ouranoco.
- We do not collect device identifiers, IP addresses, usage statistics, or any telemetry data.
- We never see your staff number, your roster, or your BSAFE password.

---

## A2. How Does Roster Radar Use Your Information?

**In Short:** Your staff number and roster cache are stored only on your device. We do not process your information at all.

All data the app stores is held in local device storage (iOS `UserDefaults`) and never leaves your device to reach our servers. Your data is used for the following purposes, all of which occur entirely on-device:

- **To provide the Services.** Your staff number is saved locally so you do not have to re-enter it each time. Your cached roster data is stored locally so it can be displayed on subsequent app opens without requiring a new network request.
- **To retrieve your roster from British Airways.** When you tap "Look Up Roster", the app sends your staff number (and, if required, your password) directly to British Airways' eMaestro system at `egprd.baplc.com`. This communication is between your device and British Airways' servers — **it does not pass through any Ouranoco infrastructure**.

The legal bases set out in the [Ouranoco Privacy Policy](/privacy#5-what-legal-bases-do-we-rely-on-to-process-your-personal-information) apply only to this local, on-device processing. Because Roster Radar transmits no data to our servers, there is no server-side processing by Ouranoco to justify.

<!-- REVIEW: The staff number and roster cache are held in iOS UserDefaults, which is not encrypted beyond iOS Data Protection at rest and is included in device backups. Consider moving the staff number to the Keychain for consistency with FlightLine, and update this notice if you do. -->

---

## A3. Who Is Your Information Shared With?

**In Short:** With no one. When you look up your roster, your credentials go directly from your device to British Airways' own systems.

Roster Radar does not route any user data through Ouranoco infrastructure. Your data interacts only with the following:

| Recipient | Data involved | Purpose |
|-----------|---------------|---------|
| **British Airways eMaestro** (`egprd.baplc.com`) | Staff number, BSAFE password (when authentication is required) | Authenticating with BA's systems and retrieving your roster on your behalf |

British Airways is an independent controller of the data it holds about you as its employee, governed by British Airways' own privacy policy. We do not have visibility into, or control over, how British Airways processes your credentials on their servers.

### We do NOT share data with

- **Ouranoco's own servers or backend**
- Advertising networks
- Data brokers
- Marketing partners
- Analytics providers
- Any other third party

See [company-wide sharing rules](/privacy#6-when-and-with-whom-do-we-share-your-personal-information).

---

## A4. Does Roster Radar Require an Account or Login?

**In Short:** No account with us. The app uses your existing British Airways BSAFE credentials to access BA's systems directly.

Roster Radar has no user account system. You do not need to create an account with us, provide a username, or sign in with us to use the app. The authentication that takes place is between your device and British Airways' servers, using your existing BA staff credentials.

Your BSAFE password is entered by you when prompted, used only to authenticate with BA's eMaestro system, and never stored by the app.

Roster Radar is intended for British Airways crew who are authorised to access their own roster through eMaestro. You should use the app in accordance with British Airways' own IT and security policies.

---

## A5. How Long Is Your Information Kept?

**In Short:** Your data is stored only on your device, and its retention is entirely under your control.

Because all data is stored locally on your device — and none on our servers — you have full control over how long it is kept.

| Data type | Where stored | How to delete |
|-----------|-------------|---------------|
| Staff number | Device (local storage) | Delete the app, or clear app data from iOS Settings |
| Cached roster data | Device (local storage) | Delete the app, or clear app data from iOS Settings |
| BSAFE password | Not stored — memory only | Discarded automatically after each authentication request |

Ouranoco has no retention period to disclose for this app, because we retain nothing.

---

## A6. Roster Radar-Specific Security Measures

**In Short:** Your data is protected by iOS security, and the app pins certificates when talking to British Airways.

In addition to the [company-wide security baseline](/privacy#9-how-do-we-keep-your-information-safe), Roster Radar applies:

- **iOS Data Protection** — data at rest on your device is encrypted using your device passcode.
- **Certificate pinning** — when the app communicates with British Airways' eMaestro servers, it uses certificate pinning to verify the server's identity and prevent man-in-the-middle attacks.
- **No password persistence** — your BSAFE password is held in memory only and never written to disk.
- **No Ouranoco-side storage** — because no data is transmitted to our servers, there is no Ouranoco-side data store that could be compromised.

You should protect your device with a strong passcode and keep your BSAFE credentials secure in accordance with British Airways' own security guidelines.

---

## A7. Deleting Your Data

To remove all data stored by Roster Radar:

- **Delete the app** from your device. This removes all locally stored data, including your saved staff number and any cached roster data.
- Alternatively, clear the app's data from iOS Settings.

Because Ouranoco holds no personal information about you, there is nothing to request from us.

---

## A8. Exercising Your Rights in Roster Radar

Your full rights are described in the [Ouranoco Privacy Policy](/privacy#11-what-are-your-privacy-rights).

For Roster Radar specifically:

- **Erasure:** delete the app from your device to remove all data it has stored.
- **Access, portability, restriction, objection:** because Ouranoco holds no personal information about you in connection with this app, there is no server-side record for us to provide, port, restrict, or delete.
- **Withdrawing consent:** delete the app from your device, which removes all locally stored data.

Requests concerning the roster and employment data held by **British Airways** should be directed to British Airways, not to Ouranoco — we are not the controller of that data and hold no copy of it.

If you have questions, or wish to complain, see [sections 11 and 14 of the Ouranoco Privacy Policy](/privacy#11-what-are-your-privacy-rights).
