# iOS 12 Cydia repo

Cydia source: https://dreyzedev.github.io/

Packages:

- **Motion Walls 1.1.0** - live wallpapers: in-app catalog of wallpaper sites (anime, cars, games) with one-tap download, 24 built-in animated wallpapers (aurora, particles, liquid, waves, space) and any video or Live Photo from the gallery, on the lock screen, home screen or both. Depiction: `depictions/motionwalls.html`.
- **Lock Clock Studio 2.1.0** - iOS 16-26 style lock screen clock: 8 fonts, weight slider, numeral systems, solid/vibrant/Liquid Glass styles, separate time and date colors, tall clock, date above or below, with a live preview app. Replaces iOS 2 Lock Clock.
- **iOS 2 Lock Clock 1.0.0** - iOS 2 style analog lock screen clock tweak. Conflicts with Lock Clock Studio.
- **Telegram 10.0.3-3** - official Telegram build for iOS 11+ without Apple ID, with the update banner removed (needs MobileSubstrate).

Telegram is built from https://github.com/TelegramMessenger/Telegram-iOS (unsigned build 26855).

`Packages` and `Release` are hashed byte-for-byte, so `.gitattributes` disables line-ending conversion. Regenerate both indexes (root and `dists/stable/`) after adding a `.deb`.
