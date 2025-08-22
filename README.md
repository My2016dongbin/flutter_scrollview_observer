![](https://github.com/LinXunFeng/flutter_assets/raw/main/flutter_scrollview_observer/banner.png)

# Flutter ScrollView Observer

Language: English | [中文](https://github.com/My2016dongbin/flutter_scrollview_observer/blob/main/README-zh.md)


This is a library of widget that can be used to listen for child widgets those are being displayed in the scroll view.

## 🔨 Feature

> You do not need to change the view you are currently using, just wrap a `ViewObserver` around the view to achieve the following features.

- [x] Observing child widgets those are being displayed in ScrollView
- [x] Support for scrolling to a specific item in ScrollView
- [x] Quickly implement the chat session page effect
- [x] Support for keeping IM message position when inserting or updating messages, avoiding jitter.

## 🎀 Support

- [x] `PageView`
- [x] `ListView`
- [x] `SliverList`
- [x] `GridView`
- [x] `SliverGrid`
- [x] Mixing usage of `SliverPersistentHeader`, `SliverList` and `SliverGrid`
- [x] `NestedScrollView`
- [x] `ScrollView` built by third-party package.

## 🕹 Preview

- 🖥 [Online Preview](https://fluttercandies.github.io/flutter_scrollview_observer/)
- 🏞 [Sample images](https://github.com/fluttercandies/flutter_scrollview_observer/wiki/Example)

## 📦 Installing

Add `scrollview_observer` to your pubspec.yaml file:


```yaml
dependencies:
  scrollview_observer: latest_version
```

Import `scrollview_observer` in files that it will be used:

```dart
import 'package:scrollview_observer/scrollview_observer.dart';
```
