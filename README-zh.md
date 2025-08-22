![](https://github.com/LinXunFeng/flutter_assets/raw/main/flutter_scrollview_observer/banner.png)

# Flutter ScrollView Observer


这是一个可用于监听滚动视图中正在显示的子部件的组件库。

## 🔨 功能点

> 不需要改变你当前所使用视图，只需要在视图外包裹一层即可实现如下功能点

- [x] 监听滚动视图中正在显示的子部件
- [x] 支持滚动到指定下标位置
- [x] 快速实现聊天会话列表的效果
- [x] 支持在插入或更新消息时保持IM消息位置，避免抖动

## 🎀 支持

- [x] `PageView`
- [x] `ListView`
- [x] `SliverList`
- [x] `GridView`
- [x] `SliverGrid`
- [x] 支持 `SliverPersistentHeader`，`SliverList` 和 `SliverGrid` 混合使用
- [x] `NestedScrollView`
- [x] 由第三方库构建的 `ScrollView`

## 🕹 预览

- 🖥 [在线预览](https://fluttercandies.github.io/flutter_scrollview_observer/)
- 🏞 [示例图片](https://github.com/fluttercandies/flutter_scrollview_observer/wiki/Example)

## 📦 安装

在你的 `pubspec.yaml` 文件中添加 `scrollview_observer` 依赖:

```yaml
dependencies:
  scrollview_observer: latest_version
```

在需要使用的地方导入 `scrollview_observer` :

```dart
import 'package:scrollview_observer/scrollview_observer.dart';
```

