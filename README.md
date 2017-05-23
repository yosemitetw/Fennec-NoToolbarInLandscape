Firefox for iOS modification to disable URLTab bar during landscape mode. [![codebeat badge](https://codebeat.co/badges/67e58b6d-bc89-4f22-ba8f-7668a9c15c5a)](https://codebeat.co/projects/github-com-mozilla-firefox-ios) [![BuddyBuild](https://dashboard.buddybuild.com/api/statusImage?appID=57bf25c0f096bc01001e21e0&branch=master&build=latest)](https://dashboard.buddybuild.com/apps/57bf25c0f096bc01001e21e0/build/latest) [![codecov](https://codecov.io/gh/mozilla-mobile/firefox-ios/branch/master/graph/badge.svg)](https://codecov.io/gh/mozilla-mobile/firefox-ios/branch/master)
===============

This branch
-----------

This branch is for mainline development that will ship in *v8.0* with modifications to make URLtabbar totally unavailable during landscape mode.

This branch works with Xcode 8.2.1, and supports iOS 9.x and 10.

This branch is written in Swift 3.0.

Please make sure you aim your pull requests in the right direction.

For bug fixes and features for the upcoming v7.0 release, please see the *v7.x* branch.

Forewords
----------------
THIS IS NOT OFFICIAL BRANCH OF Firefox-iOS.
Please support their effort.

Building the code
-----------------

> __As of Sept. 16, 2016, this project requires Xcode 8.__

1. Install the latest [Xcode developer tools](https://developer.apple.com/xcode/downloads/) from Apple.
1. Install Carthage

  ```shell
  brew update
  brew install carthage
  ```

1. Clone the repository:

  ```shell
  git clone https://github.com/mozilla-mobile/firefox-ios
  ```

1. Pull in the project dependencies:

  ```shell
  cd firefox-ios
  sh ./bootstrap.sh
  ```

1. Open `Client.xcodeproj` in Xcode.
1. Build the `Fennec` scheme in Xcode.

It is possible to use [App Code](https://www.jetbrains.com/objc/download/) instead of Xcode, but you will still require the Xcode developer tools.

