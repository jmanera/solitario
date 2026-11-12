# Solitario

Klondike solitaire for Android. The game is a single HTML page (`app/src/main/assets/index.html`) shown full screen in a WebView; it works offline and saves the current game automatically.

Features: draw 1 or 3, undo, drag or tap to move, double-tap to send a card to the foundation, auto-finish, move counter and timer.

## Download

Download [`dist/solitario-1.0.0.apk`](https://github.com/jmanera/solitario/raw/main/dist/solitario-1.0.0.apk) and open it on the device (allow installing from your browser when Android asks).

## Build

Requirements: JDK 17 and the Android SDK (platform 35).

```sh
./gradlew assembleRelease
# app/build/outputs/apk/release/app-release.apk
```

The release build is signed with the debug key so it installs directly; there is no Play Store listing.

## License

Apache-2.0
