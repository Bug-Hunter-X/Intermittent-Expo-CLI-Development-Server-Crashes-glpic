# Expo CLI Intermittent Crashes

This repository demonstrates a bug where the Expo CLI development server crashes intermittently without providing any clear error messages in the console.  The application itself continues to function correctly, but the developer loses access to hot reloading and other development server features.

## Reproducing the Bug

The exact cause of this bug is difficult to pinpoint as it occurs sporadically.  The provided `expoBug.js` file contains a simplified example project.  Running this application and consistently observing the development server for crashes may help to reproduce the issue, although there's no guarantee given the random nature of the crash.  This is a highly likely scenario for complex projects with extensive dependencies.

## Solution

The `expoBugSolution.js` file provides some potential solutions and workarounds. More investigation is needed to find a concrete solution.