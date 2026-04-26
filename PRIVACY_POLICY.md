# Drumbridge — Privacy Policy

_Last updated: 2026-04-25_

Drumbridge is a companion app for Teenage Engineering EP-series sampling drum machines. This privacy policy describes what data the app handles and, more importantly, what it does **not** collect.

---

## The short version

**Drumbridge collects nothing. At all.**

- No analytics
- No crash reporting
- No user accounts
- No network calls of any kind
- No third-party SDKs
- No tracking, no advertising identifiers, no fingerprinting

If you use Drumbridge offline on airplane mode, it will work exactly the same as with an internet connection — because the app never touches the network.

---

## What the app does on your device

Drumbridge runs entirely on-device and communicates with your Teenage Engineering EP-series hardware over a physical USB-C MIDI connection.

Files created or read by the app are stored in one of two places:

1. **The app's private sandbox** on your device (managed by iOS)
2. **The iOS Files app**, when you explicitly save backups, exports, or downloaded samples

Nothing is uploaded anywhere. The app has no servers. There are no servers.

---

## System permissions

Drumbridge requests the following iOS permissions only when you use the corresponding features:

| Permission | Why |
|---|---|
| Microphone | Only used if you tap Auto-Sampler to record audio from an external synth, or when the app plays back audio you import. Audio never leaves your device. |
| Files / Documents | To read sample files you pick and save exports/backups you create. |

Drumbridge does **not** request contacts, photos, location, health, calendar, reminders, camera, Bluetooth, or any other sensitive data.

---

## Required-reason APIs

To comply with Apple's iOS 17+ privacy manifest requirements, Drumbridge declares the following uses of required-reason APIs in its `PrivacyInfo.xcprivacy` manifest:

- **File timestamp API** — used to show the creation date of local backup files in the backup library UI (reason code `C617.1`: display to user).
- **System boot time API (`mach_absolute_time`)** — used by the project playback engine to schedule sample triggers with sample-accurate timing (reason code `35F9.1`: measure time between events within the app).

Neither API is used for tracking, fingerprinting, or any purpose other than the functionality described above.

---

## Children

Drumbridge has an age rating of 4+ and is safe for all ages. Because the app collects no data, nothing about a child (or anyone else) is ever recorded or transmitted.

---

## Changes to this policy

If the app ever changes to collect data in the future, this policy will be updated and users will be notified via the app's release notes. As of this version, that is not planned.

---

## Contact

Questions or concerns about privacy? [Open an issue](https://github.com/tonkoshkurik/Drumbridge/issues) on the support tracker, or email the developer at the contact address shown in App Store Connect.

---

## Disclaimer

Drumbridge is an independent project. It is not affiliated with, endorsed by, or sponsored by Teenage Engineering AB. All product names are trademarks of their respective owners and are used solely to describe compatibility.
