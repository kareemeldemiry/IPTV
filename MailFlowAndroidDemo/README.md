# MailFlow Android demo

This project is a native Android WebView shell. Its start screen is the English, left-to-right MailFlow interface. Selecting **Open Outlook Desktop** opens Outlook Web inside the application with desktop rendering settings enabled.

## What this demo includes

- A desktop-oriented browser configuration: wide viewport, overview mode, zoom controls, persistent cookies, and a desktop Chrome user agent.
- A native Android notification permission request and notification channel.
- The complete Outlook Web interface once Outlook is opened, so Outlook itself supplies compose, reply, forward, attachments, folders, search, archive, delete, and other mail controls.

## What is intentionally not connected yet

The notification channel is ready, but real new-mail alerts need a Microsoft Graph application registration and push-notification service. A background WebView is not a reliable or battery-safe way to detect mail while Android has closed the app.

## Build

Open this folder in Android Studio, let it install the Android Gradle Plugin, then choose **Run** on the phone. Android 13 and later will ask for notification permission on first launch.
