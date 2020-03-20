# react-native-omniture

## Code Example

```
import RNOmniture from 'react-native-omniture'
RNOmniture.trackAction('anyString', {yourContextDataObj})
```

## Motivation

Adobe Android & iOS Mobile APIs exist for native android and iOS. So, exposing the same for React Native.

## Installation
npm install --save github:copartit/react-native-omniture <br />
Get libs for both from https://github.com/Adobe-Marketing-Cloud/mobile-services <br />
- For android, add your respective ADBMobileConfig.json for configuring your project under android/app/src/main/assets/
- For iOS
 * add ADBMobile.h (downloaded from above [url](https://github.com/Adobe-Marketing-Cloud/mobile-services)) to your React Native xcode project
 * add libsqlite.tbd, libsqlite3.0.tbd, AdobeMobileLibrary.a to dependencies **(Link Binary with Libraries in Build Phases tab in xcode for each of your project targets)**
 * Also, include your config JSON file in xcode project for each target

## API Reference
 - https://github.com/Adobe-Marketing-Cloud/mobile-services
 - https://facebook.github.io/react-native/docs/native-modules-ios.html
 - http://facebook.github.io/react-native/docs/native-modules-android.html

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)

## Versions
    1.1.0
        - Updated Android Mobile Library to https://github.com/Adobe-Marketing-Cloud/mobile-services/releases/tag/v4.18.1-Android
        - Updated iOS Mobile Library to https://github.com/Adobe-Marketing-Cloud/mobile-services/releases/tag/v4.19.1-iOS
        - Update iOS deployment target to iOS 10.3
