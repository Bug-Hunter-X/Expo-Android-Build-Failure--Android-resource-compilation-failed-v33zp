# Expo Android Build Failure: Android Resource Compilation Failed

This repository demonstrates a common error encountered when building Android apps using Expo CLI: `Android resource compilation failed`. The error message itself is often vague and doesn't directly point to the problematic resource.

This example includes a scenario that may trigger this error and then a solution to fix it.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `expo prebuild` to prepare the build.
4. Run `expo build:android` to build the Android app.

You should encounter the `Android resource compilation failed` error, this repo contains example that will trigger the error.

## Solution

The solution file demonstrates a way to fix the issue, commonly involving identifying and correcting issues within the application resources (images, XML layouts, etc.). Inspect the `bugSolution.js` file and refer to the detailed solution within the code.

## Additional Notes

Debugging this issue can be time-consuming.  Carefully examine your project's resource files for any syntax errors, image format inconsistencies, or missing resources.  The Expo documentation and community forums can provide helpful insights.  Proper error handling within your Expo project is crucial for a smooth development experience.