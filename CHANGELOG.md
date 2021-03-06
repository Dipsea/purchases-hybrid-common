## 1.1.0

-  Unified Android code into a single module
	https://github.com/RevenueCat/purchases-hybrid-common/pull/25
- Added podspec
	https://github.com/RevenueCat/purchases-hybrid-common/pull/26
- Set up Android tests using spek
	https://github.com/RevenueCat/purchases-hybrid-common/pull/27
- Moved dependency management away from git submodules and into Cocoapods
	https://github.com/RevenueCat/purchases-hybrid-common/pull/29

## 1.0.14

- New iOS headers for platformFlavor and platformFlavorVersion
    https://github.com/RevenueCat/purchases-hybrid-common/pull/23
- CircleCI tests integration
    https://github.com/RevenueCat/purchases-hybrid-common/pull/20
    https://github.com/RevenueCat/purchases-hybrid-common/pull/21
    https://github.com/RevenueCat/purchases-hybrid-common/pull/22
- Add xcproject and tests target
    https://github.com/RevenueCat/purchases-hybrid-common/pull/18

## 1.0.13

- Small refactor on how periods are converted to map on Android https://github.com/RevenueCat/purchases-hybrid-common/pull/17

## 1.0.12

- Improves Unity compatibility https://github.com/RevenueCat/purchases-hybrid-common/pull/15

## 1.0.11

- Converts all NSNull attributes to string or nil

## 1.0.10

- Fix crash when setting NSNull in setAttributes

## 1.0.9

- Added subscription offers support

## 1.0.8

- Fixes a call in Subscriber Attributes when setting a push token as string

## 1.0.7

- Adds compatibility with Subscriber Attributes and invalidate purchaser info cache.

## 1.0.6

- Updates completion block for checkTrialOrIntroductoryPriceEligibility

## 1.0.5

- Fixes issue with older versions of Kotlin
