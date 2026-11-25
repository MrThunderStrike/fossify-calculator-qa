# QA Evidence Inventory - Fossify Calculator

| Evidence Category | Folder | Number of Files | What the Evidence Supports |
|---|---|---|---|
| Functional / Compatibility | evidence/qase/ | 2 PDFs | Qase execution reports document 3/3 Passed test cases on Android 16 and 2/2 Passed on Android 17. They include arithmetic calculations, division-by-zero handling, and recovery results. The Android 17 report lacks step-level Actual Results and Passed statuses for FOSS-3. |
| UI | evidence/ui/ | 4 JPGs | Screenshots demonstrate the calculator's appearance in light and dark themes, portrait and landscape layouts, button visibility and readability, and the displayed numeric input 123. They support selected UI checks but do not prove every interaction or screen-brightness condition. |
| Lifecycle | evidence/lifecycle/ | 5 PNGs | Screenshots show the displayed values associated with five exploratory lifecycle scenarios. Input preservation was reported for background/foreground transitions, screen lock/unlock, and rotation. Input resets were reported after Recent Apps dismissal and Force-stop. Screenshots do not independently prove the action sequences; the Recent Apps screenshot has a provenance limitation. |
| Installation | evidence/installation/ | 9 PNGs | Screenshots document ADB installation and uninstallation results, package absence and registration checks, and successful application launch on a physical Android 16 device and Android 17 emulator. They do not establish APK authenticity, upgrade behavior, or complete application functionality. |

**Total:** 22 evidence files - 2 PDFs and 20 screenshots.

*Evidence limitation:* Screenshots do not independently prove every test step, action, or device setting.
