# Expo Android Build Failure: AGP Version Mismatch

This repository demonstrates a common error encountered when building Android apps with Expo CLI. The error stems from an incompatibility between the Android Gradle Plugin (AGP) version specified in the project and the version supported by Expo.

## Problem

The `android/build.gradle` file specifies an AGP version that conflicts with Expo's requirements.  This leads to a failure during the build process, often with unhelpful error messages.

## Solution

The solution involves determining the correct AGP version compatible with Expo and updating the project's `android/build.gradle` file accordingly.  Often, this entails consulting Expo's documentation or online resources to find the recommended AGP version for the current Expo SDK version.

## Reproduction Steps

1. Clone this repository.
2. Attempt to build the Android app using `expo build:android`.  Observe the build failure.
3. Examine the solution provided in `build.gradle.kts` (or `build.gradle`) and rebuild the app to verify the solution.