# The Tomotoru Revival Project

We preserve the Android edition of **Tomotoru** (*Hello Kitty Happy Life*), originally released by CyberStep, and work to make it playable again.

[Project website](https://bringbacktomotoru.github.io/) · [Android releases](https://github.com/bringbacktomotoru/builds/releases) · [Technical wiki](https://github.com/bringbacktomotoru/game/wiki)

## Play Tomotoru

Get both revival editions from the [v0.3.0 Android release](https://github.com/bringbacktomotoru/builds/releases/tag/v0.3.0).

- **Offline APK:** The server is built into the app. You can play without Internet or a separate server. Progress is saved on your device.
- **Official Online APK:** The app connects over the Internet to the server run by this project's maintainer. The server must be available to play, and your progress is saved there.

The [v0.0.1 archive](https://github.com/bringbacktomotoru/builds/releases/tag/v0.0.1) contains the unmodified original APK. It is neither revival edition.

## Repositories

| Repository | What it does |
| --- | --- |
| [**builds**](https://github.com/bringbacktomotoru/builds) | APK downloads, archival base assets, and the build and release workflows. Start here if you want to play. |
| [**game**](https://github.com/bringbacktomotoru/game) | Preserved Android client code, resources, and metadata. |
| [**tools**](https://github.com/bringbacktomotoru/tools) | APK builder, asset and bytecode tools, and integration tests. |
| [**server**](https://github.com/bringbacktomotoru/server) | Tomoserver, the JavaScript backend for online APKs. Run it locally with `online-test` or host your own server and build a custom APK. |
| [**offline**](https://github.com/bringbacktomotoru/offline) | Tomoffline, the Java server bundled into offline APKs. It serves assets and saves progress on the device, so no separate server is needed. |
