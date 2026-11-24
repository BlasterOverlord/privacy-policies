---
title: AuraLook Privacy Policy
theme: jekyll-theme-cayman
---

# Privacy Policy for AuraLook

**Last updated:** November 24, 2026

AuraLook is an Android app developed by BlasterOverlord that replaces the lock screen notification display with a minimal, OLED-friendly one. The core app is free, with an optional paid "AuraLook Pro" upgrade and optional tips. AuraLook is provided "AS IS".

## Summary

AuraLook processes notification content on your device. The app does not send your personal information, notification content, or usage data to the developer or third parties. It does not request the Android `INTERNET` permission and contains no analytics, advertising, crash reporting, or account system.

## Notification Content

AuraLook uses Android notification access to read incoming and active notifications. It can display the app icon, title, text, and any contact photo or image supplied with a notification. The Pro "Privacy Mode" can hide titles and text inside AuraLook.

AuraLook keeps notification text and images in memory while handling active notifications and never writes that content to storage or sends it off your device. Optional missed-notification reminders use the notification identifiers described below.

You can assign a gesture to open a notification in its source app or dismiss an eligible notification from Android's notification shade. Swipe down is the default gesture for dismissal, and you can turn off its confirmation prompt in settings. AuraLook does not mark notifications as read when it dismisses them.

## Data Stored on Your Device

AuraLook stores the following in private app storage on your device.

- **Your settings**, such as theme, timeout, and gesture assignments.
- **Your app filter list**, which contains the package names of the apps you choose to block.
- **Pro purchase receipt**, which AuraLook uses to keep Pro unlocked offline.
- **Reminder state**, if you enable missed-notification reminders. AuraLook saves notification identifiers, attempt counts, and timing. It stores no notification text or images in this state.

AuraLook opts out of Android's automatic cloud backups. Android may still transfer private app data directly between devices, depending on the device manufacturer. Clearing the app's data or uninstalling it removes this private app data from that device.

## Settings Backup

In **Advanced → Settings backup**, you can export your settings as a local JSON file or import a backup using Android's file picker. The file contains preferences, including gesture assignments and reminder preferences, and any saved app filter package names. It excludes notification content, purchase receipts, Pro unlock status, and reminder history or pending reminders.

You choose where to save the file. AuraLook does not upload it. A copy saved outside AuraLook's private app storage remains available after you clear app data or uninstall AuraLook. You can delete it using your file manager.

## Permissions and Special Access

AuraLook uses these permissions and special access on your device.

| Permission / access | Why it's needed |
|---|---|
| Notification access | To detect, display, and browse notifications, identify missed notifications for optional reminders, and dismiss eligible notifications when you use the assigned gesture |
| Accessibility service | Only to lock the device and turn off the screen after a display timeout, when you use the Sleep screen gesture, or when a reminder glance times out or you use its sleep action. It ignores accessibility events and cannot read screen content |
| Display over other apps | To show AuraLook on top of the lock screen |
| Do Not Disturb access | To temporarily suppress system heads-up banners while AuraLook is showing, then restore your previous setting |
| Secure settings (`WRITE_SECURE_SETTINGS`), optional | Not granted by default. If you grant it via ADB or [Shizuku](https://shizuku.rikka.app/), AuraLook toggles the system heads-up banner setting while showing a notification and restores it afterward |
| Exact alarms | To time optional missed-notification reminders |
| Wake lock, vibrate, post notifications | To wake the screen, give haptic feedback, and show standard Android notifications |
| Ignore battery optimizations, boot completed | To keep AuraLook running reliably and restore its state after a restart |
| Query all packages | To list your installed apps in the app filter screen. AuraLook saves only the package names you select for filtering |

When Pocket Mode is enabled, AuraLook may briefly read your proximity, light, and motion sensors to detect whether the phone is in a pocket or bag. These readings are used immediately and are not stored or transmitted.

## In-App Purchases

AuraLook uses the Google Play Billing Library for the "AuraLook Pro" upgrade and optional tips. Google Play processes payments and supplies purchase information, including a signed receipt that AuraLook uses to verify your purchase. AuraLook has no access to your card, billing address, or other payment details. Google's handling of your data is covered by [Google's Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

AuraLook does not collect personal information from children or other users.

## Changes to This Policy

If this policy changes, the updated version will be posted on the [AuraLook privacy policy page](https://blasteroverlord.github.io/privacy-policies/AuraLook/) with a revised "Last updated" date.

## Contact

If you have questions about this privacy policy, email **[blasteroverlord10@gmail.com](mailto:blasteroverlord10@gmail.com)**.
