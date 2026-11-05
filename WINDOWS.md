# ग्रंथ प्रबंधन — Windows launcher

Same Flutter app as [Goeh8080/Flutter-Granth](https://github.com/Goeh8080/Flutter-Granth), built for Windows.

## Download

Open **Actions** → **Build Windows launcher** → latest green run → download **Granth-Windows**.
Or open **Releases** and download `Granth-Windows.zip`.

Unzip and run `granthprabandhan.exe`.

## Build on your PC

```bash
flutter config --enable-windows-desktop
flutter create --platforms=windows .
flutter pub get
flutter build windows --release
```

Output: `build/windows/x64/runner/Release/`

Android-only pieces (Firebase Messaging, native Photo Highlighter activity, Play downloads) stay off on Windows. Catalog, PDF, search, AI and the rest of the UI are the same.
