# Fossify Calculator - QA Testing Project

## Project Overview
I tested Fossify Calculator to gain practical experience in Android manual testing, test execution, evidence collection, and QA reporting using Qase.

## Test Environment
Testing was performed on a OnePlus 13R (Android 16) and an Android Studio emulator (Android 17).

## Testing Scope
Testing covered selected arithmetic operations, error recovery, UI layout, themes, orientation, application lifecycle, APK installation, and basic Android compatibility.

## Test Results
- Qase Android 16: 3/3 Passed.
- Qase Android 17: 2/2 Passed (overlapping test cases).
- UI Testing: 6/6 Passed.
- Lifecycle Testing: Input was preserved in three scenarios and reset in two.
- Installation and launch checks were successful.

No confirmed application defects were found.

## Evidence
Reports and screenshots are organized in:
- `evidence/qase/`
- `evidence/ui/`
- `evidence/lifecycle/`
- `evidence/installation/`

## Limitations
Testing covered selected scenarios across two Android environments. Application settings and advanced lifecycle scenarios were not comprehensively tested. The Android 17 Qase report lacks step-level Actual Results for `FOSS-3`. Jira issue `KAN-4` was simulated, not a confirmed application defect.