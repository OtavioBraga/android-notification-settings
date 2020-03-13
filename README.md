# RN Android Notification Settings

This native module provides a method to directly open the notification settings' of your app on Android's system.

## Getting started

`$ yarn add android-notification-settings`

### Linking

`$ react-native link android-notification-settings`

## Usage

```ts
import AndroidNotificationSettings from "android-notification-settings";

AndroidNotificationSettings.openNotificationSettings(); // Opens app's system notification settings.
```
