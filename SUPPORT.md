# Drumbridge Support

## Get help

- **Found a bug?** [Open a bug report](https://github.com/tonkoshkurik/Drumbridge/issues/new?template=bug_report.yml)
- **Have a feature idea?** [Open a feature request](https://github.com/tonkoshkurik/Drumbridge/issues/new?template=feature_request.yml)
- **Other questions?** Check existing [issues](https://github.com/tonkoshkurik/Drumbridge/issues) first — your question may already be answered.

## What to include in a bug report

The more of this you can provide, the faster the fix:

1. **Device** — EP-133 K.O. II, EP-1320 Medieval, or EP-40 RIDDIM
2. **Device firmware version** — visible in the device's settings menu
3. **iOS / iPadOS version**
4. **iPhone or iPad model**
5. **Drumbridge version** — visible at the bottom of the app's Device tab
6. **Steps to reproduce** — what you tapped, in order
7. **What you expected vs. what happened**
8. **Diagnostics export** (if relevant) — Device tab → "Share Diagnostics" sends a small bundle of crash + performance reports collected on-device by Apple's MetricKit. No samples or projects are included.

## Privacy note

Diagnostics exports contain only what iOS itself records about app crashes and performance. They never include audio, project files, or any personal data. You're always the one who chooses to share them.

## Compatibility

Drumbridge supports the following devices over USB-C MIDI:

| Device | Minimum recommended firmware |
|---|---|
| EP-133 K.O. II | latest stable |
| EP-1320 Medieval | 1.0.3+ (multisample support; earlier versions have a known crash bug — please update) |
| EP-40 RIDDIM | 1.0.5+ (earlier versions have known disk-access crashes during downloads) |

If the app reports your firmware version is below the minimum, please update via Teenage Engineering's official [field](https://teenage.engineering/field) tool before filing a bug.
