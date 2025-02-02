## 3.0.0
Breaking changes:
- [SettingsSection, SettingsTile] title is now a Widget instead of String
- [SettingsTile] Subtitle is renamed to Description
- [SettingsTile] subtitleBelowTitle is removed. descriptionInlineIos is added.
- [CustomTile] is renamed to [CustomSettingsTile]
- [CustomSection] is renamed to [CustomSettingsSection]
- [SettingsTile.switchTile] switchValue is renamed to initialValue

Bugs fixed:
- Fixed an issue which caused the settings list to crash when the width of the list was smaller than the device screen width.

Other changes:
- Updated dependencies
- Reformatted code to latest conventions

## 2.0.1
* Drop declaring variable types.
* Use `<T>[]` to create a new array.
* Reformat code.

## 2.0.0
Initial fork from settings_ui

#### New features
* iPad like settings screen for iOS devices with large screens
  NOTE: For this to work correctly you need to specifiy the SettingsTile position. Otherwise the
  shadow won't be displayed correctly.
  
* Add color option to row

#### Other changes
* Minimum iOS deployment version is iOS 9
* Migrated from pedantic to flutter_lints
* Upgraded dependencies

## [1.0.1] - [Jul 28, 2021]
* Allow manual platform style selection
* Fixed iOS Title text getting cut off in version 1.0.0
* CustomTile implemented
* Implement titleWidget and subtitleWidget parameters
* Implement the native behaviour for the iOS switch tile

## [1.0.0-nullsafety.3] - [April 6, 2021]
* Dropped use of 'dart:io'
* Use Theme.of(context) to detect platform
* Fixed a bug with long subtitles in iOS

## [1.0.0-nullsafety.2] - [February 26, 2021]
* Enable web support
* Round borders for web and iPad settings tiles

## [1.0.0-nullsafety.1] - [February 26, 2021]
* Null safety preview release

## [0.7.0] - [February 26, 2021]
* Fixed double trailing on iOS devices
* Support for MacOS
* Fixed padding in the project example

## [0.6.0] - [February 10, 2021]
* Fixed subtitle for iOS
* Added iosChevron and iosChevronPadding for forward chevron and color in iOS.
* CupertinoSettingsItem toggle on disabled fix
* Content padding implementation

## [0.5.0] - [December 4, 2020]
* Ripple effect for Android
* Ability to setup padding and subtitle for sections
* New onPressed(context) parameter for SettingsTile, onTap() is deprecated from now on.

## [0.4.0] - [August 21, 2020]

* Custom colors support for SettingsList
* Allow physics and shrinkWrap on SettingsList
* CupertinoSettingsItemButton ripple effect
* Device preview disabled for Flutter Web 
* CustomSection implementation (possibility to add your own widget)
* Use Target Platform to determine which Settings UI to show

## [0.3.0] - [May 19, 2020]

* Change background color for dark theme in SettingsList with backgroundColor attribute.
* Ability to add trailing widgets to tiles.
* Added enabled attribute to tile.
* Flutter Web support. 

## [0.2.0] - [December 6, 2019]

* Added onTap color change for cupertino tiles.

## [0.1.1] - [December 4, 2019]

* Slight updates.

## [0.1.0] - [December 4, 2019]

* Initial release with basic SettingsTile and SettingsTile.switchTile.
