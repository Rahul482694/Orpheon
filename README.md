# myspoty

**Preservation home of Myspoti 2.4.1, the last version of the Myspoti music player with Spotify login.**

## What is Myspoti?

Myspoti is a free, open-source music player for Android, Android TV and Wear OS, originally developed by [kota-zo](https://github.com/kota-zo). Up to version 2.4.1 it included a built-in Spotify client: you signed in through Spotify's own login page inside the app, and a **free Spotify account was enough** (no Premium needed).

In November 2026, after a copyright complaint from Spotify, the author removed the Spotify engine, deleted the 2.4.1 release, and continued the app as [Orpheon](https://github.com/kota-zo/Orpheon) without Spotify support. That makes 2.4.1 the last Spotify-capable version.

## Download

Get the verified original APK from the [Releases page](https://github.com/Rahul482694/myspoty/releases):

| File | Devices |
| --- | --- |
| `Myspoti-2.4.1-ARMv8.apk` | 64-bit ARM phones and tablets, Android 10+ |

SHA-256: `f8301f96452d9be0848573315fdb0572986f788caa8707601945f074f68140a5`

The APK is byte-identical to the file the author originally published on GitHub (checksum verified against the archived release page). Check the hash after downloading:

```
sha256sum Myspoti-2.4.1-ARMv8.apk
```

## Notes

- Requires **Android 10 or newer** (minSdk 29).
- Only the ARMv8 (arm64) build survived. The original ARMv7, TV and universal builds were deleted with the release and could not be recovered. This APK cannot run on 32-bit-only ARMv7 devices.
- Do not use the in-app update button: it points to Orpheon, which has no Spotify. Keep this APK.
- Myspoti is an unofficial Spotify client. Using it may violate Spotify's Terms of Service and carries a risk of action against your Spotify account. Use at your own risk. This project is not affiliated with Spotify.

## What is this repository?

A fork of [kota-zo/Orpheon](https://github.com/kota-zo/Orpheon), kept as the preservation home of Myspoti 2.4.1. The `spotify-login` branch holds an unfinished experiment to restore Spotify login on the current Orpheon codebase; it does not work and is parked.

## Credits and license

All credit for Myspoti and Orpheon goes to the original author, [kota-zo](https://github.com/kota-zo), and the project's contributors. The code is licensed under [GPL-3.0](LICENSE); the license and copyright notices are preserved as required.
