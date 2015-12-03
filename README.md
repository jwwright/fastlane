# fastlane

## Synopsis

Fastlane configuration to create an iOS app on iTunes Connect, generate/download the provisioning profile, run a custom build script, run custom commands on parse, run external script for screenshots (description of why I didn't use the fastlane screenshot tool is below), upload the app & metadata to the app store, and generate the push certificate.

## Code Example

fastlane create
fastlane update


## Installation

Place your AppIcon.png & AppIcon@2x.png in the base folder, update the Deliver file with appropriate metadata