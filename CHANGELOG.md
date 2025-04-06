## 5.0.0

### BREAKING CHANGES

* Compatibility with `file_picker` 10.0.x. See details on their [changelog](https://pub.dev/packages/file_picker/changelog)
* Compatibility with `flutter_form_builder` 10.0.x. See details on their [changelog](https://pub.dev/packages/flutter_form_builder/changelog)
* Set minimal Flutter version to 3.29.0
* Set minimal Dart version to 3.7.0

## 4.3.0

* Add `compressionQuality` parameter, that solving app crashes on some Huawei phones
* Set minimal Flutter version to 3.27.0
* Set minimal Dart version to 3.6.0

## 4.2.0

* Upgrade file_picker to 8.x.x
* Update android and web settings on example
* Set minimal Flutter version to 3.22.0
* Set minimal Dart version to 3.4.0

## 4.1.0

* Use withData instead kIsWeb to load images
* Add `customTypeViewerBuilder` property to allow custom file viewer widget
* Built with Flutter 3.13

## 4.0.0

### BREAKING CHANGES

* Update constraints to Dart 3
* Update constraints to Flutter 3.10
* Update `flutter_form_builder` to 9.x.x. Take a look breaking changes on there changelog

## 4.0.0-dev.2

### BREAKING CHANGE

* Update constraints to Dart 3

## 4.0.0-dev.1

### BREAKING CHANGE

* Update constraints to Flutter 3.10

## 3.0.0

### BREAKING CHANGE

* Remove `types` property. Use `typeSelectors` instead
* Remove `selector` property. Use `typeSelectors` instead

### Improvements

* Remove `permission_handler` dependency
* Able desktop platforms support

## 2.4.0

* Add all desktops compatibilities
* Fix issue with initialValue not taken from form initialValues
* Improve example
* Built with Flutter 3.7

## 2.3.0

* Move maxFiles display into counterText #32 (Thanks @grundid)
* Add type selector property #31 (Thanks @grundid)
* Refactor readme
* Apply license BSD-3-clause

## 2.2.0

* Improvements to Web support
* Fix issue where errorText not showing

## 2.1.0

* Added support for web platform

## 2.0.0

* Support for FormBuilder 7.*

## 2.0.0-alpha.0

* Started integration with FormBuilder 7.*

## 1.2.0

* Add option to define custom file viewer widget
* Fixed decoration issue
* Full null safety

## 1.2.0-nullsafety.3

* Fixed null safety issue on file-viewer

## 1.2.0-nullsafety.2

* more null-safety fixes

## 1.2.0-nullsafety.1

* Upgraded packages - fix null-safety issues

## 1.2.0-nullsafety.0

* Ported to null-safety

## 1.1.0

* `flutter_form_bulder` v5 compatible

## 1.0.0

* Added support for flutter_form_builder 4.*

## 0.3.0

* Bump dependency `file_picker` plugin. Include additional `file_picker` options
* Included MIT License. Closes #3
* Fix bug caused when `maxFiles` is null. Closes #4

## 0.2.0

* Bumped up dependency versions: `flutter_form_builder`, `file_picker` and `permission_handler`
* Deprecated `fileExtension` attribute. `allowedExtensions` to be used.

## 0.1.0

* Added more options: `previewImages`, `selector`, `fileType`, `fileExtension`
* BREAKING CHANGE: Renamed `maxImages` to `maxFiles`
* Minor UI improvements

## 0.0.2

* Updated dependencies
* Started working on documentation
* Set up example project

## 0.0.1

* Initial release
