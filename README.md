# Android app RebootMonitor – website

Source of **[rebootmonitor.com](https://rebootmonitor.com/)**, the website of **RebootMonitor**, a free Android app that automatically tracks device restarts, uptime and reboot history.

[![Get it on Google Play](https://img.shields.io/badge/Google%20Play-RebootMonitor-168039?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=app.rebootmonitor.mobile)

## About the app

RebootMonitor shows you when your Android phone or tablet was last restarted and keeps a private history of every restart.

- Automatic reboot detection, current uptime and latest reboot at a glance
- Reboot history for up to 12 months, with a tap-to-inspect monthly heatmap
- Optional restart reminder after 3, 7 (recommended) or 14 days
- Home screen widget
- Built for personal phones as well as shared and Intune-managed Android devices
- Available in 10 languages
- Free, no ads, no account, no analytics. All data stays on the device.

## Pages

| Page | Topic |
|------|-------|
| [Home](https://rebootmonitor.com/) | Overview, screenshots, FAQ |
| [How to check when your Android phone was last restarted](https://rebootmonitor.com/check-last-reboot-android.html) | Three ways to find the last restart |
| [Does Android keep a reboot history?](https://rebootmonitor.com/does-android-keep-reboot-history.html) | What Android records, and what it does not |
| [Android Reboot Tracker](https://rebootmonitor.com/android-reboot-tracking.html) | Automatic restart logging |
| [Android Uptime Tracker](https://rebootmonitor.com/android-uptime-monitoring.html) | Live uptime on the device |
| [Android Reboot History & Uptime Report](https://rebootmonitor.com/android-device-uptime-report.html) | History and heatmap |
| [Reboot reminders](https://rebootmonitor.com/android-reboot-notification.html) | The configurable restart reminder |
| [Delayed reminders fix](https://rebootmonitor.com/fix-delayed-reminders.html) | Step-by-step battery setting guide |
| [Kiosk monitoring](https://rebootmonitor.com/android-kiosk-monitoring.html) | Unattended kiosks and signage |
| [Intune guide](https://rebootmonitor.com/intune-shared-devices.html) | Deploying to shared devices with Managed Home Screen |
| [Reboot monitoring for Intune](https://rebootmonitor.com/intune-shared-device-monitoring.html) | Monitoring a managed fleet |
| [Privacy policy](https://rebootmonitor.com/privacy.html) | What the app and the website do with data |

## About this repository

A plain static website (HTML, CSS and a little JavaScript), hosted on GitHub Pages. There is no build step and the site does not use analytics or tracking.

Two GitHub Actions keep search engines up to date after a push that changes pages: one updates `lastmod` in `sitemap.xml`, the other notifies Bing about changed pages.

Found an error on the site? Please [open an issue](https://github.com/vanderlindenno/RebootMonitor/issues). For app questions, use the contact form on the website.

## More apps

[UpdateMonitor](https://updatemonitor.app/) keeps a history of app updates, installs and removals on your Android phone and shows which apps can use sensitive permissions.

---

© 2026 Nordic Appworks. All rights reserved. Screenshots, text and logos may not be reused without permission.
