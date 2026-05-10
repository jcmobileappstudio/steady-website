---
title: Privacy Policy
description: How Steady handles your data, in plain language.
permalink: /privacy/
---

# Privacy Policy

**Last updated: May 10, 2026**

Steady is a sleep tracker for shift workers, built and operated by **JC Mobile App Studio LLC** ("we", "us"). This policy explains what data Steady collects, what it doesn't collect, and the choices you have.

In plain English: Steady is a local-first app. Your sleep, schedule, and personal data stay on your iPhone (and your Apple Watch and iCloud account, if you've enabled iCloud sync in iOS Settings). We do not run a backend server. We do not see your data. We do not sell, share, or analyze your data.

If that's all you needed to know, you can stop here. The rest of this page covers the specifics, edge cases, and your rights under privacy laws.

---

## 1. What data Steady stores on your device

Steady stores the following on your iPhone, only on your device:

- **Sleep sessions**: bedtime, wake time, asleep duration, optional quality rating, optional notes, source (manual entry or Apple HealthKit), nap flag.
- **Shift pattern**: the work pattern you select or build during onboarding (DuPont, 4-on-4-off, custom, etc.) including start time, anchor date, and shift length.
- **Calendar overrides**: any per-day exceptions you've made to your default schedule (vacation, swap, PTO, etc.).
- **Caffeine log**: amount in milligrams and timestamp for each entry you log.
- **Smart wake history**: the wake-window settings and motion-derived alertness score for each smart-wake session.
- **Computed fatigue scores**: derived from your sleep + shift data.
- **App settings and preferences**: notification toggles, sleep target, light reminder preferences, language, theme.
- **Subscription status**: whether your in-app purchase is active or in trial. Apple handles the actual billing.

Steady does not collect or store any of the following: your name, email, phone number, photos, location, contacts, calendar events outside the app, microphone audio, camera, biometric identifiers, advertising identifier, or any device fingerprint.

## 2. Apple HealthKit

If you grant Steady permission to read sleep data from Apple HealthKit, the app pulls your sleep sessions from HealthKit into Steady's local storage so you can see them alongside manually-logged sessions.

We never write any data back to HealthKit. We only read from it.

You can revoke HealthKit access at any time in iOS Settings > Privacy & Security > Health > Steady. If you do, Steady stops syncing new data immediately. The sessions Steady has already imported remain in Steady's local database until you delete them.

We do not transmit HealthKit data anywhere. Apple's HealthKit framework prevents us from doing so even if we wanted to. HealthKit data stays inside the bounds of your device, your Apple ID, and Apple's encrypted services.

## 3. Apple Watch (optional)

If you have an Apple Watch and the Steady Watch app installed, Steady syncs a small snapshot of your current data to the watch (fatigue score, next shift, last sleep, today's caffeine total). This sync uses Apple's WatchConnectivity framework and stays inside Apple's encrypted device-to-device pipeline. We never see this data.

If you log a quick nap from the watch, the watch sends a message back to the iPhone using the same framework, the iPhone records the nap in your local database. Same applies to any Watch face complications you set up.

## 4. iCloud (optional)

Steady does not use a custom iCloud container. If you have iCloud Backup enabled in iOS Settings, your iPhone may include Steady's data in your encrypted iCloud Backup, this is Apple's behavior, not ours. Apple controls and encrypts that backup.

## 5. Notifications

Steady sends local notifications for nap reminders, bedtime reminders, light-exposure reminders, and drive-home risk alerts. These are scheduled by your iPhone using the standard iOS UserNotifications framework. They do not leave your device. We do not receive any signal when a notification fires or when you interact with it.

You can disable notifications globally in iOS Settings > Notifications > Steady, or per-category inside Steady's Settings.

## 6. In-App Purchases (subscription)

Steady offers an optional Pro subscription processed entirely by Apple's StoreKit. When you purchase a subscription:

- Apple processes the payment using your Apple ID.
- Apple, not Steady, has access to your payment information (credit card, billing address, etc.).
- Steady receives a verified entitlement token from Apple confirming your subscription is active. This token does not include personal payment information.
- We use the token only to unlock Pro features inside the app on your device.

Apple's privacy policy applies to the payment portion of this transaction: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)

We do not run a subscription server. We do not have a database of who is subscribed.

## 7. Analytics, tracking, and third-party SDKs

Steady contains no analytics, no crash-reporting SDK, no advertising SDK, no marketing SDK, and no other third-party software development kits that collect or transmit any data. The app is built only on Apple frameworks (SwiftUI, SwiftData, HealthKit, StoreKit, WatchConnectivity, UserNotifications, WidgetKit, ActivityKit).

We do not use Facebook Pixel, Google Analytics, Firebase, Mixpanel, Amplitude, AppsFlyer, Adjust, Branch, or any similar tools.

We do not track you across other apps or websites. We do not use the Identifier for Advertisers (IDFA). Steady does not present an App Tracking Transparency prompt because there is nothing to track.

## 8. Data export

You can export all your Steady data at any time via Settings > Export your data. The export is a CSV file you can save, email, or share through any iOS app. The export contains your sleep sessions and shift override history. It is generated on your device, we do not see it.

## 9. Data deletion

To delete all your Steady data, you have two options:

1. **Delete the Steady app from your iPhone.** This removes all of Steady's local data immediately. (HealthKit data, which lives in Apple's Health app, is not affected.)
2. **Reset within the app** via the recovery screen if you encounter a database error, this wipes Steady's local SwiftData store.

Because Steady has no server, there is no separate account or cloud database to delete. Deleting the app deletes the data.

## 10. Your rights under GDPR, CCPA, and other privacy laws

Even though Steady does not collect personally identifiable information that would normally trigger these laws, we still want you to know the rights you have:

- **Right to know what we collect**: this entire policy.
- **Right to access your data**: use Settings > Export your data.
- **Right to delete your data**: delete the app.
- **Right to portability**: the CSV export is portable to any other tool.
- **Right to non-discrimination**: we do not condition app access on data sharing because there's nothing to share.
- **Right to opt out of sale of personal information**: we do not sell any data, ever.

If you are a resident of the European Union, the United Kingdom, California, Colorado, Virginia, Connecticut, Utah, or any other jurisdiction with privacy laws, the rights above apply to you regardless of jurisdiction.

## 11. Children

Steady is not directed to children under 13 (or under 16 in jurisdictions where that is the applicable age of digital consent). We do not knowingly collect data from children. If a parent or guardian discovers that a child has been using Steady, they can simply delete the app to remove all associated data.

## 12. Security

Because all your Steady data lives on your iPhone, the security of that data depends on the security of your iPhone. We strongly recommend:

- Use a passcode (or Face ID / Touch ID) on your iPhone.
- Enable Find My iPhone.
- Keep iOS up to date.

For data that briefly transits between your iPhone and Apple Watch via WatchConnectivity, that channel is encrypted by Apple end-to-end. We have no access to it.

## 13. Changes to this policy

We may update this privacy policy when the app changes or when laws change. The "Last updated" date at the top reflects the most recent change. For material changes, we will surface a notice inside the Steady app on next launch.

## 14. Contact

If you have questions about this privacy policy, want to exercise any of the rights above, or believe Steady has handled your data improperly, please reach out:

- Email: **jcmappstudio@gmail.com**
- Mailing address available on request: write us at the email above and we will provide it.

We will respond to verifiable requests within 30 days.

---

*Steady is operated by JC Mobile App Studio LLC. This policy is governed by the laws of the United States and the state where JC Mobile App Studio LLC is registered. Written for humans first.*
