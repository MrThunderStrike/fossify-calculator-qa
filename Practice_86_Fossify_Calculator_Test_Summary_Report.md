# Test Summary Report - Fossify Calculator

**Practice:** #86 - Practical QA Engineering  
**Report date:** 2026-11-24  
**Scope:** Historical Android testing conducted during November 2026  
**Status:** Accepted training portfolio report

## 1. Test Objective

The objective was to evaluate the basic functionality, user interface (UI), application lifecycle, and installation behavior of Fossify Calculator, identify observable defects, and assess the quality of the tested features.

## 2. Test Environment

- **Physical device:** OnePlus 13R, Android 16.
- **Emulator:** Android Emulator, Android 17.
- **Application:** Fossify Calculator, version 1.4.0. The version was verified on the emulator and on the physical device before its reinstall. The version on the physical device was not independently rechecked after reinstalling.

## 3. Test Execution Summary

- **Qase, Android 16:** 3/3 selected Test Cases Passed.
- **Qase, Android 17:** 2/2 selected Test Cases Passed. These runs overlap: three unique Test Cases were executed across both runs. `FOSS-4` (zero-operand addition) was tested separately on the physical device and was not included in either Qase Test Run.
- **Functional testing:** Addition, multiplication, division by zero, recovery after an error, and zero-operand addition worked in the selected scenarios.
- **UI testing:** 6/6 selected checks Passed on the physical device, against training UI requirements.
- **Lifecycle testing:** Five exploratory scenarios were observed. Input was preserved in three and reset to `0` in two. These observations do not establish requirement-based defects.
- **Installation testing:** APK uninstall, absence of the package, reinstall, package presence, launch, and basic responsiveness were verified.

## 4. Defects and Limitations

**Confirmed application defects:** None identified in the tested scope.

**Limitations:**

- The Android 17 Qase export records `FOSS-3` as Passed overall, but lacks its step-level Actual Results and Passed statuses.
- Requirements for input persistence across lifecycle scenarios were not established.
- Some UI evidence relied on user-reported observation; not every device action was independently evidenced.
- Application settings, extensive mathematical functionality, and other scenarios remained outside the tested scope.
- The physical-device application version was not reverified after reinstalling.

**Jira training note:** `KAN-4` documents a clearly labeled simulated defect and fictional verification results. It is **not** a confirmed Fossify Calculator defect and must not be counted as one.

## 5. QA Conclusion

The tested functionality performed as expected, and no application defects were confirmed in the selected scenarios. However, test coverage was limited, and several functional areas, including application settings, were not tested. The available results are therefore insufficient to confirm that the entire application is ready for release.

---

**Evidence basis:** Previously reviewed Qase run exports, device/emulator screenshots, command outputs, UI and lifecycle observations, and the project master status file. This report summarizes historical work; it does not claim a new test execution on the report date.
