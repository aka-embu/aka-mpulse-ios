# mPulse-iOS
iOS library for mPulse Analytics

mPulse supports `CocoaPods` and `Carthage` for easy installation.

To install and use the mPulse library in your iOS project, see our [Getting Started Guide](https://developer.akamai.com/article/getting-started-mpulse-sdk-native-apps) and our **[full documentation](https://downloads.pvoc-anaina.com/sdk/mPulseSDK-iOSIntegrationGuide.pdf)**.

## Release Notes

### 21.90 (2021-Jan-19)
Fixes an issue where the SDK could malfunction due to insufficient file permissions.
Fixes an issue with cleaning old log files.
Fixes an issue that could create a name conflict when using the SDK alongside with the CocoaLumberjack library.

### 21.70 (2020-Oct-21)
Fixes an issue with missing timers/metrics added right before stopping the action.

### 21.60 (2020-Sep-24)
Fixes an issue with missing beacons at application launch.

### 21.40 (2020-Jul-02)
Fixes an issue with processing some request errors.

### 21.30 (2020-Jun-04)
Fixes a memory leak in the URL request interception mechanism.
Add support for configure with an SDK specific plist file (instead of Application’s Info.plist).

### 21.21 (2020-May-07)
Fixes an issue with missing Session ID for some beacons.
Add support for action cancellation.

### 21.13 (2020-Apr-06)
Add beacon obfuscation.
Add support for stripping query parameters.
Remove geolocation option from beacons.

### 21.12 (2020-Feb-14)
Version parity with MAP SDK.

### 21.11 (2020-Jan-28)
Add strip-frameworks script and documentation for manual installs.

### 20.41 (2019-Dec-20)
Rename framework from ‘Aka-mPulse’ from ‘MPulse’.

### 20.33 (2019-Nov-06)
Add Carthage support.
Switch from static to dynamic framework.

### 20.32 (2019-Oct-18)
Switch to unified SDK architecture that builds atop the AkaCommon framework.  This requires the inclusion of the AkaCommon SDK, which is automatically imported via CocoaPods.  See the upgrade guide included in the project to upgrade from a previous mPulse SDK.

### Older release notes 
Older release notes can be found at https://developer.akamai.com/api/web_performance/mpulse_ios_sdk/v2.html#ReleaseNotes.

