# Uncommon Expo CLI Errors

This repository demonstrates some uncommon errors that can occur when using the Expo CLI, focusing on version mismatches between the CLI and project dependencies and configuration issues.  The errors often present vague messages, making them challenging to debug.

## Bug Description

Uncommon Expo CLI errors can stem from various factors, including:

* **Version Mismatches:** Incompatibilities between the global Expo CLI version and the project's dependencies (specified in `package.json`).
* **Configuration Issues:** Problems in `app.json`, `package.json`, or `eas.json` (for EAS Build) can cause build failures.
* **Native Module Conflicts:**  Underlying problems with native modules (though less common as the source of *uncommon* errors).

This repository provides examples and solutions to help diagnose and fix these elusive errors.