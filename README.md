# Expo CLI Managed Workflow Android Build Failure

This repository demonstrates a bug encountered when using the Expo CLI's managed workflow with the `expo prebuild` command. The build process fails on Android, while succeeding on iOS.  The error message is typically non-specific, hindering debugging.

## Reproduction

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`
4. Run `expo prebuild`

The Android build should fail.

## Solution

See the `bugSolution.js` for a potential solution, often involving checking dependencies or configuration files for Android-specific settings.  The exact solution may vary depending on the underlying cause, which is difficult to isolate due to the vague error messages.