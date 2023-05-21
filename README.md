# NASA Wallpaper App in KMM (Kotlin Multiplatform Mobile)

Android UI in Jetpack Compose. iOS UI in SwiftUI. Shared code in Kotlin.

## How to run

### Android

1. Open the entire project in Android Studio

2. Run the app

![](/assets/Android.png)

### iOS

1. Open the project in Xcode (iosApp folder)

2. Run the app

![](/assets/iOS.png)

## How to UI test

The tests are located in the `.maestro` folder. To run the tests, you need to install [Maestro](https://maestro.mobile.dev/)

### Android

```
maestro test -e APP_ID=com.wallpapers.androidapp .maestro/wallpapers/ListDetailWallpaper.yaml
```

### iOS

```
maestro test -e APP_ID=com.wallpapers.iosapp .maestro/wallpapers/ListDetailWallpaper.yaml
```

## Thanks

This repository is a fork of https://github.com/mobile-development-group/NASAWallpaper. Thanks to the authors for the great work!