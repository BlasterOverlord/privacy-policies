---
title: AuraLook Privacy Policy
theme: jekyll-theme-cayman
---

# Privacy Policy for AuraLook

**Effective date:** April 22, 2026
**Last updated:** October 16, 2026

AuraLook ("the Application") is an Android app developed by BlasterOverlord that replaces the lock screen notification display with a minimal, OLED-friendly one. The core app is free, with an optional paid "AuraLook Pro" upgrade and optional tips. The Application is provided "AS IS".

## Summary

AuraLook does not collect, store, share, or transmit your personal information, notification content, or usage data. The Application does not request the Android `INTERNET` permission, so the app itself cannot connect to the internet. It contains no analytics, advertising, crash reporting, or account system.

## Notification Content

AuraLook reads notifications only to show them on its lock screen: the app icon, title, text, and any contact photo or image the notification already includes.

This content is held in your device's memory (RAM) only while it is displayed, then discarded. It is never written to storage and never leaves your device. The Pro "Privacy Mode" can additionally hide titles and text inside AuraLook.

## Data Stored on Your Device

AuraLook saves only the following, locally and privately to the app:

- **Your settings**, such as theme, animation, timeout, and cooldown.
- **Your app filter list:** the package names of apps you chose to block or allow.
- **Pro purchase receipt:** the signed receipt from Google Play, so Pro stays unlocked offline.
- **Reminder state** (only if you enable missed-notification reminders): internal notification identifiers, attempt counts, and timing. It contains no notification text, senders, or images.

This data is excluded from Android backups and is removed when you clear the app's data or uninstall it.

## Permissions and Special Access

All of the following are used only on your device and never to collect or share personal data.

| Permission / access | Why it's needed |
|---|---|
| Notification access | To detect incoming notifications and display them on the AuraLook lock screen |
| Accessibility service | Only to turn the screen off after the display timeout or on double-tap. It ignores all accessibility events and cannot read screen content |
| Display over other apps | To show AuraLook on top of the lock screen |
| Do Not Disturb access | To temporarily suppress system heads-up banners while AuraLook is showing, then restore your previous setting |
| Secure settings (`WRITE_SECURE_SETTINGS`), optional | Not granted by default. If you grant it via ADB or [Shizuku](https://shizuku.rikka.app/), AuraLook toggles the system heads-up banner setting while showing a notification and restores it afterward |
| Exact alarms | To time optional missed-notification reminders |
| Wake lock, vibrate, post notifications | To wake the screen, give haptic feedback, and show standard Android notifications |
| Ignore battery optimizations, boot completed | To keep AuraLook running reliably and restore its state after a restart |
| Query all packages | To list your installed apps in the app filter screen. This list is never stored or sent anywhere |

AuraLook may also briefly read your proximity, light, and motion sensors to detect whether the phone is in a pocket or bag. These readings are used immediately and are not stored or transmitted.

## In-App Purchases

AuraLook uses the Google Play Billing Library for the "AuraLook Pro" upgrade and optional tips. Payments are processed entirely by Google Play. AuraLook has no access to your card, billing address, or other financial details and only receives a signed receipt confirming your purchase. Google's handling of your data is covered by [Google's Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

AuraLook does not knowingly collect personal information from anyone, including children, because it does not collect personal information at all.

## Changes to This Policy

If this policy changes, the updated version will be posted at this same URL with a revised "Last updated" date.

## Contact

If you have questions about this privacy policy, contact: **[blasteroverlord10@gmail.com](mailto:blasteroverlord10@gmail.com)**
