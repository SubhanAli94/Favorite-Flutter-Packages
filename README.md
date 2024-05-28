# Favorite Flutter Packages
A collection of frequently used packages to save time for newbies.

## 1. flutter_launcher_icons<br>
  Add the icon in the assets/icon directory and add the following snippet in pubspec.yaml file.
```yaml
flutter_launcher_icons:
  android: "launcher_icon"
  ios: true
  image_path: "assets/icon/icon.png"
```
and run the following commands in terminal:
```bash
flutter pub get  
flutter pub run flutter_launcher_icons:main
```
