# Changelog

All notable changes to [Saltabo](https://saltabo.app), newest first.
Downloads: https://github.com/saltabo/saltabo/releases

## [1.3.6] - 2026-10-20

### Improved
- **A clear message when your license ends.** If your subscription ends or is refunded, Saltabo now tells you once and offers to renew or open the customer portal, instead of quietly turning Pro features off.
- **Clearer license errors.** Entering a key whose subscription has ended now explains that the license is no longer active, instead of calling the key invalid.
- If this Mac's activation was removed (for example from the customer portal), Saltabo tells you and lets you enter your key again.

### Fixes
- Licenses and trials work correctly again once Saltabo is back online, even if the Mac's clock was set wrong.

## [1.3.5] - 2026-10-18

### New
- **Liquid Glass.** On macOS 26 and later, the switcher and Dock previews use the new Liquid Glass look. You can turn it off in Settings → Appearance.
- **A purple Settings window**, matching the Saltabo brand.

### Improved
- **One look for the switcher and Dock previews:** frosted cards with a clear outline on the selected window, in both light and dark themes. Dock preview titles are now centered.
- **The dark switcher stays dark** even when your Mac uses the light appearance.
- **The Classic menu bar icon** now has a transparent background and follows a light or dark menu bar.
- Sharper style previews in Settings.

### Fixes
- With "All screens", windows on other desktops can now be closed and minimized from the switcher.
- Windows you closed no longer show up in the switcher when you switch from another desktop.

## [1.3.4] - 2026-10-17

### Important
- **Required update.** Saltabo now uses a new license server at saltabo.app. Earlier versions can no longer activate or verify licenses, so please update to keep Pro working.

### New
- **Lost your license key?** A new button in Settings → License opens the customer portal, where you can sign in with your purchase email to see your keys and activations.

### Changes
- The website, pricing page and support email moved to saltabo.app.

## [1.3.3] - 2026-10-16

### Improved
- **Smaller Dock previews by default**, plus a new Extra Large size. Padding, titles and buttons scale with the size you choose (Settings → Dock → Preview size).
- **Dock previews follow your theme** (light, dark or system), just like the switcher.
- **Full-screen windows are marked** with a badge in the switcher.
- **A refreshed switcher panel:** rounder corners, a frosted background and a soft shadow.
- **The search bar appears instantly**, with a lighter placeholder.

### Fixes
- Full-screen windows no longer show a minimize button, since macOS cannot minimize them.

## [1.3.2] - 2026-10-16

### Fixes
- **Update notes in your language.** When you choose a language in Saltabo, update notes and system dialogs now use it too (after Saltabo restarts).
- **Minimizing from the switcher** now removes the window from the switcher when minimized windows are hidden, instead of leaving it marked "Minimized". Hiding an app with H works the same way.
- **Restored windows come back:** if you restore a window while the switcher is open, it reappears in the switcher.

## [1.3.1] - 2026-10-16

### Improved
- **A cleaner switcher.** Each window is now a card with its app icon and title above a rounded preview, and the selected window is outlined in your accent color. Light and dark themes share the same layout, and the dark theme uses a neutral charcoal background.
- **Bigger previews** in the switcher, closer to the shape of your windows.
- **Neater close and minimize buttons:** smaller, tucked into the card's corner, crisp and centered, and they no longer cover the window title.
- **Tighter spacing** in the switcher and the Dock previews.

## [1.3.0] - 2026-10-15

### New
- **Free plan.** When the 14-day trial ends, Saltabo keeps working as a free app switcher instead of locking. Dock previews, search in the switcher, closing and minimizing windows, and excluded apps are Pro features.
- **Trial reminders.** A notification 3 days before the trial ends and on the last day. The menu bar menu shows how many trial days are left.
- **Close and minimize buttons** on switcher items and Dock preview thumbnails. With "One item per app", they act on all of the app's windows, and choosing a minimized app brings all its windows back.
- **Dock preview options:** preview size, distance from the Dock, and showing or hiding window titles.
- **Reorganized Settings** with new Dock and License tabs. The License tab shows your plan and which Pro features are included.

### Changes
- Licenses and trials are now verified by the Saltabo server. Activated licenses are checked again automatically and keep working offline for up to 30 days. Existing licenses are carried over; open Saltabo while online within 14 days.
- The W and M keys no longer close or minimize windows in the switcher; use the new buttons.
- Minimized windows and windows of hidden apps are no longer shown by default. Turn them back on in Settings > Controls.
- The menu bar icon is always shown.
- Clearer wording across Settings.

## [1.2.10] - 2026-10-14

### Fixes
- Dock previews and the app switcher no longer show windows you already closed (for example Keychain Access item windows).
- An app's main window now appears in its Dock preview even when its title is the app's name.

## [1.2.9] - 2026-10-14

### Fixes
- The Settings window no longer closes when you switch apps with the app switcher or use ⌘ shortcuts; it stays open behind the app you switch to.

## [1.2.8] - 2026-10-13

### New
- Close buttons: hover a window in the app switcher or in a Dock preview and click × to close it.
- Choose the key that opens search in the app switcher (Settings → Controls → Open search with). The default is still /.

### Improvements
- Dock previews sit closer to the Dock.

## [1.2.7] - 2026-10-13

### New
- Search in the app switcher: press / and type to filter apps and windows by name or title.
- Keyboard actions in the app switcher: ← → to move, ` to cycle through the selected app's windows, Q to quit, H to hide, M to minimize and W to close a window. Return opens the selection.
- New "Show list of windows" setting (Settings → Controls) to show every window as its own item.
- Apps that are hidden or only have minimized windows are badged and dimmed in the switcher.

### Improvements
- Saltabo is now fully translated in all supported languages, and the menu bar menu follows language changes right away.
- Window thumbnails are captured with ScreenCaptureKit: sharper and lighter on memory.
- Dock previews fit on screen when an app has many windows, and load faster.
- Cleaner Settings layout.

### Fixes
- Switching to another window of the same app (e.g. a second Chrome window) now brings that exact window to the front.
- Saltabo keeps checking for updates after the free trial ends, so you always get the latest fixes.

## [1.2.6] - 2026-10-12

### Fixes
- Fixed the app switcher being cut off at the right edge when an app was minimized just before opening it.

## [1.2.5] - 2026-10-12

### Updates
- Update prompts now include release notes, so you can see what's new before choosing Install Update, Skip This Version or Remind Me Later.

## [1.2.4] - 2026-10-12

### Updates
- Saltabo now asks before installing updates. When a new version is found, you can choose Install Update, Skip This Version or Remind Me Later — updates are no longer downloaded and installed silently.

## [1.2.3] - 2026-10-12

### Performance
- Greatly reduced background CPU usage: Saltabo no longer queries the Dock on every mouse movement, which also lowers CPU load from the Dock and launchservicesd.
