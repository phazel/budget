# Budget

This is an app for my personal budgeting. Right now it just reads from my personal budget spreadsheet on google docs and displays a summary. It's only intended for my own use.

## Setup

```bash
brew bundle
pub global activate fvm
fvm help # if this doesn't work, check output from previous command
fvm flutter pub get
fvm install 1.17.1
```

###### Dart versioning
- Upgrade: `brew upgrade dart`
- Switch versions: `brew switch dart 2.1.0`

<details>
  <summary><em>Guides used</em></summary>

  - [Install dart][dart] *(There are some dart version managers available but none seemed mature enough to use)*
  - [Install fvm][fvm]
  - [Using pub get][pub get]

  [dart]: https://dart.dev/get-dart
  [fvm]: https://pub.dev/packages/fvm
  [pub get]: https://flutter.dev/docs/development/packages-and-plugins/using-packages
</details>
