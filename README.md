![MiceWine Logo](img/MiceWine-Logo.png "MiceWine Logo")

# MiceWine

MiceWine is a project that aims to run Windows applications and games on Android smartphones.

It uses a customized build of Wine compiled for Android and Box86/Box64 to run in the best possible way, STILL IN DEVELOPMENT.

Please check newer APK version, this is outdated and no longer supported.

- [MiceWine-Application](https://github.com/KreitinnSoftware/MiceWine-Application)
- [MiceWine-RootFS-Generator](https://github.com/KreitinnSoftware/MiceWine-RootFS-Generator)

To install the Alpha version use on a clean Termux:

```bash
curl -O https://raw.githubusercontent.com/KreitinnSoftware/MiceWine/main/install-micewine.sh; bash install-micewine.sh; . $PREFIX/etc/termux-login.sh
```

If you want to update MiceWine (Only need the manual command in versions older than V7.2 and update is only supported now in V7.1)

```bash
curl -O https://raw.githubusercontent.com/KreitinnSoftware/MiceWine/main/update-micewine.sh
```

After installed, run `micewine` on your termux to open MiceWine.

⚠️ Install Termux and Termux-X11 from Releases Page ⚠️

### Compatible Android Versions

| Android    | Support     |
| ---------- | ----------- |
| Android 9  | Unsupported |
| Android 10 | Supported   |
| Android 11 | Supported   |
| Android 12 | Supported   |
| Android 13 | Supported   | 
| Android 14 | Supported   |

### Compatible GPUs

| GPU        | Support             | Driver            |
| ---------- | ------------------- | ----------------- |
| Adreno 7xx | Parcially Supported | VirGL/Zink        |
| Adreno 6xx | Supported           | Turnip/VirGL/Zink |
| Others     | Parcially Supported | VirGL/Zink        |

⚠️ In theory, any GPU that supports Vulkan should work with Zink, and any GPU should work through VirGL. ⚠️

# Open Source Applications used on MiceWine:

- [Box86](https://github.com/ptitSeb/box86)
- [Box64](https://github.com/ptitSeb/box64)
- [WineHQ](https://gitlab.winehq.org/wine/wine)
- [Termux](https://github.com/termux/termux-app)
- [Termux-X11](https://github.com/termux/termux-x11)
- [Mesa](https://gitlab.freedesktop.org/mesa/mesa)
