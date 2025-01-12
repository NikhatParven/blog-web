---
title: revanced-manager
date: 2023-09-26T12:16:52+08:00
draft: False
featuredImage: https://images.unsplash.com/photo-1692447265857-b44d118476d6?ixid=M3w0NjAwMjJ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2OTU3MDE2OTl8&ixlib=rb-4.0.3
featuredImagePreview: https://images.unsplash.com/photo-1692447265857-b44d118476d6?ixid=M3w0NjAwMjJ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2OTU3MDE2OTl8&ixlib=rb-4.0.3
---

# [ReVanced/revanced-manager](https://github.com/ReVanced/revanced-manager)

# 💊 ReVanced Manager

The official ReVanced Manager based on Flutter.

## 🔽 Download

You can obtain ReVanced Manager by downloading it from either [revanced.app/download](https://revanced.app/download) or [GitHub Releases](https://github.com/ReVanced/revanced-manager/releases)

## 📝 Prerequisites

1. Android 8 or higher
2. Incompatible with certain ARMv7 devices

## 📃 Documentation
The documentation can be found [here](https://github.com/revanced/revanced-manager/tree/main/docs).

## 🔴 Issues

For suggestions and bug reports, open an issue [here](https://github.com/revanced/revanced-manager/issues/new/choose).

## 🌐 Translation

[![Crowdin](https://badges.crowdin.net/revanced/localized.svg)](https://crowdin.com/project/revanced)

We're accepting translations on [Crowdin](https://translate.revanced.app).

## 🛠️ Building Manager from source

1. Setup flutter environment for your [platform](https://docs.flutter.dev/get-started/install)
2. Clone the repository locally
3. Add your GitHub token in gradle.properties like [this](/docs/4_building.md)
4. Open the project in terminal
5. Run `flutter pub get` in terminal
6. Then `flutter packages pub run build_runner build --delete-conflicting-outputs` (Must be done on each git pull)
7. To build release APK run `flutter build apk`
