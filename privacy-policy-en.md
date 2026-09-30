# Privacy Policy

**Effective Date**: September 30, 2026

---

## Introduction

MoGotcha ("the App") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our application.

## Information We Collect

**The App has no account system, operates no backend server, and the developer never receives any of your data.**

The following data, generated as you use the App, is stored on your own device by default. Only features you choose to turn on (iCloud auto backup, saving to the system photo library) place data in your own iCloud or photo library, as described below:

- **Photos**: Photos you take or select to record the subjects you've encountered (such as cats, dogs, insects, or anything in categories you create yourself)
- **Location Data**: Geographic location you authorize the App to capture when logging where you saw a subject
- **Subject & Bond Records**: The subject profiles, encounter counts, bond levels, and related progression data you create

## Data Storage & Usage

- **On-Device Storage by Default**: The data above is saved using on-device local storage by default. It is not sent to the developer, and there is no developer-operated server
- **iCloud Auto Backup (Optional, Off by Default)**: You can turn on "Auto Backup" in the App. When on, the App writes a full backup package — including photos, subject and encounter records, and the **precise location coordinates** you recorded — to the App's folder in your own iCloud Drive, on Wi-Fi and at most daily, keeping the latest 3 copies. These files are held by Apple's iCloud under your Apple account; the developer cannot access or receive them. You can turn it off at any time and delete existing backups in the Files app or iCloud storage settings. Separately, the App's manual backup export produces an archive file saved to a location you choose, kept entirely by you
- **Precise Location Is Not Made Public**: A subject's precise coordinates are kept on your device, in your own full backups, and in original photos you save to your own photo library. They never appear in shared images or any outward-facing output, and the developer never receives them
- **Maps and Place Features Use Apple Maps Services**: Map display, map pin selection, place search, converting coordinates to a city/district (reverse geocoding), and the small map preview in forms are handled by the system's Apple MapKit. Related coordinates or search terms are sent to Apple to obtain results and are governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). These requests do not pass through the developer, and the developer does not receive them
- **Shared Content Is Automatically Sanitized**: When you share or export content such as a bond card, the App automatically strips all EXIF metadata (including GPS coordinates) from the image. By default, shared images only display a "City · District" level location label. If you actively turn on "Include place name" in the photo-poster share settings, the poster instead shows the place name you picked or entered for that encounter (which may be a shop, attraction, or landmark). That switch is off every time you open the settings and applies only to that share. In every configuration, shared images never contain exact coordinates
- **No Photo Library Access for Picking**: When selecting a photo from your library, the App uses the system's out-of-process photo picker — the App itself is never granted read access to your photo library, and only receives the single photo you actively selected
- **Saving to Photos Requires Add-Only Permission**: When you save a share image, sticker, or photo to your system photo library, or turn on "Also save photos to Photos" in Preferences (off by default), the App requests "add photos only" permission. It can write to, but never read, your photo library. **Original photos saved to your library keep their EXIF information**, and the location you recorded is written into the photo. These photos live in your own library and, if you use iCloud Photos, sync to your iCloud according to your system settings. Keep in mind such photos may carry location information before you send them to others

## Permissions

The App may request the following device permissions, each used only to support its corresponding feature:

- **Camera**: To take photos of the subjects you encounter
- **Location (While Using the App)**: To record where you encountered a subject (kept on your device and in your own backups; automatically sanitized before sharing)
- **Photo Library Add (Add-Only)**: Used only when you actively save images to your system photo library or turn on "Also save photos to Photos"

We never collect your location in the background, and we never read any photos in your library beyond the one you actively select.

## Third-Party Services & Data Transmission

**The App does not integrate any third-party data collection, analytics, or advertising services.**

The App uses Apple's map services through the operating system (see above) and may integrate other optional services in future versions. These connections use only the operating system's built-in standard encryption and involve no proprietary or custom cryptographic algorithms. If you participate in testing via TestFlight, testing data (such as crash logs and screenshot feedback you voluntarily submit) is handled per Apple's standard TestFlight data-processing practices — see [Apple's TestFlight documentation](https://developer.apple.com/testflight/) for details.

## Data Security & Your Control

The developer does not hold your data, so you retain full control over your information:

- The App provides in-app deletion of individual records as well as a "wipe all data" option
- Uninstalling the App removes all locally stored data (photos, location records, subject and bond data). Your own iCloud auto-backup files and photos saved to your photo library are not removed with it; delete them yourself in the Files app / iCloud storage settings / Photos
- The developer operates no server and holds none of your data, so there is no "delete my cloud data" request to make to us; manage iCloud and Apple Maps–related data through your Apple account and system settings

## Children's Privacy

The App does not knowingly collect personal information from children. The App has no account system and does not collect personally identifiable information from users of any age.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Effective Date."

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:

- GitHub Issues: https://github.com/HatCloud/MoGotcha-Support/issues

---

**Developer**: Hat Studio
**Copyright**: © 2026 Hat Studio. All Rights Reserved
