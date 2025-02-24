# ObjectBox Flutter Database Performance Benchmarks

## Setup

As usual run `flutter pub get`.

## Running

Make sure to run the app in release mode to avoid any performance penalties from
debug mode. (Note: release mode is not supported on the iOS simulator, a real
device is required.)

To run in release mode with Android Studio connect a device or start an
emulator, then Run > Flutter Run 'main.dart' in Release Mode.

Or run `flutter run --release`.

To further improve performance, make sure to disconnect dev tools. E.g. stop the
app on the device and launch it again.

## Implementation notes

### Hive

- No test with index as Hive does not support explicit indexes.

### Isar

- Skipped as Isar is not mainained.

## Results

Check this
[URL](https://docs.google.com/spreadsheets/d/1LjhgZ-CgvmzinKK5YrA8G3gLBl54D9RtegrHIKQNtSU/edit?usp=sharing).
