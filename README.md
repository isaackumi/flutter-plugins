# Flutter plugins

[![Build Status](https://api.cirrus-ci.com/github/truongsinh/flutter-plugins.svg)](https://cirrus-ci.com/github/truongsinh/flutter-plugins/master)
[![codecov](https://codecov.io/gh/truongsinh/flutter-plugins/branch/master/graph/badge.svg)](https://codecov.io/gh/truongsinh/flutter-plugins)

This repo is a **fork** of [companion repo](https://github.com/flutter/plugins) to the main [flutter
repo](https://github.com/flutter/flutter).

## Visions
- Visible unit test coverage
- Unit test for all parts (dart, ios, android)
- Convert all plugins to Swift/Kotlin for better engagement with the community using modern languages
- Ultimately merged back to upstream

## Unmerged to upstream
- test coverage for dart, ios and java [flutter/plugins#1032](https://github.com/flutter/plugins/pull/1032), [flutter/plugins#1036](https://github.com/flutter/plugins/pull/1036)
  - dummy test dart [#13](https://github.com/truongsinh/flutter-plugins/pull/13)
  - dummy test android [#12](https://github.com/truongsinh/flutter-plugins/pull/12), [#14](https://github.com/truongsinh/flutter-plugins/pull/14), [#15](https://github.com/truongsinh/flutter-plugins/pull/15),
- unit test for `device_info` [flutter/plugins#975](https://github.com/flutter/plugins/pull/975)
- fix [flutter/flutter#21863](https://github.com/flutter/flutter/issues/21863) image_picker: FATAL EXCEPTION when choosing an image from downloads
[flutter/plugins#986](https://github.com/flutter/plugins/issues/986)
- changed files after running flutter build (for ios) [#11](https://github.com/truongsinh/flutter-plugins/pull/11)

## Plugins
These are the available plugins in this repository. The coverage badges of each plugin are manually generated now, see [my tweet](https://twitter.com/truongsinhtn/status/1082253861195108354)

| Plugin | Pub | Coverage |
|--------|-----| -------- |
| [android_alarm_manager](./packages/android_alarm_manager/) | [![pub package](https://img.shields.io/pub/v/android_alarm_manager.svg)](https://pub.dartlang.org/packages/android_alarm_manager) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/android_alarm_manager.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/android_alarm_manager)
| [android_intent](./packages/android_intent/) | [![pub package](https://img.shields.io/pub/v/android_intent.svg)](https://pub.dartlang.org/packages/android_intent) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/android_intent.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/android_intent)
| [battery](./packages/battery/) | [![pub package](https://img.shields.io/pub/v/battery.svg)](https://pub.dartlang.org/packages/battery) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/battery.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/battery)
| [camera](./packages/camera/) | [![pub package](https://img.shields.io/pub/v/camera.svg)](https://pub.dartlang.org/packages/camera) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/camera.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/camera)
| [connectivity](./packages/connectivity/) | [![pub package](https://img.shields.io/pub/v/connectivity.svg)](https://pub.dartlang.org/packages/connectivity) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/connectivity.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/connectivity)
| [device_info](./packages/device_info/) | [![pub package](https://img.shields.io/pub/v/device_info.svg)](https://pub.dartlang.org/packages/device_info) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/device_info.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/device_info)
| [google_maps_flutter](./packages/google_maps_flutter) | [![pub package](https://img.shields.io/pub/v/google_maps_flutter.svg)](https://pub.dartlang.org/packages/google_maps_flutter) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/google_maps_flutter.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/google_maps_flutter)
| [google_sign_in](./packages/google_sign_in/) | [![pub package](https://img.shields.io/pub/v/google_sign_in.svg)](https://pub.dartlang.org/packages/google_sign_in) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/google_sign_in.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/google_sign_in)
| [image_picker](./packages/image_picker/) | [![pub package](https://img.shields.io/pub/v/image_picker.svg)](https://pub.dartlang.org/packages/image_picker) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/image_picker.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/image_picker)
| [local_auth](./packages/local_auth/) | [![pub package](https://img.shields.io/pub/v/local_auth.svg)](https://pub.dartlang.org/packages/local_auth) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/local_auth.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/local_auth)
| [package_info](./packages/package_info/) | [![pub package](https://img.shields.io/pub/v/package_info.svg)](https://pub.dartlang.org/packages/package_info) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/package_info.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/package_info)
| [path_provider](./packages/path_provider/) | [![pub package](https://img.shields.io/pub/v/path_provider.svg)](https://pub.dartlang.org/packages/path_provider) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/path_provider.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/path_provider)
| [quick_actions](./packages/quick_actions/) | [![pub package](https://img.shields.io/pub/v/quick_actions.svg)](https://pub.dartlang.org/packages/quick_actions) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/quick_actions.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/quick_actions)
| [sensors](./packages/sensors/) | [![pub package](https://img.shields.io/pub/v/sensors.svg)](https://pub.dartlang.org/packages/sensors) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/sensors.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/sensors)
| [share](./packages/share/) | [![pub package](https://img.shields.io/pub/v/share.svg)](https://pub.dartlang.org/packages/share) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/share.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/share)
| [shared_preferences](./packages/shared_preferences/) | [![pub package](https://img.shields.io/pub/v/shared_preferences.svg)](https://pub.dartlang.org/packages/shared_preferences) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/shared_preferences.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/shared_preferences)
| [url_launcher](./packages/url_launcher/) | [![pub package](https://img.shields.io/pub/v/url_launcher.svg)](https://pub.dartlang.org/packages/url_launcher) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/url_launcher.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/url_launcher)
| [video_player](./packages/video_player/) | [![pub package](https://img.shields.io/pub/v/video_player.svg)](https://pub.dartlang.org/packages/video_player) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/video_player.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/video_player)
| [webview_flutter](./packages/webview_flutter/) | [![pub package](https://img.shields.io/pub/v/webview_flutter.svg)](https://pub.dartlang.org/packages/webview_flutter) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/webview_flutter.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/webview_flutter)
| | |
| **FlutterFire Plugins** |  |
| [cloud_firestore](./packages/cloud_firestore/) | [![pub package](https://img.shields.io/pub/v/cloud_firestore.svg)](https://pub.dartlang.org/packages/cloud_firestore) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/cloud_firestore.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/cloud_firestore)
| [cloud_functions](./packages/cloud_functions/) | [![pub package](https://img.shields.io/pub/v/cloud_functions.svg)](https://pub.dartlang.org/packages/cloud_functions) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/cloud_functions.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/cloud_functions)
| [firebase_admob](./packages/firebase_admob/) | [![pub package](https://img.shields.io/pub/v/firebase_admob.svg)](https://pub.dartlang.org/packages/firebase_admob) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_admob.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_admob)
| [firebase_analytics](./packages/firebase_analytics/) | [![pub package](https://img.shields.io/pub/v/firebase_analytics.svg)](https://pub.dartlang.org/packages/firebase_analytics) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_analytics.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_analytics)
| [firebase_auth](./packages/firebase_auth/) | [![pub package](https://img.shields.io/pub/v/firebase_auth.svg)](https://pub.dartlang.org/packages/firebase_auth) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_auth.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_auth)
| [firebase_core](./packages/firebase_core/) | [![pub package](https://img.shields.io/pub/v/firebase_core.svg)](https://pub.dartlang.org/packages/firebase_core) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_core.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_core)
| [firebase_database](./packages/firebase_database/) | [![pub package](https://img.shields.io/pub/v/firebase_database.svg)](https://pub.dartlang.org/packages/firebase_database) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_database.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_database)
| [firebase_dynamic_links](./packages/firebase_dynamic_links/) | [![pub package](https://img.shields.io/pub/v/firebase_dynamic_links.svg)](https://pub.dartlang.org/packages/firebase_dynamic_links) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_dynamic_links.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_dynamic_links)
| [firebase_messaging](./packages/firebase_messaging/) | [![pub package](https://img.shields.io/pub/v/firebase_messaging.svg)](https://pub.dartlang.org/packages/firebase_messaging) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_messaging.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_messaging)
| [firebase_ml_vision](./packages/firebase_ml_vision/) | [![pub package](https://img.shields.io/pub/v/firebase_ml_vision.svg)](https://pub.dartlang.org/packages/firebase_ml_vision) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_ml_vision.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_ml_vision)
| [firebase_performance](./packages/firebase_performance/) | [![pub package](https://img.shields.io/pub/v/firebase_performance.svg)](https://pub.dartlang.org/packages/firebase_performance) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_performance.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_performance)
| [firebase_remote_config](./packages/firebase_remote_config/) | [![pub package](https://img.shields.io/pub/v/firebase_remote_config.svg)](https://pub.dartlang.org/packages/firebase_remote_config) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_remote_config.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_remote_config)
| [firebase_storage](./packages/firebase_storage/) | [![pub package](https://img.shields.io/pub/v/firebase_storage.svg)](https://pub.dartlang.org/packages/firebase_storage) | [![](https://img.shields.io/endpoint.svg?url=https://flutter-plugins-coverage.netlify.com/firebase_storage.json)](https://codecov.io/gh/truongsinh/flutter-plugins/tree/master/packages/firebase_storage)

Learn more about [FlutterFire](https://github.com/flutter/plugins/blob/master/FlutterFire.md).
