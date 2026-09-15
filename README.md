# Bitaniya Bible Study

A Flutter Bible study journal and New Testament reading tracker.

## Included

- Home dashboard and progress
- Daily Study with multiple chapters per day
- Restored Chapter Study format
- Character Study
- Rich-text study fields
- Calendar and study history
- Statistics and streak tracking
- New Testament reading tracker (357 chapters)
- Search and study/character libraries
- Bookmarks/favorites
- Backup and restore
- Light/dark mode
- Local persistence with SharedPreferences
- Responsive Flutter UI for web and mobile

## Run

1. Create/enter a Flutter project folder.
2. Replace its `lib/main.dart` with the included `lib/main.dart`.
3. Use the included `pubspec.yaml`.
4. Run:

```bash
flutter pub get
flutter run -d chrome
```

For web deployment:

```bash
flutter config --enable-web
flutter build web --release
```

The generated `build/web` folder can be deployed to GitHub Pages.

## Important

The app stores study data locally in the browser/device. Use the Backup screen regularly if the data is important.
