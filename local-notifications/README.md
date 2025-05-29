# @dharma-code-chris/capacitor-local-notifications

This is a fork of the official Capacitor Local Notifications plugin.

## Install

```bash
npm install @dharma-code-chris/capacitor-local-notifications
npx cap sync
```

# Modifications

## Android

- Modified `LocalNotificationManager`, adding the `every` schedule value to affect the repeating interval so that alarms can be configured repeating based on `at` with a configurable repeating interval.
- Changed repeating alarms from type `AlarmManager.RTC` to type `AlarmManager.RTC_WAKEUP`.

## iOS

- None yet, but when work begins on iOS version of our app we will be updating the iOS fork to align with Android.
