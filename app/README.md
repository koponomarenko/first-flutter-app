# app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Web app

```
flutter doctor
flutter config --enable-web
```

## Debug locally

```
flutter run -d chrome
```

## Deploy to Vercel

```
npm install -g vercel

flutter build web
vercel login
vercel --prod --cwd build/web
```

# Android App

```
flutter config --enable-android
```
