# In App Purchase

A Flutter plugin for in-app purchases.

## Getting Started

This plugin is not ready to be used yet. Follow
[flutter/flutter#9591](https://github.com/flutter/flutter/issues/9591) for more
updates.

There's a significant amount of setup required for testing in app purchases
successfully, including registering new app IDs and store entries to use for
testing in both the Play Developer Console and App Store Connect. Both Google
Play and the App Store require developers to configure an app with in-app items
for purchase to call their in-app-purchase APIs. You can check out the [example
app](example/README.md) for an example on configuring both.

## Design

The API surface is stacked into 2 main layers.

1. [in_app_purchase.dart](lib/in_app_purchase.dart), the generic idiommatic
   Flutter API. This exposes the most basic IAP-related functionality. The goal
   is that Flutter apps should be able to use this API surface on its own for
   the vast majority of cases.

2. The dart wrappers around the platform specific IAP APIs and their platform
   specific implementations of the generic interface. See
   [google_play.dart](lib/google_play.dart) and
   [app_store.dart](lib/app_store.dart). These API surfaces should expose all
   the platform-specific behavior and allow for more fine-tuned control when
   needed.
