# STUDY_ZONE

Advanced offline-first student learning app built with HTML/CSS/JavaScript + Capacitor.

## Features
- Dashboard
- Subjects and chapters
- Search
- Notes and important points
- Chapter completion
- Bookmarks
- MCQ quiz engine
- Explanations and scoring
- Progress analytics
- Achievements
- Focus timer
- Study planner
- Dark mode
- Student profile
- Local storage
- Phone/tablet responsive UI

## Local build

```bash
npm install
npm run build
npx cap add android
npx cap sync android
cd android
./gradlew assembleDebug
```

APK:
`android/app/build/outputs/apk/debug/app-debug.apk`

## GitHub

Push the project to GitHub. The workflow in `.github/workflows/build.yml` automatically creates the APK and uploads it as the `STUDY_ZONE-apk` artifact.
