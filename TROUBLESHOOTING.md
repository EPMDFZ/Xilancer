# Troubleshooting

## Flutter doctor issues

- Run `flutter doctor -v` and address any missing SDKs.

## Android build errors

- Ensure Android SDK and licenses are installed.
- Try `flutter clean` then `flutter pub get`.

## iOS build errors

- Ensure Xcode is installed and up to date (macOS only).
- Run `pod install` in `ios/` if CocoaPods is required.

## Web issues

- Clear Chrome cache and restart `flutter run -d chrome`.
