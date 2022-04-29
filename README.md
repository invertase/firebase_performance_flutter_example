# Firebase Performance Example for Flutter

To initialize and configure Firebase see the [documentation](https://firebase.google.com/docs/flutter/setup?platform=android). After adding the `firebase_performance` monitoring plugin from Step 4 of the documentation, ensure you run `flutterfire configure` again.

Running android application:

- Ensure an Android Emulator is running.
- Find your device ID in `flutter devices list`
- Run the Flutter app against your device via `flutter run -d <deviceId>`, e.g. `flutter run -d emulator-5554`
- Once started, press any of the example buttons to submit traces/metrics.
  - First time apps may take a few minutes before
    the Firebase Console starts to show the application as integrated with Performance Monitoring. See [this link](https://firebase.google.com/docs/perf-mon/troubleshooting?authuser=0&hl=en&platform=android#sdk-not-detected) for information.
