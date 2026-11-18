# Week 13B Starter - IGME-340

Today we give a Flutter app a custom icon and a splash screen, using RIT branding. It's a standalone exercise, separate from the asteroid game, so it doesn't matter where you are with earlier work.

This is a plain Hello World app with the default Flutter icon. Nothing is installed ahead of time: we add the icon files and the `flutter_native_splash` package together, following the [Week 13B notes](https://github.com/jptweb/IGME-340-Shared/blob/main/weekly/13B.md). Almost none of today's work is Dart code. It's image files and config in the `android/` and `ios/` folders.

## Get the Code

Work in your own repo (`igme-340-week-13b-starter-<your-github-username>`), not the template. Clone it with GitHub Desktop or the command line. Full steps: [Participation Repos](https://github.com/jptweb/IGME-340-Shared/blob/main/documents/participation.md).

Open the folder that *contains* `pubspec.yaml`, and don't clone into a path with spaces.

## Run It

```bash
flutter pub get
flutter run
```

Use the Android emulator if you can, since the icon and the splash screen are easiest to see there. You should see "Hello World!" and, on the home screen, the default Flutter logo as the app icon. Android build errors? See [Gradle Build Errors](https://github.com/jptweb/IGME-340-Shared/blob/main/reference/setup/gradle-build-errors.md).

## To Get Credit

Push before the start of class on Tuesday Nov 24. Your pushed code has to show:

- your custom icon files in the Android `mipmap-*` folders
- a `flutter_native_splash.yaml` and the splash screen it generated

Got screenshots of your icon and splash screen? Drag them into the project folder and push those too. The iOS icons, the tagline image, and the splash duration step are welcome but not required.

Missed class? Everything is in the notes. Still stuck? Slack me.
