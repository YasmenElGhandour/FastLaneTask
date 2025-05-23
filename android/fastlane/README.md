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

### android test

```sh
[bundle exec] fastlane android test
```

Run unit tests

### android build

```sh
[bundle exec] fastlane android build
```

Build release APK or AAB

### android internal

```sh
[bundle exec] fastlane android internal
```

Sign the AAB file manually if needed (optional step)

Upload to internal test track

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Upload to production track

### android beta

```sh
[bundle exec] fastlane android beta
```

Upload to Firebase Crashlytics (Beta Testing)

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
