# Prayer Display Apps

[Download Prayer Display for Android](https://github.com/alimul-khan/PrayerDisplayApps/raw/refs/heads/main/PrayerDisplay.apk)

**Current version: 1.2 (version code 3).**

Requires Android 8 or later. Download the APK on your phone and open it to install, allowing installation from your browser or file manager if prompted.

For first use, enable a phone hotspot named `azanazan` with password `azanazan`, then tap **Find display**. The Pi must first have the [network setup installed](https://github.com/alimul-khan/AzanDisplay/blob/main/network/README.md). Administration opens without sign-in by default. You can also connect through the same home/mosque Wi-Fi using discovery or a saved IP.

The download URL stays the same for each new APK, so existing QR codes continue to work.

This APK is a debug-signed development build for direct installation.

[Source code and server setup](https://github.com/alimul-khan/AzanDisplay)

Version 1.2 improves discovery on phones with vendor-specific hotspot interfaces and clarifies that your phone is the hotspot host. If the Pi is visible in NetScan but not in the app, use **Connect** with its IP; the Pi must also be running the Prayer Display web server on port 5501.
