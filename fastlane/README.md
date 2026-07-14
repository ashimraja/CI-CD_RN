fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android lint

```sh
[bundle exec] fastlane android lint
```

Run lint

### android test

```sh
[bundle exec] fastlane android test
```

Run unit tests

### android build_debug

```sh
[bundle exec] fastlane android build_debug
```

Build debug APK (practice - no signing needed)

### android build_release

```sh
[bundle exec] fastlane android build_release
```

Build release APK (debug-signed for practice)

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Deploy to Google Play (requires service account json)

----


## iOS

### ios build

```sh
[bundle exec] fastlane ios build
```

Build iOS app for simulator (practice - no signing needed)

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Deploy to TestFlight (requires signing + App Store Connect API key)

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
