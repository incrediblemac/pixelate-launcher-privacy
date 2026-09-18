# Privacy Policy — Pixelate Launcher

**Last updated: September 18, 2026 (recent searches)**

This privacy policy applies to **Pixelate Launcher** (package `com.pixelate.launcher`), an Android home-screen app ("the app", "we", "us").

## Summary

Pixelate Launcher works almost entirely on your device. It has **no accounts, no ads, no analytics, and no third-party tracking SDKs**. The only information that leaves your device is your **approximate location (rounded to about 1 km)**, sent to a weather service to show the current weather, and only if you allow location access.

## Information stored on your device

The app saves the following in its private storage on your phone. It is never uploaded to us:

- Your settings (grid size, icon shape, label options, dock options, themed icons, notification badges and their style, drawer blur, temperature unit, what tapping the weather does, double-tap to lock).
- The apps and app shortcuts you placed on the home screen and dock, and their positions.
- The IDs, positions and sizes of widgets you added to the home screen.
- Your last 5 app-drawer searches (only searches you acted on), shown as "recent searches" when you tap the empty search box. You can clear them there with "Clear recent searches".
- How many times you opened each app from the launcher, used to show "suggested apps" in the app drawer.
- The last weather result (temperature, condition, time), so weather shows while offline.
- Whether you have already been asked for location access or shown the accessibility tip.

## Permissions and why we use them

- **Approximate location** (`ACCESS_COARSE_LOCATION`) — *optional*. Used only to show local weather. Before the system asks, the app explains what is sent. If you decline, weather is shown for a default city. You can revoke it any time in Settings → Apps → Pixelate Launcher → Permissions.
- **Contacts** (`READ_CONTACTS`) — *optional, never requested on its own*. Search in the app drawer can show contacts whose names match what you type. The permission is only asked for when you tap "Search your contacts" in the search results; if you decline, the app stops offering it. Matching contacts (name and photo thumbnail) are looked up on your device while you search, held only in memory to display the results, and are **never stored, uploaded or shared**. Tapping a contact opens it in your contacts app. You can revoke it any time in Settings → Apps → Pixelate Launcher → Permissions.
- **Internet** (`INTERNET`) — used only for the weather request described below.
- **See all installed apps** (`QUERY_ALL_PACKAGES`) — required to list your apps in the launcher. The app list stays on your device.
- **Request app uninstall** (`REQUEST_DELETE_PACKAGES`) — lets you start uninstalling an app from its menu. Android always asks you to confirm.
- **Expand status bar** (`EXPAND_STATUS_BAR`) — lets a swipe down on the home screen open the notification shade.
- **Notification access** — *optional, off by default*. If you enable it, the launcher checks **which apps** currently have notifications so it can show notification dots. It does **not** read, store or send notification content. You can turn it off in Settings → Notifications → Device & app notifications.
- **Accessibility service ("Pixelate Launcher gestures")** — *optional, off by default*. It is used for exactly two actions you trigger on the home screen: **locking the screen when you double-tap** an empty spot, and **opening the notification shade when you swipe down** (on devices that block launchers from doing this directly). It does **not** read screen content, observe what you type, or collect any data. You can turn it off in Settings → Accessibility, and double-tap to lock can be switched off in the launcher's menu.
- **Widgets** — if you add a widget, Android asks you to allow the launcher to display it. The widget's content comes from the app that provides the widget.
- **App shortcuts** — as your home app, the launcher can show an app's shortcuts (for example "New chat") in its long-press menu and pin the ones you drag to the home screen. This uses Android's standard shortcut access for home apps; shortcut names and icons stay on your device.
- **Work profile** — if your device has a work profile, its apps are shown with a badge. No work data is accessed beyond the app list Android provides to launchers.

## Network requests

- **Open-Meteo (api.open-meteo.com)** — to get the current weather, the app sends your **latitude and longitude rounded to two decimal places (about 1 km)** over an encrypted HTTPS connection. No name, account, device ID or other identifier is sent. Like any web server, Open-Meteo receives your IP address to answer the request. Requests are made at most about every 30 minutes, or when you tap the weather. See the [Open-Meteo terms and privacy policy](https://open-meteo.com/en/terms).

The app makes no other network requests.

## Third-party services and SDKs

Apart from the Open-Meteo weather request, the app contains **no third-party SDKs** — no analytics, crash reporting, advertising or attribution libraries.

## Data shared with others

We do not share or sell any data. When **you** choose to — for example, searching the web, opening a contact or a settings page from search, tapping the weather, opening the calendar, voice search, or uninstalling an app — the launcher opens another app on your device, and that app's own privacy policy applies to what you do there.

## Backups

The app allows Android's standard backup. If backup is turned on for your device, the on-device settings listed above may be included in your personal Android / Google account backup, which is controlled by you and by Google. We cannot access it.

## Data retention and deletion

- All app data stays on your device until you clear it: Settings → Apps → Pixelate Launcher → Storage → Clear storage, or uninstall the app.
- We keep no data on our own servers, so there is nothing for us to delete. If you have questions, contact us below.

## Security

The weather request uses HTTPS encryption. Search text, calculator and unit-conversion results and contact lookups are processed only on your device (a calculator result is copied to your clipboard only when you tap it). All other data is kept in the app's private storage, which other apps cannot read.

## Children's privacy

Pixelate Launcher is a general-audience app and is not directed at children under 13. We do not knowingly collect personal information from children.

## What we do NOT do

- No account or sign-in.
- No advertising or advertising ID.
- No analytics, tracking, or crash reporting.
- No reading of notification content or screen content.
- No uploading, storing or sharing of your contacts — they are only looked up on your device when you search.
- No selling or sharing of your data.
- No precise location — only approximate location, rounded to about 1 km, and only if you allow it.

## Changes to this policy

If the app's data practices change, we will update this page and the "Last updated" date above.

## Contact

- Open an issue: <https://github.com/incrediblemac/pixelate-launcher-privacy/issues>
- Email: **fullscreendev@gmail.com**

---

*Pixelate Launcher is an independent app and is not affiliated with, endorsed by, or sponsored by Google LLC. Android, Google and Pixel are trademarks of Google LLC. Open-Meteo is a trademark of its respective owner.*
