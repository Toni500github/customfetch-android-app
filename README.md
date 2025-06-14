<p align="center">
  <img src="assets/icons/logoAndroid.svg" width="30%"/>
</p>
<h2></h2> <!-- add a separating line -->
<p align="center">
    An android widget app for diplaying system information, which its focus point is the performance and <b>customizability</b>
</p>
<p align="center">
    <img src="https://img.shields.io/github/languages/top/Toni500github/customfetch?logo=kotlin&label=" />
    <img src="https://img.shields.io/github/actions/workflow/status/Toni500github/customfetch/makefile.yml" />
    <img src="https://img.shields.io/badge/Standard-C%2B%2B20-success" />
</p>
<img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Transparent_Square_Tiles_Texture.png" width="45%" height="14px" align="right" />
<img align=right width=54.2% src="screenshots/android_widget2.png"/>
<p align=left>
  <img width=42.45% src="screenshots/android_widget.jpg" />
</p>

# Installation
## Stable
Download the latest `.apk` file in the [releases](https://github.com/Toni500github/customfetch/releases/v1.0.0) \
AFAIK The google play protect doesn't detect any malware. If your antivirus does, please open an [issue here](https://github.com/Toni500github/customfetch-android-app/issues)

## Development
Download the latest apk build from the [GitHub actions](https://github.com/Toni500github/customfetch-android-app/actions/workflows/makefile.yml) artifacts\
If you can't download or you are not logged in GitHub, use this link: https://nightly.link/Toni500github/customfetch-android-app/workflows/makefile/main/customfetch-android-app.zip

# Build from source
```bash
# need java 17 + gradle 8.9 installed.
# It's suggested to build from android studio,
# so you that you can install the NDK library
./gradlew assembleDebug
```
