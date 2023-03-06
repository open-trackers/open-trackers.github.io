---
layout: page
title: Daily Calorie Tracker
permalink: /dct/
---

<div style="width: 250px; height: 298px;"> 
<img src="/assets/images/dct-on-wrist.jpeg" style="width: inherit" /> 
</div> 
<p/>

_A minimalist calorie tracker, for the Apple Watch, iPhone, and iPad_

## Download

Available as FREE downloads in the App Store:

- [DCT for Apple Watch](https://apps.apple.com/us/app/daily-calorie-tracker/id6445856852)
- [DCT+ for iPhone/iPad](https://apps.apple.com/us/app/daily-calorie-tracker/id6445856794)

## Features

- Simple model of user-defined categories and servings.
- ‘Quick Log’ option to add a raw calorie amount to a category.
- Define your own servings, with handy presets.
- Conveniently adjust serving size (aka intensity) when logging calories.
- Your data syncs with your private iCloud account when a network connection is available.
- Fully open source, where code is licensed with Mozilla Public License 2.0.

DCT prioritizes convenience, quick interactions, and the basic needs of the casual calorie counter.

### Quick and easy setup

- Add categories and servings in the app itself, with convenient preset names available.
- Standard set of categories available (prompted when first starting app.)
- For each serving, optionally specify weight (in g) and volume (in ml).

### History features

- Logging a serving (or through quick log) is automatically stored to your private iCloud account.
- For the WatchOS app, recent history will be stored locally for up to 1 year. Periodically run iOS app for long-term storage and review.
- The day’s history can be viewed on the Watch app. Full history can be reviewed on the iOS app for the iPhone/iPad. 

### iCloud Sync

- Your data automatically syncs with your private iCloud account when a network connection is available.
- That synced data available to the _Daily Calorie Tracker_ app running on your other devices.

### Watch App (WatchOS)

- The WatchOS app is independent, not requiring companion iOS app. Leave your iPhone at home!

### iPhone/iPad App (iOS)

- Similar to the Watch App, but adapted for iOS conventions.
- Includes long-term storage of historical completions of categories/servings.
- Review history of calories consumed (via servings and quick logs).

## Requirements

For watchOS version, version 9.1 or later

For iOS version, version 16.1 or later

## Tutorial

The _Daily Calorie Tracker_ app is relatively simple in layout and usage, but there are subtle features that may not be obvious.

The [Tutorial](/dct/tutorial/) steps through the layout and features of app.

## Source code

* [DCT Website](https://open-trackers.github.io) - Website for DCT
* [DCT for Apple Watch Source](https://github.com/open-trackers/Daily-Calorie-Tracker-Watch-App) - watchOS implementation, for Apple Watch
* [DCT+ for iPhone/iPad Source](https://github.com/open-trackers/Daily-Calorie-Tracker-Plus-App) - iOS implementation, for iPhone and iPad
* [DcaltUI](https://github.com/open-trackers/DcaltUI/) - shared layer for user interface
* [DcaltLib](https://github.com/open-trackers/DcaltLib/) - shared layer for business logic and data
* [TrackerUI](https://github.com/open-trackers/TrackerUI/) - base shared layer (with GRT) for user interface
* [TrackerLib](https://github.com/open-trackers/TrackerLib/) - base shared layer (with GRT) for business logic and data layer

To any Apple product managers who like this app, please consider Sherlocking it!

## See Also

macOS apps by the same author:

* [FlowAllocator](https://openalloc.github.io/FlowAllocator/index.html) - portfolio rebalancing tool for macOS
* [FlowWorth](https://openalloc.github.io/FlowWorth/index.html) - portfolio valuation and tracking tool for macOS

A few of the Vim plugins by the same author:

* [vim-pencil](https://github.com/preservim/vim-pencil) - Rethinking Vim as a tool for writing
* [vim-wordy](https://github.com/preservim/vim-wordy) - Uncover usage problems in your writing
* [vim-wheel](https://github.com/preservim/vim-wheel) - Screen-anchored cursor movement for Vim

## License

Copyright 2023 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.

