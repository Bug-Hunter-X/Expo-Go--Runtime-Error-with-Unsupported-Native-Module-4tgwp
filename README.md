# Expo Go Incompatibility with Native Modules

This repository demonstrates a common issue encountered when developing Expo applications and testing with Expo Go.  The issue arises when using a native module that's not supported by Expo Go. This example uses a hypothetical module, but the principle applies to any native module that isn't included in the Expo Go environment.

## Problem:

Attempting to use a native module within an Expo app results in a runtime error when deployed to Expo Go. The error message isn't always helpful in identifying the root cause.

## Solution:

The ideal solution is to use Expo modules or find alternatives that don't require native modules. If a native module is absolutely essential, consider using EAS Build or a standalone app build process for testing and deployment to actual devices.